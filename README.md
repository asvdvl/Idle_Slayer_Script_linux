# How to make it run?

(Works only with the Steam Version on Windows & linux(partly))

You have three options:

1) **Run with _.exe files** (easy):

    Go under [Github Releases](https://github.com/Devil4ngle/Idle_Slayer_Script/releases) and download `Idle Runner_x64.exe` or `Idle Runner_x32.exe` depending on your [System](https://support.microsoft.com/en-us/windows/32-bit-and-64-bit-windows-frequently-asked-questions-c6ca9541-8dce-4d48-0415-94a3faa2e13d). After that run it. Do not run it from the search bar.


2) **Run with source code** (harder):

    If you do not trust the .exe files or your antivirus won't let you run it. You can download the [Source Code](https://github.com/Devil4ngle/Idle_Slayer_Script/releases) and unzip it. After that download and install [AutoIt Full Installation and AutoIt Script Editor](https://www.autoitscript.com/site/autoit/downloads/).
![image](https://github.com/Devil4ngle/Idle_Slayer_Script/assets/101042789/5f894aaf-81fa-474f-8f70-116e9e34ab1f)

    When Autoit is installed right-click the file `Idle Runner.au3` and click the option `Compile with Options` in the menu click `Compile Script`.
    It will generate .exe file which you can run.

3) **Run on linux**

    Firstly, I must immediately say that not everything works, but for me personally the functionality is enough:
    - chest hunt
    - auto ascend (useless due to non-working auto upgrades)

    What doesn't work and is critical:
    - jumping (use external bash script)
    - bonus level (for a fix, I bought a vertical magnet for a special random box)

    Installation:
    - We will use [protonhax](https://github.com/jcnils/protonhax) to run programs within the proton environment.
      
      For Arch linux/Manjaro:      
      `yay -S protonhax`
      If you don't have yay, install from the repositories:
      `sudo pacman -S yay`

      If your system package manager is not pacman then go to the protonhax repository and follow the installation section

    - Go to the game properties on Steam and set the game launch options to `protonhax init %COMMAND%`
    - If you did everything correctly, then after you start the game, the `protonhax ls` command should give the following result:
      ```
        > protonhax ls
        1353300
      ```
    - Download the exe file from the releases page and put it where you like best (the script will create a folder for its work next to the launch file, keep this in mind), for me this is my home directory `~/Idle.Runner_x64.exe`
    - Finally, you can run the script:
      ```
      protonhax run 1353300 ~/Idle.Runner_x64.exe
      ```

    If you decide to try to compile the script, the instructions remain the same(except that after installing autoit you will either have to find where the program is on the host machine or use `protonhax cmd 1353300` and run from there),
    I personally have a problem with displaying the GUI in proton and in windows
    
# Important Options

### The script will ***ONLY*** work with the following options:

- Resolution of the game needs to be ***1280x720*** and Windowed.

- ***Bonus stage 2*** will only work.

- Do NOT buy the ***Vertical Magnet***.

- Disable ***dialogue for Portal*** in setting.

- Enable ***rounded bulk*** in setting.

- Enable ***hide locked quest rewards*** in setting.

- The game must be in ***English***.

- Ascension Upgrade ***Leadership Master*** is mandatory.

- Ascension Upgrade ***Protect***  is mandatory.

- Game needs to be in ***focus***
  
- Use Anna for Ascending Heights

### For Bossfight only:

- Use the Character Anna.

- Use Bat Long bow.

- It only works after you beat him in the story mode
  
# Join Our Discord Community!

For additional assistance and to connect with a supportive community, visit our [discord server](https://discord.gg/aEaBr77UDn)

# What can it do?

Everything the game offers with Human Performance if not better. Here is a showcase.
[![Watch the video](https://img.youtube.com/vi/uDY0wCMQZX8/hqdefault.jpg)](https://www.youtube.com/watch?v=uDY0wCMQZX8)

---

Buy Me a [Coffee](https://www.buymeacoffee.com/devil4ngle) :coffee: 
