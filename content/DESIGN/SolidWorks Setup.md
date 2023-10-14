To install SolidWorks, follow the instructions provided in this spreadsheet:
https://docs.google.com/spreadsheets/d/1AAJ7ueWqx_pui89ytcHOLbipR8hLAZMzIT-uO9koAL8/edit#gid=0

Once SolidWorks is installed, there are a number of settings you can change to make life easier later on. These are mostly unrelated to each other, so here's a list of suggested settings changes in order from most recommended to merely suggested:

**Check Default Units**
![[Pasted image 20231014000128.png]]
To check your default units, create a new part and check the lower right hand corner. If it says IPS, your default units are Inches, Pounds and Seconds which is perfect for our purposes (we generally build using imperial units). If it says MMGS, it's best to change the default so you don't finish designing the coolest part anyone's ever seen just to realize your part is 25.4 times too small. 

To change your part's default units:
1. Create a new part and leave it blank
2. Set the units to IPS by clicking "MMGS" in the lower right corner, then selecting IPS
3. Click File -> Save As
4. Change the name to "Part", and the Save As Type to "Part Templates (\*.prtdot)"
6. Make sure you're saving in a folder named templates, then save the part template to overwrite the old one
7. Close the part

Now, when you create a new part, it should go straight to IPS units. Repeat the above steps for assemblies by creating a new blank assembly, changing your units, and saving it as "Assembly.asmdot" in the same templates folder.

**Enable "Rename Components from Feature Tree"**
By default, the procedure to rename files is very clumsy and can cause errors in assemblies. Enabling this setting lets you rename components in the feature tree.

Go to: {Settings -> System Options -> FeatureManager} then check "Allow components to be renamed...".

Now, you can right click on the component's name in the feature tree to rename components. Not only do you no longer have to close SolidWorks to rename a file, SolidWorks will automatically update all references so your assemblies stay happy (and when assemblies are happy, everyone's happy). 

**Enable "Dimension on Entity Creation"**
Enabling this setting lets you dimension sketch entities while you're initially placing them down. 

Go to: {Settings -> System Options -> Sketch} and check "Enable on screen numeric input..." and "Create dimension only when value is entered". 

**Set Favorite Materials**