# Game automation using AutoHotkey
*A guide to help you make games play by themself.*

# Welcome
AutoHotkey is scripting language to help you automate mundane tasks on your pc. It’s easy to learn but can be very powerful. This course will walk you through from basics like single key automation to advanced code writing to make it so that you don’t have to play all day just to level up once.

* **What you'll learn:** Use AutoHotkey to make games play by themselves.
* **How long:** You can read all of this in under 15 min, and I can guarantee that you will not be disappointed.
 
# Quick Reference
* [Disclaimer](#Disclaimer) 
* [Prerequisites](#Prerequisites) 
* [Basics](#Basics) 

# Disclaimer
> _Disclaimer_

# Prerequisites
### **Must Have**
* **AutoHotkey[[Link]](https://www.autohotkey.com/v2/):** Its kind of obvious but you will need AutoHotkey for this, we will be using AutoHotkey v2 as there is no point in learning v1. Follow the Installation instructions its not very complicatied. 

* **VS code[[Link]](https://code.visualstudio.com/download):** Since we are writing a programme its recommended to use some kind of IDE, I personally use VS code with the following extensions.

| Extensions    | Link   |
| ----------    | ----   |
| AHK++ (AutoHotkey Plus Plus)    | [link](https://marketplace.visualstudio.com/items?itemName=mark-wiemer.vscode-autohotkey-plus-plus)   |
| AutoHotkey v2 Language Support    | [link](https://marketplace.visualstudio.com/items?itemName=thqby.vscode-autohotkey2-lsp)   |

### **Optional (but recomended)**

* **Roblox:** I know it’s kind of odd but it’s a convenient way for me to share a place where you can test out **your** code.
* **Prior Programming Knowledge:** If you know even a little about programming this course will be much easier for you to digest but if you don't, worry not as this course is very easy.  

&nbsp;

# Basics
### Making the file
1. Start by creating a folder where you would like to store these Files.<br>
2. Open the folder using VS code.

   ![Logo](Images/Open_Folder_VScode.png)

3. Create a new File but **MAKE SURE IT ENDS WITH ``.ahk ``**

    ![Logo](Images/MakeFile.png)

4. Great you just created your first AutoHotkey file.

### Running the file

If you want to run your AutoHotkey file then just **Right Click**, then click **AutoHotkey v2**, then **Run ahk file**.  



 Now if you look at the hidden icons at the bottom of your screen you will see that a AutoHotkey icon. This means that your AutoHotkey file is running.

 ### Important Things to Know

**The following things will be used alot, and is very useful and important to know about when writing a AutoHotkey Script.**

* MsgBox [[Link]](https://www.autohotkey.com/docs/v2/lib/MsgBox.htm):
Like the name suggests its a handy little thing to display a Message on your screen. When used it will pop up with a window containing your Message.

    ![Logo](Images/MsgBox_example.png)

* Hotkeys [[Link]](https://www.autohotkey.com/docs/v2/Hotkeys.htm):
Its best to show how this works using an example.

    1. Open your `.ahk` file you created and write the following things
        
        ![Logo](Images/Hello_World.png)
        
    2. Now Run the file.
    3. You will notice that nothing has happened

    exit code runnning