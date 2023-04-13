# Menu-Bar

Looking to add some custom flair to your Windows desktop? Check out our new `MenuBar` Rainmeter skin, inspired by the sleek designs of macOS and GNOME operating systems. With this customizable element, you can access various features and functions of your software applications in style. Incorporating design elements such as color schemes, fonts, icons, and layout from these two popular operating systems, our `MenuBar` customization is the perfect way to elevate your Windows desktop experience. Download now and start customizing!

![image](https://user-images.githubusercontent.com/68902530/230720743-c6aca63d-2d2a-4197-a8a5-2725c59dadf3.png)

![](https://i.imgur.com/3pXvWlr.png)

> Deviant Art: [Menu Bar for Windows](https://sameerasw.netlify.app/menubar.html)

## Directory Map

```markdown
├───@Resources
│   ├───Fonts
│   ├───icons
│   ├───Images
│   │   ├───icons
│   │   └───location
│   ├───Language
│   └───Taskbar icon
├───@Vault
│   └───Plugins
├───Corner
├───Date
├───Google
├───Menu
├───Programs
└───Skin
```

> Website Reference: https://sameerasw.netlify.app/menubar.html

## Installation

+ [Rainmeter, desktop customization tool](https://www.rainmeter.net/)
+ Just install the [SKIN](https://github.com/sameerasw/MenuBar/releases).

## Redirections

+ [My Setup by 54M33R4 on DeviantArt](https://www.deviantart.com/54m33r4/art/My-Setup-934211134)
+ Telegram Community: [TIDWIB](https://www.deviantart.com/users/outgoing?https://t.me/tidwib)

## Customizations

### Customize `TOP` Bar Default Icon

1.  Navigate to  `@Resources` and change `new-t-miniiiiii.png` with your file with same name.
2. Save the file and reload the skin via rainmeter.

### Customize `File` Context Menu

1. Navigate to `Menu` folder and open `Menu.ini`.
2. It looks something like this:

```bash
[text1]
Meter=String
Text="This PC"
FontFace=#FONT#
FontSize=#FONTSIZE#
AntiAlias=1
DynamicVariables=1
FontColor=ffffff
X=10
Y=10
LeftMouseDownAction=["C:\Users\samee\Documents\This PC.lnk"]
MouseOverAction=[!SetOption text1 FontColor bbbbbb]
MouseLeaveAction=[!SetOption text1 FontColor ffffff]
```

3. Save the file and reload the skin via rainmeter.

For example:

```bash
[text1]
Meter=String
Text="Documents" # Edit this
FontFace=#FONT#
FontSize=#FONTSIZE#
AntiAlias=1
DynamicVariables=1
FontColor=ffffff
X=10
Y=10
LeftMouseDownAction=["C:\Users\dhana\Documents"] # Change this link to the path of software you want to use.
MouseOverAction=[!SetOption text1 FontColor bbbbbb]
MouseLeaveAction=[!SetOption text1 FontColor ffffff]
```


### Customize `Programs` Context Menu

1. Navigate to `Programs` folder and open `Menu.ini`.
2. It looks something like this:

```bash
[text1]
Meter=String
Text="Calendar" # Edit this text
FontFace=#FONT#
FontSize=#FONTSIZE#
AntiAlias=1
DynamicVariables=1
FontColor=ffffff
X=10
Y=10
LeftMouseDownAction=["C:\Users\samee\Documents\Shortcuts\Calendar"] # Change this link to the path of software you want to use.
```

3. Save the file and reload the skin via rainmeter.

For example:

```bash
[text1]
Meter=String
Text="CCleaner"
FontFace=#FONT#
FontSize=#FONTSIZE#
AntiAlias=1
DynamicVariables=1
FontColor=ffffff
X=10
Y=10
LeftMouseDownAction=["C:\Users\dhana\Desktop\CCleaner.exe"]
```

### Customize `Google` Context Menu

1. Navigate to `Google` folder and open `Menu.ini`.
2. It looks something like this:

```bash
[text1]
Meter=String
Text="Gmail - Personal" # Edit this text
FontFace=#FONT#
FontSize=#FONTSIZE#
AntiAlias=1
DynamicVariables=1
FontColor=ffffff
X=10
Y=10
LeftMouseDownAction=["https://mail.google.com/mail/u/0/"] # Change this link to the path of software you want to use.
```

3. Save the file and reload the skin via rainmeter.

For example:

```bash
[text1]
Meter=String
Text="GitHub"
FontFace=#FONT#
FontSize=#FONTSIZE#
AntiAlias=1
DynamicVariables=1
FontColor=ffffff
X=10
Y=10
LeftMouseDownAction=["https://github.com/"]
```
