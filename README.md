# test


## Step 1: Unity Setup

* Unity Hub
  * Go to: https://unity3d.com/get-unity/download
  * Download Unity Hub
  * Run the Unity Hub Setup file
* License
  * After setup is complete and Unity Hub is open, you should see this at the bottom of the window:
  ![Unity Hub Menu](https://i.paste.pics/fcbee8923b6678a27448515de12622be.png)
  * Click “Manage License”
  * Click “Login”
  * Click “Sign in with google”
  * Click “Activate New License”
  * Select “Unity Personal” + "I don't use Unity in a professional capacity."
* Installing Unity
  * Navigate to “Installs” within Unity Hub
  * Click “Add” and select the first version of Unity shown under "Official Releases" (download might take a while)

## Step 2: workshop3 Folder
* Create a folder named "workshop3" somewhere. This will be used to keep the workshop files organized.

## Step 3: Download Project Files

* Press the green "Code" button and click "Download ZIP".
* Save the folder to your computer inside the "workshop3" folder and extract the contents.

## Step 4: Download Python 3.7.9
### Windows
* Go to: https://www.python.org/downloads/windows/
* Scroll down until you see Python 3.7.9
* Click on "Windows x86-64 executable installer"
 
### Mac OSX / Linux
* Go to: https://www.python.org/downloads/mac-osx/
* Scroll down until you see Python 3.7.9
* Click on "macOS 64-bit installer"
 
 
## Step 5: Creating the Virtual Environment

Open a Terminal (OSX/LINUX) or CMD (WINDOWS) and follow the below instructions

Change directories to "workshop3" folder
```
cd /path/to/workshop3/
```

### Mac OSX / Linux

Install virtual environment tool:
```
pip3 install virtualenv
```

Create and activate virtual environment:
```
python3 -m venv blockrunnerenv

source blockrunnerenv/bin/activate
```

### Windows

Install virtual environment tool:
```
pip3 install --user virtualenv
```

Create and activate virtual environment:
```
py -m venv blockrunnerenv

blockrunnerenv\Scripts\activate.bat
```
