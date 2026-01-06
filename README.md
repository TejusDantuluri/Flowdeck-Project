# Flowdeck-Project
This is a simple instruction set; more in-depth instructions will come soon.
Download the Windows file on your host PC and the Pi files on the Pi you will use.
Open up the Windows files and edit config.json using your text editor.
Before you edit the audio devices, you will have to run find_audio_devices.py to get the two currently used devices.
Copy and paste into the indicated area in config.json.
You can change the audio groups, the voice setting presets, and the macro pad to open or do what you need.
You are done with your PC.

Go to your Raspberry Pi files and open up pi_config.json.
This is where you will find and enter the server address from your host PC.
In the terminal on your Windows PC, you have to type "ipconfig" and scroll down till it tells you the IPv4 address.
Copy and paste onto your Pi where indicated.

Now, on your PC, launch the "start_server" batch file.
Do the same for the shell script file on your Pi. Now it should show an active connection between the two,
and it should be running!

I use a Raspberry Pi 4 with a capacitive touch screen at 5 inches. If you do use a different display with a different aspect ratio,
you may need to edit the Kivy file on your Pi to suit the resolution.
