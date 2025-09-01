<img width="1920" height="831" alt="image" src="https://github.com/user-attachments/assets/1a32c58c-dc1f-454c-92d9-c403923fcd82" />
<img width="489" height="299" alt="image" src="https://github.com/user-attachments/assets/9405f7eb-1259-47b4-b7ea-88aa5f8eee6a" />

A SimHub ShakeIt Device emulator for XBOX Series X/S Controller

Allows mapping all four vibration motors to various telemetry-driven effects.

<img width="1225" height="1310" alt="image" src="https://github.com/user-attachments/assets/878f0b07-5882-4ec6-83cc-87c86a95fb90" />

<b>Prerequisites</b><br>
SimHub (Licensed if you want 60FPS) https://www.simhubdash.com/<br>
com0com http://sourceforge.net/projects/com0com/<br>

<b>Usage</b><br>
Run com0com setup, verify pair using COM numbers.<br>
Run SimHub, XboxShakeIt and connect to Arduino ShakeIt device in SimHub.<br>
Import included Effects Profile and Motor Outputs or configure manually.<br>
<br>
<br>
<b>Notes</b><br>
May Work with other controller brands? Enter valid digit HID Vendor ID as decimal. Default is 1118 (Microsoft).<br>
May support multiple controllers? Untested.<br>
May need to disable Secure Boot to instal com0com. (there are other paid virtual null modems out there)<br>
New WRC23 profile requires 60FPS SimHub to function properly.<br>
