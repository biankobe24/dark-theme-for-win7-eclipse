dark-theme-for-win7-eclipse
===========================

This is a one-stop solution to create a completely dark theme for eclipse in win7
Here are pictures that can show you what happened after I applied this win7 theme with eclipse dark juno ui and eclipse editor theme.
https://plus.google.com/photos/114921213517944089128/albums/5952793008016527457


It's  not easy to find out a dark win7 theme that suits perfectly for eclipse dark ui theme such as Dark juno without any patchs to system files, this is because of the fact that eclipse GUI is implemented by SWT , and SWT is implemented by the lib of specific operating system.

Inorder to get a completely dark eclipse theme, 
I build this theme base on a pupolar win 7 theme on the internet named 'Concave 7',
and modified some settings in a popular eclipse editor color theme named Zenburn, created by Janni Nurmin.

Follow these steps to apply this theme:

1. Install eclipse color theme plugin, it's free.
http://eclipsecolorthemes.org/

2. Install eclipse dark juno theme to change the Majority ui color of eclipse
http://rogerdudler.github.io/eclipse-ui-themes/

3. import darkEditorTheme.xml file at the eclipse perference:
General -> Appearance -> Color theme -> import
then apply color theme 'dark editor theme for juno'

4. apply the 'dark eclipse.theme' for win 7 : 
Move the "dark eclipse" folder and "dark eclipse.theme" file to %System%\Windows\Resources\Themes
and double click dark eclipse.theme to apply it.

After finishing your tasks in eclipse, you can restore to previous win7 theme at windows control pane.

Files in dark eclipse folder is the essential files for the concave 7 theme to build a win 7 theme.
dark eclipse.theme is the setting file that tells win7 which color should display for specific ui component.

You can edit win7 theme color settings by text editor at the paragraph [Control Panel\Colors]
Here's a good tutorial that teach you how to build your ideal win 7 theme.
http://www.howtogeek.com/howto/24609/create-a-windows-7-theme-pack-from-scratch/
