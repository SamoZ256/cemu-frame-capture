# Cemu Metal frame capture

This repository contains an Xcode project configured to do Metal frame capture for Cemu.

## Requirements

- Xcode (Tested with 16.0, might not work with older versions)

## How to do a frame capture

Here is a step-by-step guide on how to do a Metal frame capture with this project:
1. Clone this repository
2. Open `CemuFrameCapture/CemuFrameCapture.xcodeproj` in Xcode
3. Alt+Click the `>` button in the top left corner
4. Click on the Executable drop down menu
5. Choose `Other...`
6. Go to where you have Cemu installed
7. Click on `Close`
8. Now you can run Cemu by clicking on the `>` button in the top left
9. Launch the game you would like to capture, and then in Xcode, click on the Metal icon in the bottom toolbar
<img width="502" alt="Screenshot 2024-11-09 at 08 00 02" src="https://github.com/user-attachments/assets/a4918686-1fe8-4167-b621-239b59247f61">

10. Click on `Capture`

Congratulations, you have successfully made a frame capture! If you'd like to make a frame capture again, you can skip to step 8.

## How to save the frame capture

Now that you have made the capture, you might want to save it so that you can open it again later. The steps for that are pretty simple:
1. Click on one of the items on the left side that says `CAMetalLayer Drawable`
2. In the top toolbar, hover with your mouse over the first toolbar item and click on it (it should say the name of your executable, `Cemu_release` in my case)
3. Click on the top most folder in the drop down manu that appears
4. A finder window with the frame capture file should appear. Move that file wherever you want.
