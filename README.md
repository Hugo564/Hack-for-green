# 🌿 Hack-for-green - Real-Time Offroad Vision Tool

[![Download Hack-for-green](https://img.shields.io/badge/Download-Go%20to%20Page-ff69b4?style=for-the-badge&logo=github)](https://github.com/Hugo564/Hack-for-green/releases)

## 🌲 What is Hack-for-green?

Hack-for-green is a tool that helps autonomous vehicles understand offroad terrain. It uses a camera to look at the environment and separates different parts of the scene in real time. This process is called semantic segmentation. With this, the vehicle can know where it is safe to move and where it is not.

The software works fast, processing high-resolution images without delay. It achieves this by using a technology called Reactive Streaming Architecture. This means it can provide detailed and accurate terrain information with a high score of 78.21% mean Intersection over Union (mIoU), a measure of accuracy in image segmentation.

Hack-for-green was made during the Pathway Hackathon and is ready to use on Windows computers.

## 💾 Download Hack-for-green

To get Hack-for-green, you need to visit the release page on GitHub. This page hosts the latest version of the software.

[![Get Hack-for-green Here](https://img.shields.io/badge/Get%20Hack-for-green-4b0082?style=for-the-badge&logo=windows)](https://github.com/Hugo564/Hack-for-green/releases)

Click on the link above or go directly to:

https://github.com/Hugo564/Hack-for-green/releases

On this page, look for the latest release. The release will contain one or more files. Download the file for Windows. It will usually be an `.exe` or `.zip` file.

## 🚀 Getting Started: Installing the Software

### 1. Download the Windows file

From the release page, click on the Windows file link to start the download. The file size is around 100-200 MB depending on the version.

If the file is zipped (.zip), it contains the program and any support files needed for it to work.

### 2. Open the downloaded file

- If you have an `.exe` file:
  - Double-click the file.
  - Follow any on-screen prompts to install.
  - You may need to accept a permission dialog from Windows.
- If you have a `.zip` file:
  - Right-click the file and choose "Extract All".
  - Pick a folder to extract the files to.
  - Open the folder and look for the main program file (usually `.exe`).

### 3. Run the program

After installation or extraction, double-click the main executable file to start Hack-for-green.

You should see a window or interface open. This is the main program where you can start using the software.

## 🖥️ System Requirements

To run Hack-for-green smoothly, make sure your Windows computer meets these minimum requirements:

- **Operating System:** Windows 10 or newer (64-bit)
- **Processor:** Intel i5 or equivalent AMD processor
- **Memory (RAM):** 8 GB minimum
- **Graphics:** GPU with CUDA support recommended but not required  
- **Storage:** 500 MB free space  
- **Internet:** Required for download only, not for using the software  

Having a GPU that supports CUDA will make the program faster but Hack-for-green will still work on computers without it.

## ⚙️ How to Use Hack-for-green

Hack-for-green takes input from offroad images and segments them into separate parts, such as trees, paths, rocks, or dirt. Here’s how to start processing your own images once the software is running:

1. **Choose Input Source**  
   You can either load pre-recorded images or connect a live camera if supported.  
   Click on “Open File” or “Connect Camera” in the interface.

2. **Start Processing**  
   Click the “Start” button. The program will immediately analyze images and show the segmented output on the screen.

3. **View Results**  
   The segmented image appears next to the original input, with each terrain type marked by a different color.  
   This helps you understand the terrain layout in real time.

4. **Save Output**  
   You can save segmentation results for later review. Use the “Save” option in the menu.

5. **Adjust Settings**  
   The tool allows you to tune some settings like frame rate or color scheme from the “Settings” menu.

## ▶️ Running Hack-for-green After Installation

To run the program again after the first time:

- Find the Hack-for-green shortcut in your Start menu or on your desktop.
- Double-click to open.
- Follow the steps in the “How to Use Hack-for-green” section to start segmentation.

## 🔧 Troubleshooting Common Issues

- **Program does not start:**  
  Make sure you have installed the software or properly extracted all files if using a zip.  
  Check if your antivirus has blocked the program.

- **No image input:**  
  Confirm your camera is connected and turned on if using live input.  
  If using files, check the format is supported (usually `.jpg`, `.png`, or `.bmp`).

- **Slow performance:**  
  Try closing other applications. If possible, use a computer with a supported GPU.

- **Error messages during launch:**  
  Restart your computer and try running again.

## 🛠️ More Information

Hack-for-green is built with open tools and follows the MIT license. You can review source code and reports such as test coverage, code quality, and security audits on the repository page.

If you want to learn about the inner workings or help improve Hack-for-green, visit the GitHub repository:

https://github.com/Hugo564/Hack-for-green

## 📞 Getting Help

If you have questions about using Hack-for-green, explore the "Issues" section on GitHub to see if others have the same question. You can also open a new issue for help.

For basic help:

- Check the README on GitHub.
- Review the setup instructions again.
- Look for common problems in this document.

## License

Hack-for-green is licensed under the MIT License. This means you can use, copy, and modify it freely. See the LICENSE file included in the download for details.