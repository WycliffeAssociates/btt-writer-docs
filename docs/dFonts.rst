BTT Writer for the Desktop: Adding Fonts
==========================================================

.. image:: ../images/BTTwriterDesktop.gif
    :width: 180px
    :align: center
    :height: 200px
    :alt: BTT Writer for the Desktop

If you install a new font on your Windows 10 PC, how can you get BTT Writer to use that font? Fonts of the target and source text can be changed in BTT Writer's General settings, but what if your new font is not visible in the font list?

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

You should now be able to see the font in BTT Writer. If you don’t see it at first, you may need to close and reopen BTT Writer.
