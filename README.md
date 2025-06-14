# Windows-XP-Tour
A Tour program I extracted form a windows XP pro iso.
# QNA
Q: Why Did I extract it?
A: For people who missed out on it or is using it for a tutorial.
# SOME BUGS
Sometimes. toursrt and tourstart won't open.

# MORE
If you do wanna experience some pieces.
For html tour. extract the Htmltour to desktop.
C:\Users\%username%\Desktop\Tours\htmlTour
For the real tour, i don't really know
ALSO YOU NEED 7ZIP FOR THE BATCH TO WORK

# BATCH
Also don't rename it.
Extract the master file to desktop
Extract the 7z file.
Make a batch file Also might not work since it's midnight.
Copy this code:


@echo off
title Windows XP Tour Program Installer
echo Windows XP Tour Program For Windows 10 (Pre-Release 0.0.1)
echo ===========================================================
echo 1. Prepare...
timeout 1
echo 2. Copying Tour Files
cd C:\Windows\Help
mkdir ToursBe
copy C:\Users\%username%\Desktop\Windows-XP-Tour-main C:\Windows\Help\ToursBe
cd C:\Windows\Help\ToursBe
mkdir Tour
cd C:\Windows\Help\ToursBe\Tour
mkdir "mmTour"
mkdir "htmlTour"
cd htmlTour
copy C:\Users\%username%\Desktop\Windows-XP-Tour-main\Tours\htmlTour C:\Windows\Help\ToursBe\Tour\htmlTour\
cd mmTour
copy C:\Users\%username%\Desktop\Windows-XP-Tour-main\Tours\mmTour C:\Windows\Help\ToursBe\Tour\mmTour\
echo 3. Finished
echo Windows XP Tour Program For Windows 10 (Pre-Release 0.0.1)
echo ===========================================================
echo Try out the xp tour program for now.
start explorer.exe C:\Windows\Help\ToursBe\Tour\mmTour\
pause
