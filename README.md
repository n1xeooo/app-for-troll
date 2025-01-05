This code performs the following actions:
1. On launch, it opens a video in full-screen mode on top of all windows (except for the Start menu and Ctrl+Alt+Delete).
2. It clones itself to the path C:\Program Files (x86)\Steam under the name steamgameoverlay.exe (the path and file name for cloning can be easily changed in the code).
3. From there, it adds itself to the system's startup programs, making deleting the main file ineffective for removing the issue.
I have already disguised this program as a legitimate Steam file, but you can modify it for your own purposes. The code uses a video file named video.mp4 located in the root directory. You can replace it simply by adding your own video with the same name. Icon also changeable. Make staps also you do with video and recompile.

Code has been written on Python in PyCharm
