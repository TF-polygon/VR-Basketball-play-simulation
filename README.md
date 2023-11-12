# Virtual Reality Human Computer Interaction Team Proejct

This project was team project of VR HCI lecture from College of ICT Construction & Welfare Convergence, Kangnam University. It was made for human interaction with virtual reality and development enviornment was Unity C# using Oculus Quest 2 device. Compatibility among Oculus Quest 2 and Unity are on the great side, so you can experience realistic virtual reality contents. It might be not good quality because this is a just team project of one lecture but you can feel a lot of realistic feeling by experiencing a interaction with virtual reality.

## Contents

When we were discussing what topic would like to use for Human Computer Interaction, we decided to try interacting using basketball content. Simply, It's all that you catch the ball in front of you in virtual reality and throw up to basketball hoop. If you success to goal, score will be increased for one.

Controller controls are as follow:
- Left Controller `Joystick` : Move to user position.
- Right Controller : a act of right hand in virtual reality.
- Right Controller `Joystick` : Rotates 90 degree to user's view.
- Right Controller `Index finger button` : Catch the ball.
  - If you catch the ball in virtual reality, you can throw it during swing your arm and release the button.


## Depencies
- Oculus Quest 2
- Unity C#   >=  2020.3.32f1

## Setup
- In 'File > Build Settings', set the following :
  - Android, Texture Compression: ASTC<br>
  - And exeute Switch Platform

- In 'Player Settings' or 'Edit > Project Settings' at the bottom left of 'Building Settings', select 'Player' and set the following :
  - Company name (option)<br>
  - product name (option)<br>
  - Other Setting: Color Space - Linear<br>
  - Delete a Vulkan<br>
  - Package name: (check up company name, product name)<br>
  - Minimum API Level: API level 23<br>
  - Scripting Backend: Mono<br>

- Install Oculus Interation
  - Open the 'Window > Asset Store'.
  - Click the 'Search Online' and open the store.
  - Search 'Oculus Integration' in asset store and open it.
  - Click the 'Open In Unity' and load as package manager.
  - Click the 'Download' at the bottom right of 'Package Mangager' and  Click the 'Import'.
  - Declude unnecessary components in 'Import' list. (Avatar, LipSync, SampleFramewok etc.)
  - Import it. If it need to upgrade, do it.
  - Configure and install necessary components.

- Install XR Plugin Management
  - Open the 'Unity Registory' at 'Packages' at the top right of 'Pacakge Manager' and install as following:
    - Select 'XR Plugin Management' and click the 'Install'.
    - Select 'Oculus XR Plugin' and click the 'Install'.
  - Open the 'Edit > Project Settings' and set as following :
    - XR Plugin Management
      - Android > Plugin Provider: Oculus
      - PC > Plugin Provider: Oculus
    - XR Plugin Management > Oculus
      - Android > Stereo Rendering Mode: Multi Pass
      - PC > Stereo Rendering Mode: Multi Pass
  - In PC, select a 'PC' at 'Building Settings' and execute 'Build & Run'.

- Modify Oculus Quest 2 Developer
  - Install Oculus app in android smartphone and set a initial according to command.
    - Execute 'til success to pair between Oculus Quest 2 and Oculus App.
  - Open the Oculus app and 'settings' at the bottom right of.
  - Tap to open the connected Coulus Quest 2 and open the 'More Settings'.
  - Select 'Developer mode' and Trasnfer to ON.

- Build App
  - Connect to PC a Oculus Quest 2 using USB Type-C cable.
  - Agree some dialogs like 'do you agree to debug usb?', in display of Oculus Quest 2.
  - Open the VR sample 'Assets > Oculus > VR > Scenes > ControllerModels' at Unity project created in 2.1 version.
  - Open the 'File > Building Settings' and execute 'Build & Run'. Agree it when the prompted with the dialogs, etc.
  - If Oculus Quest 2 is prompted the app, Build complete.
  - If you want to quit, close the app on the Quest 2 side.


