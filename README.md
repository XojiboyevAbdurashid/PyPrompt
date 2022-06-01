# PyPrompt

Making a terminal based in Python 3.10.1

<a href="https://replit.com/github/joalricha869/PyPrompt"><img src="https://raw.githubusercontent.com/BinBashBanana/deploy-buttons/master/buttons/remade/replit.svg" alt="Deploy On Replit"></a>
<a href="https://glitch.com/edit/#!/import/github/joalricha869/PyPrompt"><img src="https://raw.githubusercontent.com/BinBashBanana/deploy-buttons/master/buttons/remade/glitch.svg" alt="Deploy On Glitch"></a>

### Engine based on Termithon by idkDwij

Inspired by: [This repo!](https://github.com/IdkDwij/Termithon)


## Run this in your PC

First download python from [python.org](https://python.org). Once it's installed, Run the PyPrompt file from the 'Releases' tab. 

### TO RUN IN WINDOWS TERMINAL

Name the PyPrompt file to prompt.py and put it on the root of the C drive. In Windows Terminal, make a new profile, named PyPrompt. use the following command. ```python.exe C:\prompt.py``` or ```py C:\prompt.py``` Run that new profile. PyPrompt should work.

### Why isn't there an ```.exe``` version?

Using pyinstaller it gives me an error (_apparently about the main() function. idk why it happens_)

## What is this PyPrompt Development Kit?...

It's the necessary tools needed to compile PyPrompt to a ```.pyc``` format. (_You may need to re-compile for different computers. Else it won't work..._)

I will upload it soon. Check this document regularly... I might just put it HERE: Download [PyDevKit](https://drive.google.com/file/d/1TtT72DXU6JIxWEfVa3aCU3BXcDBVyjmb/view?usp=sharing)

You may need to delete the compiled version i pre made. It might not work. Run ```compilePrompt.py``` or whatever its called and it will compile the necessary files needed.


## Features:

Many...

```
'''
  _____       _                       _           _ 
 |_   _|     | |                     | |         | |
   | |  _ __ | |_ ___  __ _ _ __ __ _| |_ ___  __| |
   | | | '_ \| __/ _ \/ _` | '__/ _` | __/ _ \/ _` |
  _| |_| | | | ||  __/ (_| | | | (_| | ||  __/ (_| |
 |_____|_| |_|\__\___|\__, |_|  \__,_|\__\___|\__,_|
                       __/ |                        
                      |___/                         

DIR                     (Integrated dir/ls command. To use vanilla dir on Windows, Enter CMD Mode and type dir.)
IP                      (Gives you your IP)
HOSTNAME                (Gives you your Computer's ID)
MAC                     (Retrieves the Physical MAC Address of The Device)
PING                    (lets you ping a website)
CALC                    (A simple calculator)
PASSGEN                 (A very efficient password generator)
SYSINFO                 (Gets relevant system info)
TEST                    (Tests PyPrompt Sample Command)
MAILGEN                 (Generates dummy E-Mail Addresses)
VER                     (Reports PyPrompt Version)
CLEAR                   (Clears screen)
LOADBARTEST             (Tests the loadbar)
INTRO                   (Displays initial text)
SQRT                    (Enter a number and it will calculate the square root)
DATE                    (Displays date)
CD                      (Navigate through folders) (NOTE: Applicable on PyPrompt Mode ONLY!. If you use CMD/BASH directories will change)
IPLOCATION              (Find the physical location of your IP address)
SPEEDTEST               (Speedtest.net but built into PyPrompt!)
ENCRYPT                 (Uses the RSA Algorithm to encrypt a message!)
TROUBLESHOOT            (Troubleshoots extra modules neccessary for PyPrompt to run)
SSH                     (An SSH Client made in Python) (To use vanilla ssh use either CMD/BASH MODE)
MACOSDOWNLOADER         (A simple macOS downloader) no longer based on gibMacOS
FILESEARCH              (Searches files via their file name)
FILEDOWNLOADER          (Download any file via their url)
UNHELP                  (i'm not sure what this is. it just exists.)
LOCATOR                 (Locate basically any location in the planet)
DEVHELP                 (Detailed info about PyPrompt useful for troubleshooting)
COMPILER                (Compile any standard Python file to a *.pyc format)
PYVIM                   (Vim clone 'MADE BY jonathanslenders On GitHub')

PyPrompt Modes:

CMD Mode (If usual Windows Shell commands are broken in PyPrompt, just use the 'cmd' command and you are in vanilla Command Prompt.)
         (NOTE: You are still in the PyPrompt App. Exit by typing exit in CMD Mode)
Bash Mode (Same as CMD Mode but you can run UNIX commands. Again, this is just a sidemode. You can return by typing exit or logoff.)

'''
```



## Contributing
Anyone can contribute with this project! Just open up an issue or pull request and I will review what you will be adding/removing/changing and might add it in. 


## License
[GPL 3.0](https://www.gnu.org/licenses/gpl-3.0.en.html)


## Credits

Termithon Shell/Kernel: [idkDwij](https://github.com/idkDwij)  |  [Termithon](https://github.com/idkDwij/Termithon)

Calculator Fix: [BigBoyTaco](https://github.com/BigBoyTaco)   |   [BigBoyTaco Studios](https://github.com/BigBoyTacoStudios)

Majority of Commands (slightly modified to work in PyPrompt + Bug Fixes): [hastagAB/Awesome-Python-Scripts](https://github.com/hastagAB/Awesome-Python-Scripts)  (_this helped alot_)
