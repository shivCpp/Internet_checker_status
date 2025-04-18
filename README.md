# Internet Status Checker 🌐

This is a simple web application that checks the user's internet connection status, displays their public IP address, and shows their network strength.

## 🚀 Features
- Detects if the user is online or offline.
- Fetches and displays the user's public IP address.
- Shows network download speed strength (if available).

## 📸 Preview
![Internet Status Checker Screenshot](preview.png) <!-- (Optional: You can add a screenshot later) -->

## 🛠️ Technologies Used
- HTML5
- CSS3
- JavaScript (Vanilla JS)
- Fetch API (`https://api.ipify.org` for IP address)

## 📂 Project Structure

/////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

## ⚙️ How it Works
- On page load, the app checks if the device is connected to the internet.
- If connected:
  - It fetches the IP address using a public API.
  - It reads network strength from the browser (if available).
- If disconnected:
  - It updates the UI accordingly.

## 📢 Important Note
- Network strength detection (`navigator.connection`) may not work on all browsers.
- This app needs an internet connection to fetch the IP address.

## 💻 Run Locally
Clone the project and open `index.html` in your browser:
```bash
git clone https://github.com/shivCpp/Internet_checker_status.git
cd Internet_checker_status



/////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////


