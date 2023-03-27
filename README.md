# Modifying-Auto-Completes-in-Sublime-Text-3

Sublime Text 3 stores its packages in .sublime-package zip files (the location varies by OS), you can't just go to the Packages folder and see everything. However, there is an excellent plugin called PackageResourceViewer (available via Package Control) that can, among other things, extract files or whole packages to the Packages directory.

__***Guide To modify the auto complete snippets in Sublime Text 3***__

Once you've installed the plugin:

**Step1:** 
You have to open Package Resource Viewer from Command Pallete

   Command Pallete : CTRL + SHIFT + P\
   type prv to get the **P**ackage **R**esource **V**iewer options.
   
   
&nbsp;



**Step2:** select **Package Resource Viewer: Open Resource**


![Testimage1](Images/Screenshot%20(258).png)   

&nbsp; 


**Step3:** Select the language whose Snippet you want to edit.

![Testimage1](Images/Screenshot%20(259).png)

&nbsp;


**Step4:** Select Snippets/
![Testimage1](Images/Screenshot%20(260).png)

&nbsp;

**Step5:** Go to the snippet you want to edit.\
(Here I want to edit the for loop snippet to change the bracket alignments)
(hehe, fetishes)
![Testimage1](Images/Screenshot%20(261).png)

&nbsp;

Earlier snippet
![Testimage1](Images/Screenshot%20(262).png)
New snippet
![Testimage1](Images/Screenshot%20(263).png)

PS - You need to save the new snippet for it to work.\
Use CTRL + S for saving it.

&nbsp;

**Here you can see the final effects.**
![Testimage1](Images/Screenshot%20(265).png)
![Testimage1](Images/Screenshot%20(266).png)




