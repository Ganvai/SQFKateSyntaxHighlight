Syntax Highlighting XML for Kate Editor. Initially created by jamesxmcIntosh but since it was not updated anymore I chose to update it myself. Still, huge credits go to JMX and his work. You can find his original file here: (https://github.com/jamesxmcintosh/sqf-ksyntaxhighlighting).

Open issues:
- A lot of double entries
- I am not sure if I like the seperation of OFP, Arma 2 and Arma 3 commands, although ultimately it doesn't make a difference
- Not sure about the initial formating - might work on this later on but right now it is what it is.

Install sqf.xml in **org.kde.syntax-highlighting/syntax/**, which is located in your user directory.
Usually it is:

<table>
    <tr>
        <td>For local user</td>
        <td>$HOME/.local/share/org.kde.syntax-highlighting/syntax/</td>
    </tr>
    <tr>
        <td>For Flatpak packages</td>
        <td>$HOME/.var/app/<em>package-name</em>/data/org.kde.syntax-highlighting/syntax/</td>
    </tr>
    <tr>
        <td>For Snap packages</a></td>
        <td>$HOME/snap/<em>package-name</em>/current/.local/share/org.kde.syntax-highlighting/syntax/</td>
    </tr>
    <tr>
        <td>On Windows®</td>
        <td>&#37;USERPROFILE&#37;&#92;AppData&#92;Local&#92;org.kde.syntax-highlighting&#92;syntax&#92;</td>
    </tr>
    <tr>
        <td>On macOS®</td>
        <td>$HOME/Library/Application Support/org.kde.syntax-highlighting/syntax/</td>
    </tr>
</table>

If you are on a Distro like Bazzite and don't find any of these folders, just create your own folder tree like:

/home/*yourUserName*/.local/share/org.kde.syntax-highlighting/syntax/

and drop the file in here. To check if the installation worked you can just open an SQF file or look in "Settings / Configure Kate... / Color Themes / Theme Editor / Highlighting Text Styles / Scripts/SQF" (it shows up automatically if you have an SQF file open and as active window).

For more details, see ["The Highlight Definition XML Format" (Working with Syntax Highlighting, KDE Documentation)](https://docs.kde.org/?application=katepart&branch=trunk5&path=highlight.html#katehighlight-xml-format).


Report any issues you find. I am new to this and never done this before.
