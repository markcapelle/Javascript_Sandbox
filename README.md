# Javascript_Sandbox
A handy little sandbox in which to easily output javascript.
Created for use with VSCode and the Live Server addin.

The index.html page essentially routes all of the error, console.log/.error/.warning output from the browser's inspector console to a viewport. Just put the index.html and script.js together in the same directory/folder and run the index.html from VSCode using Live Server.
You'll get the viewport in your browser window like below:
<img width="742" height="407" alt="image" src="https://github.com/user-attachments/assets/d90bcc5f-2d2c-481f-a936-a89dededdfc8" />

Next open the script.js in VSCode. You can make changes live, and when you save them Live Server should automatically refresh and send your output right to the viewport.
For example...

Script:
<img width="276" height="135" alt="image" src="https://github.com/user-attachments/assets/c40bdcbd-a92a-4059-9946-da154d398cd4" />

Output:
<img width="739" height="369" alt="image" src="https://github.com/user-attachments/assets/1c2d6771-bf8a-46fc-ab56-72ca1d153575" />

LIMITATIONS:
The viewport displays errors, so if you make a type-o you could get something like below.
<img width="360" height="114" alt="image" src="https://github.com/user-attachments/assets/095aa861-1d25-41ed-8d4a-695eec19c193" />
It just doesn't give any detail on where the error is beyond that.

Additionally all your output needs to use the console.log, console.warning and console.error commands.
For example, this:
<img width="230" height="181" alt="image" src="https://github.com/user-attachments/assets/0ef2dc53-25bd-4a13-b7b8-cbae208d3c92" />
Outputs nothing:
<img width="292" height="132" alt="image" src="https://github.com/user-attachments/assets/3fafa1b0-4bda-4b70-91c9-e427ab8b4a42" />

But below:
<img width="230" height="181" alt="image" src="https://github.com/user-attachments/assets/e509cbc4-0e92-4ce9-94dc-15bdb3739106" />
Outputs desired result:
<img width="175" height="101" alt="image" src="https://github.com/user-attachments/assets/f738c552-b3fe-4fd4-b1cb-a2a0ac600334" />
