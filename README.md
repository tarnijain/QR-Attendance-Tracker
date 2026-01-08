
# QR Attendance Tracker

This is a simple web application made to mark attendance using QR codes.

The app uses the device camera to scan a QR code, extracts participant details from it, and marks the participant as present. If the same QR code is scanned again, the app detects it as a duplicate and shows a warning message.

This project was built as part of a student task to understand basic JavaScript logic, DOM manipulation, and QR code scanning.

---

## Features

- Scan QR codes using the device camera
- Extract participant details from QR code data
- Mark participants as present
- Prevent duplicate attendance entries
- Display attendance status and participant details on screen
- Show a simple list of attendees

---

## Technologies Used

- HTML
- CSS
- JavaScript
- html5-qrcode library

---

## How It Works

1. Click the **Scan Now** button to start the camera.
2. Point the camera at a QR code.
3. The app reads the QR code data.
4. If the participant is new, they are marked as present.
5. If the QR code was already scanned, the app shows a duplicate message.
6. Attendance details are displayed on the screen.

---

## QR Code Format

The QR code can contain JSON data like:

```json
{
  "id": "101",
  "name": "Student Name"
}
