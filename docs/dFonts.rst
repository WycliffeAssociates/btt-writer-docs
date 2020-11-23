BTT Writer for the Desktop: Adding Fonts
==========================================================

.. image:: ../images/BTTwriterDesktop.gif
    :width: 180px
    :align: center
    :height: 200px
    :alt: BTT Writer for the Desktop

If you install a new font on your computer, how can you get BTT Writer to use that font? Fonts of the target and source text can be changed in BTT Writer's General settings, but what if your new font is not visible in the font list?

For Windows
-----------

Windows 10 stores user-installed fonts in the Microsoft\\Windows\\Fonts subdirectory of the user’s local directory: 


   c:\\Users\\[user name]\\AppData\\Local\\Microsoft\\Windows\\Fonts 
   
Microsoft can use these fonts in its applications, such as Word, but BTT Writer looks for fonts only in the c:\\Windows\\Fonts directory.

To fix this, you can copy the font file from the user’s local directory to the Windows Fonts directory. However, you can’t use File Explorer to do this, because when you open c:\\Windows\\Fonts in File Explorer, it displays all installed fonts, including the user-installed ones that are not actually in that directory.

To copy the font to where it is visible to BTT Writer, you must run the command prompt as an administrator and then use the copy command to copy the font file from the user's local directory to the c:\\Windows\\Fonts directory. To do this, perform the following steps:

1.	Press the **[Windows] key** (or click the Windows icon in the task ribbon) to invoke the Start menu.

2.	Start typing the word **command** to search for the command prompt.

3.	Windows displays the search results. If Command Prompt is not highlighted, click the **right arrow** next to Command Prompt.

4.	On the right side of the window, click **Run as Administrator**.

5.	If prompted to allow the app to make changes, click **Yes**.

6.	In the command prompt screen, issue the following command:

    **copy c:\\Users\\[user name]\\AppData\\Local\\Microsoft\\Windows\\Fonts\\[file name] c:\\windows\\fonts**
    
    where [file_name] is the name of the font file (such as bamini.ttf) and [user name] is the directory that corresponds to the user who installed the font.

You should now be able to see the new font in BTT Writer's font list when you try to change the target or source text font in settings. If you don’t see the new font at first, try closing and reopening BTT Writer.

For MAC
-------

For Mac users, the same problem can be resolved by copying the font to /Library/Fonts.

For Linux
---------

For Linux users, install the font to /usr/share/fonts/truetype. Although the other fonts in this folder are in subfolders, if you put the fonts you install into subfolders, BTT Writer will be unable to find them.
