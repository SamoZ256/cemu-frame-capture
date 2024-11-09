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
<img width="1552" alt="Screenshot 2024-11-09 at 08 10 01" src="https://github.com/user-attachments/assets/7a16c6f1-3c98-4a5a-a5c6-94a8fa97225f">

2. In the top toolbar, hover with your mouse over the first toolbar item and click on it (it should say the name of your executable, `Cemu_release` in my case)
<img width="1552" alt="Screenshot 2024-11-09 at 08 10 11" src="https://github.com/user-attachments/assets/fc26716a-0c43-446e-bc44-109ba20b18b8">

3. Click on the top most folder in the drop down manu that appears
<img width="1552" alt="Screenshot 2024-11-09 at 08 10 20" src="https://github.com/user-attachments/assets/b38eea02-92ff-4d94-9f1a-7b2904c10bbc">

4. A finder window with the frame capture file should appear. Move that file wherever you want.
<img width="1032" alt="Screenshot 2024-11-09 at 08 10 26" src="https://github.com/user-attachments/assets/846d01c3-233c-426d-adfa-1c3185cae450">


## Notes

There are a few things to be aware of:
- The frame capture files can get really big sometimes. I recommend zipping them if you plan on sharing them, it drastically reduces their size.
- On some computers, you won't be able to close Cemu after doing a frame capture (even with `Force Quit`). It will continue to occupy a part of the RAM, and the only way (that I am aware of) to close it is to restart your computer.
