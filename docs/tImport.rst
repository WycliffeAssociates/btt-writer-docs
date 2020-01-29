BTT Writer for Android: Importing a Project 
==========================================================

.. image:: ../images/BTTwriterAndroid.gif
    :width: 305px
    :align: center
    :height: 245px
    :alt: BTT Writer for Android


The BTT Writer program enables you to import a project from various sources. To import a project:
 
1. Navigate to the Home page.

2. Tap the 3-dot icon at the bottom left of the window. 

3. Tap **Import** on the menu. 

There are five options to choose from when importing to BTT Writer.
 
1. Import from Server
----------------------

This requires an Internet connection.

If you are logged into BTT Writer with a server account (either WA's or Door43's content server), choosing this option opens 
a screen where you can search for server online projects. You will be able to import only text projects; Gateway Language projects 
(Words, Notes, or Questions) are not supported in the Android version of BTT Writer.

You can search for your own or another user's project:

1. Tap in the *login name* field.

2. Type in the server user name of the user whose project you want to import.

3. Tap **Search**.

Another possibility is to search for a project by the book name or language: 

1. Remove the user name from the *login name* search field. 

2. Type in either the book abbreviation or the language code in the right field, or a combination of both (for example, fr_eph for French Ephesians). 

3. Optional: type in a user's account in the User Name field to also filter by the User.

4. Tap **Search**.

Once you have located the project you wish to import:

1. Tap the desired file to import it, or tap **DISMISS** to close the option and return to the Import Options menu.

2. If you import the file, you receive a success message. Tap **CLOSE** to close the window.

2. Import Project File
-----------------------

This process imports into the program a BTT Writer project from a file on the computer. These are files that have an extension of tstudio.

Follow this process to import a tstudio file:

1.	Tap **Import Project File** to import a project from the tablet's storage. 
 
2.	The program opens the file explorer to the directory of the BTT Writer backups. Either choose one of the backup projects or 
navigate to the desired file. Hint: you will be able to view only the files that have an extension of tstudio. 
 
3.	Tap to select the desired tstudio file, and then Tap **CONFIRM**. 
 
4.	The import begins; when the import is completed a window displays a success message. Tap **CLOSE** to close the window.

3. Import USFM File
-------------------

This process imports a file that is formatted as a USFM document. Unified Standard Format Marker (USFM) is the international standard of 
Biblical text. 

Follow this process to import a usfm file:

1.	Tap **Import USFM File** to import a file from the hard drive of the computer. 
 
2.	The program opens the file explorer to the BTT Writer backups folder. Navigate to find the desired file. 

3.	Tap the desired file, and then tap **CONFIRM**. 

4.	Tap to select the target language on the 'Choose a Target Language' screen. You can search for a language by tapping the magnifying
glass and then typing the first few letters of the language in the search field. 
 
5.	The remaining screens depend on what information is contained in the USFM file. 

    * You may be asked to choose a category. Tap the desired category to select it. 
    
    * You may be asked to choose a book name. Tap the desired book name to select it. 
    
    * You may be asked to choose the project type. Tap the desired type to select it.
    
6. A USFM Processing Summary is displayed. If no errors were found, tap **CONTINUE**.    
    
7.  The import begins, and when the import is completed a window displays a success message. Tap **CONTINUE** to close the window.

4. Import Source Text
----------------------

If you have a file containing source text that you want to use for a project, you can select this option to do so. 
Refer to the information on `<http://resource-container.readthedocs.io/en/latest/index.html>`_ to create your own source text file 
that can be imported into the BTT Writer program. 

Making the choice to import source text opens the File Explorer. Navigate to the desired source text file, tap the file name, and 
tap **Open** to import it.

5. Import from Another Device
---------------------------------
This enables you to import a project from another device.

If you have not already named your device, you are first prompted to do so. Enter a name for your device and tap **CONFIRM**.
 
On the *Import From Another Device* pop-up, select the device where the project to be imported resides, or tap CANCEL if no device is found. 

Importing Duplicate Projects
-----------------------------

If you are importing a project that is the same as a project already in the local program, you will receive a warning message that 
states: 


  *Project Already Exists*
  
  *This project already exists locally with differences in some chunks. How would you like to proceed?*
  
The possible actions for dealing with importing duplicate projects are: 

* Cancel: Tapping Cancel closes the message and the project does not get imported. 

* Overwrite Project 
 
  * We recommend that you do not choose this option if you have previously uploaded the project to the server.
 
  * If you run into difficulty you can always contact helpdesk@techadvancement.com for help or submit a ticket using the following link: `<https://www.techadvancement.com/submit-ticket/>`_.

.. warning:: Choosing to overwrite the project removes all information on the computer related to the previous local project and substitutes it with the information from the imported project.
  
* Merge Projects
  
  * The importing process continues. 
  
  * When the message that the import is complete shows, tap **Close**. 
  
  * Open the project. 
  
  * If the imported translation has recent changes, they now show in the text. 


Merge Conflicts 
---------------

When you merge an imported project with one that already exists on your device, there may be differences between the information in the 
existing project and the information that is in the imported project. This is known as a conflict. When this happens, you see this message:

     Merge Complete 

     The projects have been merged. There are 2 chunks that contain new conflicts that need your attention. 

Resolve the differences by following these steps: 

* Tap **CLOSE** to close the message window. 

* The project opens. 

* Observe that there is a triangle icon in the left column. Tap the triangle icon to view only the chunks with a conflict.

  * The text that was in the translation before the import is in the upper box.  
  
  * The text that is new is in the lower box.

  * Choose the text that has the preferred translation by tapping that box. 
  
  * Tap **CONFIRM** to use the selected text, or tap **CANCEL** to deselect the text. 
  
  * Once you confirm your preferred text, the text that you did not select disappears. 
  
Repeat all the above steps until all the conflicts have been resolved by choosing the desired translations. If you run into difficulty 
you can always contact helpdesk@techadvancement.com for help or submit a ticket using the following link: 
https://www.techadvancement.com/submit-ticket/. 

**NOTE**: resolve all conflicts before doing another export or import of the project.
