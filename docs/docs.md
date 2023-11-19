# Documentation and tutorials

## How to use

### Pin to the "Quick Access" bar of the WPS Office or PowerPoint icon on the taskbar

#### On Windows 10 and below devices:

Drag and drop the Screen Blackening PPT onto the pinned taskbar icon, and when the "Pin file to quick access" prompt appears, release it. After that, right-click (or long press) this icon to find the shortcut link to the PPT.

#### On Windows 11 and above devices:

First open the Screen Blackening PPT, pin WPS Office or PowerPoint to the taskbar, right-click (or long press), find and pin the PPT in the recently accessed files, and it becomes a shortcut link.

![1](https://github.com/Nick-DL/Dead-Dog/assets/106737278/6351dd4c-8ea0-4de0-8ae3-a4fb6eb083fb)

### Create a shortcut and pin it to the taskbar

Because the taskbar cannot directly put shortcuts of ordinary files, only .exe files, and Windows 11 has stricter restrictions on adding than previous versions, here is the most reliable method.

#### Create a shortcut

Create a new shortcut on the desktop, fill in the file address `"C:\Windows\System32\taskkill.exe"` or other obscure harmless program, enter the shortcut name "Screen Blackening", click "finish", and drag the newly created shortcut to the taskbar.

#### Perfect the shortcut

Right-click the shortcut on the taskbar, right-click "Screen Blackening", click properties, and open the shortcut modification page.

![2](https://github.com/Nick-DL/Dead-Dog/assets/106737278/ae84fc93-43c6-4e4d-b3a4-94d3b731c293)

Right-click the Screen Blackening PPT, click "copy file address", paste and fill in the "target" of the shortcut, fill in the "start position" as empty, "shortcut key" can be filled in (press when the cursor flashes) Alt + Shift + D;

Download the Screen Blackening .ICO icon from [here](https://github.com/Nick-DL/Dead-Dog/blob/main/icon/dead_dog_icon_256px.ico), click "change icon", select the downloaded icon, then click OK, OK, save the shortcut settings and restart the computer to see the configured taskbar shortcut.

![3](https://github.com/Nick-DL/Dead-Dog/assets/106737278/0a22ee05-7326-419d-8171-08cad4359c4b")

### Add Screen Blackening to task scheduler

Win + R to open run, enter taskschd.msc to open the task scheduler, switch to "Task Scheduler (Local) > Task Scheduler Library", download the Screen Blackening task scheduler configuration file from [here](https://github.com/Nick-DL/Dead-Dog/blob/main/docs/dead_dog.xml), click "import task..." on the right to select and import.

After that, please calibrate whether the trigger time, action (path to start the program, important!) in the automatic script are filled in correctly! If not, right-click the Screen Blackening automatic trigger, click "properties" to modify! After the modification is completed, please right-click "run" to do a test!

![4](https://github.com/Nick-DL/Dead-Dog/assets/106737278/1f077579-33a1-41e6-900e-58bb8cdab68d")

## Precautions

If you use "Screen Blackening" to temporarily make the screen black, **please make sure there are no floating balls or floating windows on your computer**! If you use tools like Epic Pen, remember to turn it off when the screen is black, and set the instruction to close its process in the task scheduler!

"Screen Blackening" is not suitable for display-type electronic teaching devices, because these devices always have some backlight when the screen is black! Therefore, "Screen Blackening" **is only suitable for computers that use projectors as monitors**!

"Screen Blackening" **is only suitable for temporarily making the screen black**, and it is strongly discouraged to keep the screen black for a long time (such as an afternoon, a night)! April 22 is Earth Day, reducing the meaningless running time of the computer, reducing the power consumption, is to reduce carbon emissions, contribute to Mother Earth! 