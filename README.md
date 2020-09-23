<div align="center">

## Program startup


</div>

### Description

This trick will show you how to startup your program first thing on windows XP(nt or 2k) without writing any enteries in the registry or adding anyshortcuts in the startup menu.. This trick will also disable the running of the explorer.exe and any startup program

by doing that , the desktop and taskbar will not load!! and you'll only have your program running, providing complete user restriction over windows , cool ha ??!?

Please Vote!!
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Fathi Alsharif\(Raven\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/fathi-alsharif-raven.md)
**Level**          |Intermediate
**User Rating**    |5.0 (25 globes from 5 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__1-1.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/fathi-alsharif-raven-program-startup__1-49611/archive/master.zip)





### Source Code

```
1. First of all, you have to run the windows on safe mode.
2. Press ctrl+alt+delete , when the task manager loads , Goto Proccesses and end the program userinit.exe
3. Goto windowsdirectory\system32\
4. erase the file userinit.exe
5. rename your exe file "userinit.exe" and place it in the system32 folder
PS: if u didnt run windows on safe mode, wenever u try to delete the USERINIT.exe file , windows will restore it back , so run safe mode..
Now , When windows starts , ur program is the first thing to load on windows, with no desktop or taskbar...
To load the rest of the windows normally ,
create a command button on your program..
Private command1_click ()
shell "explorer.exe"
end sub
this code will loade the windows explorer which includes the desktop and taskbar.....
for full security , download a code that disables task manager so that user wont be able to run the explorer by himself!
This trick is not danagerous or anything..
```

