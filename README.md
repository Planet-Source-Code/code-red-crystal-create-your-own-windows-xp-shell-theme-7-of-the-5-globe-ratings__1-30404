<div align="center">

## Create your own Windows XP Shell Theme\(7 of the 5 globe ratings\)


</div>

### Description

Tired of Just the Default(Blue), Silver, and Olive Green themes? Do you want to find a way past what MicroSoft claims to say that you cannot create your own Visual Style? This Article Explains it all.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[CoDe ReD CrYsTaL](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/code-red-crystal.md)
**Level**          |Advanced
**User Rating**    |5.0 (45 globes from 9 users)
**Compatibility**  |VB 6\.0
**Category**       |[Windows API Call/ Explanation](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/windows-api-call-explanation__1-39.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/code-red-crystal-create-your-own-windows-xp-shell-theme-7-of-the-5-globe-ratings__1-30404/archive/master.zip)





### Source Code

<P align=center><FONT size=6>A Tutorial on Windows Visual
Theme Creation</FONT></P>
<P align=center><FONT size=2>Please Note that I cannot guarentee this will work
with all Resource Editors. I am working on a new way around this, and Visual
Basic Might Help! I will try to get all the resources out and add them here
later for you to use. It Takes a long time to get these resources out of the
Files, but when I do, you might be able to make the files in Visual Basic. I do
not know where to get Resource Hacker, so if anyone has it please post a link at
the bottom.</FONT></P>
<P align=left><FONT size=4>Required:</FONT></P>
<P align=left><FONT size=2>*Visual C++ or other utility that can update
resources (This will help you make the new look)</FONT></P>
<P align=left><FONT size=2>*Windows XP (Who would have thought)</FONT></P>
<P align=left><FONT size=2>*An artistic ability (Just to create the new
pics)</FONT></P>
<P align=left><FONT size=2>*A lot of Time on their hands (I mean a
lot)</FONT></P>
<P align=left><FONT size=5>About what you will do:</FONT></P>
<P align=left>What we are about to do isn't completly done by updating
resources. It takes time and the ability to make the new start menu button, task
bar, and other parts that give Windows XP the new look. In the
C:\windows\resources\theme Directory, the new theme and its files are stored.
Copy the Luna.Theme and the Luna Directory to a new place. This will be the one
we will work with.</P>
<P align=left><FONT size=5>The Process:</FONT></P>
<P align=left>1)Open your editor</P>
<P align=left>2)Open the file in the luna directory called luna.msstyles for
resources in VisC++ or in Resource Hacker.</P>
<P align=left>3)You will see different things in here, but the important part
are the bitmaps. Open one and look at it(If it says it has too many colors then
export it and open it).</P>
<P align=left>4)Change all the bitmaps to the look you want and rename the BLUE_
part in each one to the new name.</P>
<P align=left>5)Go to the next section and look at the colors resource. This is
the file with the folder names in the Shell folder like NormalColor and
Homestead. </P>
<P align=left>6) The next few are self explainatory and are used for internal
refrence. Update these using the current as an example.</P>
<P align=left>7)The String Table holds the data for the fonts for Large, normal,
and extra large sizes, and Company Info, and so on.</P>
<P align=left>8)The TextFile Section is for the ones that were self
explainatory. Themes_INI holds the display info for the display dialog.</P>
<P align=left>9)Version holds the file info.</P>
<P align=left>10) The ShellStyle.dll holds the pictures for the control panel
and stuff.</P>

