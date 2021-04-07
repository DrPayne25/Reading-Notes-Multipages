# **Fun With Terminal:** An Alex Payne Reading-Notes Original

**Acronym Cheat Sheet** 

**CD** = Change Directory  
**PWD** - Print Working Directory tells you what directory you are in! Use this to locate where you are when you get lost  
**LS** - List

## **Choosing A Text Editor** 

### **MVP Features**
1. **Code Completion** - Lets the text editor predict possible suggestions based on what you originally typed TIME SAVER - Look at Emmet
2. **Syntax Highlighting** - Highlight your text so you can better visually see what you typed (look at above screen shot) 
3. **Nice Variety of Themes** - Eye health you already know we looking for dark mode with green text
4. **Healthy Selection of Extensions** -  allows your text editor to grow with the tools you would need down the road through extensions 

Code in Plain text no need to bold underline or italicize  
Make sure to check that the file is saved with the appropriate file extension file name isn’t important just the stuff after

### **Text Editor Options**
1. **NotePad++** - not quite sold on this based on the review in the articles
2. **BB Edit** - currently use this at work and it struggles with the 1 and 2 MVP features 
3. **Visual Studio Code** - Never used but we did download it so I want to test this out
4. **Atom** - Also interested in looking at this like the layout of Github so I think testing this wouldn’t hurt 
5. **Brackets** - Seems to be a great first time text editor think I would rather learn the features of Visual or Atom though 
6. **Sublime** - I’m Hella bougie and this looks to have all the works so you know I need to see the free trial 

**IDE(Integrated Development Environment) VS TEXT EDITOR FIGHT!!!!!!!** 

IDE are actually a more all in one they can do the text stuff that a text editor can do but can also do more for managing and debugging more! Outlook is a good example of a IDE (not a fan of outlook so might be text editors for me) 

The Command Line! 
![note one](https://user-images.githubusercontent.com/81712870/113821795-6fcf9980-9731-11eb-8fe7-96090b78d05e.png)

￼<!--Image pending don't forget to add-->

Line 1: Is showing the user (user@bash) then showing the commands you are telling it (ls -l /home/Ryan)  
Line 2-5: This is the output from the above command that was sent  
Line 6: Finally you get a new prompt to start all over  

You can use the command echo $SHELL to see what Bash you are in
Arrow keys are you friend they let you sort though what you have previously issued

### **Basic Navigation: Team Rocket is Blasting off again**
![note two](https://user-images.githubusercontent.com/81712870/113821853-84ac2d00-9731-11eb-9adf-2f9a9d2fd7cd.png)

Line 1: Basic LS  
Line 2-3: is the output form the search followed by 3 being a new command prompt  
Line 4-9: the -l indicate this will be a long listing a long listing has the following
* First character indicates whether it is a normal file ( - ) or directory ( d )
* Next 9 characters are permissions for the file or directory (we'll learn more about them in section 6).
* The next field is the number of blocks (don't worry too much about this).
* The next field is the owner of the file or directory (ryan in this case).
* The next field is the group the file or directory belongs to (users in this case).
* Following this is the file size.
* Next up is the file modification time.
* Finally we have the actual name of the file or directory.  
 
Line 10-12: the /etc after tells the ls to not show our current directory but instead tells you the directories contents  
Line 13: Showing a ls command with a command (-l) and a argument (/etc)  
Line 12 and 18: indicate that some of the output has been cut for brevities sake  

## **Paths**

### **Absolute and Relative Paths: Which way will we go???**
![note three](https://user-images.githubusercontent.com/81712870/113821709-4f074400-9731-11eb-8114-6685e2a2d498.png)

Line 1-3: Just a PWD command to see where this is   
Line 4-6: Think this basically is just telling us where the documents folder is located on the machine  
Line 7: This is an absolute path it will give the same output since we are just telling it exactly what to do  

### **More fun with Paths**

### **Shortcuts**
* **~ (tilde)** - This is a shortcut for your home directory. eg, if your home directory is /home/ryan then you could refer to the directory Documents with the path /home/ryan/Documents or ~/Documents
* **. (dot)** - This is a reference to your current directory. eg in the example above we referred to Documents on line 4 with a relative path. It could also be written as ./Documents (Normally this extra bit is not required but in later sections we will see where it comes in handy).
* **.. (dotdot)** - This is a reference to the parent directory. You can use this several times in a path to keep going up the hierarchy. eg if you were in the path /home/ryan you could run the command ls ../../ and this would do a listing of the root directory.
Any of the above methods are acceptable use the one I like

### **Lets Travel around in the world of terminal**

CD - Change Directory running this without any argument will take you back to the home directory
￼![note four](https://user-images.githubusercontent.com/81712870/113821720-53336180-9731-11eb-8aa5-81cba696f275.png)

### **Summary**
![photo five](https://user-images.githubusercontent.com/81712870/113821734-5890ac00-9731-11eb-9fcf-0277053d2e43.png)

### **Activity: Making my way back home**
1. CD /home
2. LS /tab then select home
3. Struggling with coming up with others might want to follow up with this one part 

## **More Fun with Files**

### **Everything is a file!!**
Mac is an extension less system 
Mac is Case Sensitive make sure to check that 
If you were looking for a folder with a space in such a the User Pictures folder you would put that in ‘User Pictures’
You can also use a backslash as an escape character so like cd User\ Pictures to tell it to ignore the next space 
![photo six](https://user-images.githubusercontent.com/81712870/113821746-5f1f2380-9731-11eb-88da-57069edfbbfc.png)

?????? What how does this work - Figured out you just need to use tab to go to the options

![photo seven](https://user-images.githubusercontent.com/81712870/113821756-62b2aa80-9731-11eb-8a4a-850d668aca98.png)

 **Mkdir** - will create a drive  
 **Double Space** - This will formate the line to the next direct line no code skip
