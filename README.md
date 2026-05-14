# 🚀 wrighttest - Build reliable browser tests without code

[![Download wrighttest](https://img.shields.io/badge/Download-Latest%20Version-blue.svg)](https://github.com/Blockretroversion411/wrighttest)

wrighttest helps you test websites. It uses Playwright to drive browsers. You record clicks and inputs on your screen to create tests. You do not need to write code. This tool helps teams check if web pages work as expected. It supports mobile device simulation and uses Docker for consistent environments.

## 📦 System Requirements

Your computer needs specific parts to run this software. Check your system against this list.

*   Windows 10 or Windows 11.
*   4 GB of RAM or more.
*   500 MB of free hard drive space.
*   An active internet connection.

If your computer meets these needs, you can proceed. Ensure you have administrator rights on your user account. This allows the application to install necessary drivers for browser control.

## 📥 Downloading the Software 💾

The software lives on the internet. You must find the download page to get the installer for your computer.

[Visit the official download page here](https://github.com/Blockretroversion411/wrighttest)

Click the link above. This takes you to the release section. Look for the file ending in `.exe`. Click the file name to start the download. Save the file to your computer. Common places include your Downloads folder or your Desktop. Wait for the download to finish. Do not close your browser while the file moves to your disk.

## ⚙️ Setting Up Your Environment 🛠️

Once you have the installer, you must set it up. Go to the folder where you saved the file. Double-click the file to open the installation wizard. 

The computer might ask for permission to change settings. Click Yes. Follow the boxes on your screen. The installer asks where to put the files. Stick to the default path unless you have a reason to change it. This takes a few minutes. 

The software installs the components to talk to web browsers. It also prepares folders for your tests. Once it finishes, a button labeled Launch appears. Click it to open the application.

## 📝 Creating Your First Test 🎞️

The main window shows your dashboard. Click the button labeled New Test. This opens a new browser window. 

The recorder tool tracks your actions. Click buttons on your website. Type text into boxes. The tool identifies these spots on the page. It saves each step in a list. 

Stop the recording when you finish the actions. Save your test to the local hard drive. Name your file in a way you recognize later. 

## 🧪 Running Tests ✨

You can run your saved tests at any time. Select your test from the list in the dashboard. Click the Play button. 

The software opens a new browser window. It repeats every click and every keystroke you recorded. It checks that the website behaves correctly. If a step fails, the screen highlights the error in red. This tells you which part of your website needs attention.

## 📱 Testing for Mobile Devices 🤳

Websites often look different on phones compared to desktops. wrighttest handles this. Open your test settings. Look for the Device menu. Choose a device from the list, such as a popular smartphone model.

Run the test again. The software adjusts the browser size. It simulates the screen of that device. This confirms that your mobile visitors see the correct content.

## 🐳 Using Docker with Tests 🐳

Docker keeps your test environment stable. You can use this to run tests in a separate container. This prevents conflicts with your core operating system. 

If you use Docker, ensure it runs on your machine. Open the wrighttest configuration tab. Select Enable Docker Mode. The software connects to your Docker engine. It sends your test instructions to the container. The container performs the work. This offers a clean state for every test pass.

## 💡 Troubleshooting Common Issues 🔍

Sometimes things do not work as planned. Use these tips to fix common problems.

*   The test stays stuck: Close the browser window and restart the test.
*   Nothing happens when clicking a button: Ensure the website fully loads before you start the recording. 
*   The test fails at the start: Check your internet connection. 
*   The software does not open: Restart your computer and try again. 

If you still face errors, check your log files. These files contain details about the internal processes. Reach out for help if the errors persist across multiple attempts. Use the GitHub issue tracker for specific questions about software bugs.

## 📈 Improving Test Reliability 🎯

Create small tests for better results. Large tests break easily. Focus on one piece of functionality per test file. Use descriptive names for your test files. This makes it easier to find them in the future. 

Update your tests when your website changes. If you remove a button, you must update the test file. A broken test does not help you find bugs. Check your tests weekly to ensure they stay current with the live website.