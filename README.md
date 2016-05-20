# SPECIFY
Illustrator script to specify dimensions of an object, or to specify the dimensions between two objects


[![GitHub release](https://img.shields.io/github/release/adamdehaven/Specify.svg?maxAge=3600)](https://github.com/adamdehaven/Specify/archive/master.zip) 
[![GitHub commits](https://img.shields.io/github/commits-since/adamdehaven/Specify/v1.0.svg?maxAge=3600)](https://github.com/adamdehaven/Specify/commits/master) 
[![GitHub issues](https://img.shields.io/github/issues/adamdehaven/Specify.svg?maxAge=3600)](https://github.com/adamdehaven/Specify/issues) 
[![license](https://img.shields.io/github/license/adamdehaven/Specify.svg?maxAge=3600)](https://raw.githubusercontent.com/adamdehaven/Specify/master/LICENSE)

##### Save to Default Scripts
> To allow the script to show as an option within the default `Scripts` menu, save the script in the following location _(path shown is for Mac. Your actual path may vary)_
> ```
> Applications > Adobe Illustrator [YOUR VERSION] > Presets > en_US > Scripts
> ```

Alternatively, you may save the script in a folder of your choosing.

## REQUIREMENTS
1. Must have an open document in Illustrator
2. Must have 1 or 2 objects selected via Illustrator's Selection Tool (V) or Direct Selection Tool (A)

## HOW TO RUN
If you saved the script as [described above](#save-to-default-scripts), you should be able to run the script (after selecting one or two objects in the document) by navigating within Illustrator to:
```
File > Scripts > Specify
```
If you chose an alternate location to save the script, you may run by using the following path, and selecting the script file once you navigate to your designated folder:
```
File > Scripts > Other Script...
```

#### Dimension a Single Object
Select a single object (or group) on your artboard and [run the script](#how-to-run) within Illustrator.

With a single object selected, the script will display a dialog box and will specify the single dimension you chose. The dialog allows you to choose which dimension to specify (top, right, bottom, or left) which also corresponds to the placement of the dimension line and text.

#### Dimension Between Two Objects
Select two objects and [run the script](#how-to-run) within Illustrator

With two objects selected, the script will display a dialog box and will specify the single dimension between the two chosen objects. The dialog allows you to choose which dimension to specify (top, right, bottom, or left) which also corresponds to the placement of the dimension line and text.

#### Units
The script automatically dimensions objects based on the Document's default units. To dimension in different units (i.e. Inches, Centimeters, etc.) follow the instructions below:
> 1. In your document, select show Rulers via `View > Rulers > Show Rulers` ( <kbd>⌘Cmd</kbd> + <kbd>R</kbd> on Mac, <kbd>Ctrl</kbd> + <kbd>R</kbd> on PC )
> 2. Right click on the Ruler, and select your desired units. Otherwise, the script will use the Document's selected units by default.
> 3. Run the script and you will now get output as shown in the example below
![specify-example-with-units](https://raw.githubusercontent.com/adamdehaven/Specify/master/specify-example-with-units.jpg)

The units label is optional. A checkbox is included in the Specify dialog box that allows the user to turn the units label on or off.
##### Examples
Units Label On: 
> **220.00 px**

Units Label Off: 
> **220.00**