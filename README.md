<h1>Blue Screen and Incompatible Virtualisation Settings</h1>

<h2>Description</h2>
A ticket-solving practice of a blue screen issue related to a BIOS settings in a simulated environment, IT Specialist Simulator.
<br />

<h2>Environments Used</h2>

- <b>IT Specialist Simulator</b>


<h2>Walkthrough</h2>

<p align="center">
I got this task via email. I'll have to see what the blue screen says.
<img width="1158" height="648" alt="image" src="https://github.com/user-attachments/assets/3239752a-2000-4d9e-b17f-971f98211b2c" />


<br/>
<br/>

<p align="center">
The error code is 0x000000D1 (DRIVER_IRQL_NOT_LESS_OR_EQUAL). <br/>
<img width="1576" height="910" alt="image" src="https://github.com/user-attachments/assets/962075b8-d6e6-42e6-bb2d-7a22a6f47459" />


<br/>
<br/>

<p align="center">
I went back to my PC and searched on the forum. Looks like an issue related to VT-D settings on BIOS. <br/>
<img width="1491" height="763" alt="image" src="https://github.com/user-attachments/assets/1337dca7-f7f0-4860-bd55-13a1290578b4" />


<br/>
<br/>

<p align="center">
I went back to the employee's PC and check the BIOS settings. VT-D was enabled even though it says right above that VT-D is not supported. I disabled it, saved the settings and rebooted the computer.<br/>
<img width="1568" height="910" alt="image" src="https://github.com/user-attachments/assets/58c04cee-4c7d-4df2-a3f6-cb79f58d889d" />


<br/>
<br/>

<p align="center">
The OS startsup successfully. Marking it as done.<br/>
<img width="1920" height="1080" alt="IT Specialist Simulator 2_9_2026 8_34_45 PM" src="https://github.com/user-attachments/assets/2caa4a32-1246-465b-82b9-b7b60c137f37" />
<br/>
<br/>


