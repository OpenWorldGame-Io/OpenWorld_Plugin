# OpenWorld

## To play test the pre-Built Game:
- Grab the latest versions from here:
  - [OpenWorld - All Builds](https://drive.google.com/drive/folders/1_ZObODcccQm6E5Y8RsOlOiryJd6r56bR?usp=share_link) (Win and Mac)
  - Run the `LyraGame` executable in the root of the `OpenWorld` folder
  - Choose -> Play -> Start Game -> Open Space
![image](https://github.com/user-attachments/assets/6844b2ce-e2ff-46b9-a0be-bcfce1bca820)
  - This opens a customizeable level with interactive blocks and pictures
  - Use these keys to use new functions:
    - "N", to clear inventory, drop the pistol
    - "Z", to drop a metal box, for building
    - "X", to drop a "16x9" picture which loads "https://bit.ly/random169" by default.  You can approach the picture to see the URL field where you can copy'n'paste in any Image URL.
    - "P", to pickup an metal box or picture actor.
![image](https://github.com/user-attachments/assets/8e8c28cc-5961-4792-9bf8-991fb9fa6e30)
![image](https://github.com/user-attachments/assets/1016b6fb-cf8b-4867-b96e-7acb47d4e96d)
  - Use blocks and sign to build platform and walls
![image](https://github.com/user-attachments/assets/fa7ef242-5810-41c2-a07d-6f06751e729c)

## To open the project in the Unreal Editor:

### Start a new Lyra Starter game and load the OpenSpace plugin from this Repo into the stock Lyra Starter Project
- Open "Epic Games Launcher" -> Unreal Engine -> Samples -> Lyra Starter Game
- Clone this repo.  E.g. Using...:
  - GitHub Desktop -> Clone -> https://github.com/OpenWorldGame-Io/OpenWorld_Plugin.git
- Move the folder from this projects into here... LyraStarterGame\Plugins\GameFeatures\OpenSpace\
  - Note: The plugin needs to be name "OpenSpace".
- Open the "OpenWorld.uproject" in the Editor 
- Once the Editor is loaded, go to the Plugins Window and Activate the `OpenSpace` plugin under the `GameFeatures` category
- Restart the Editor and the Game mode should be activated automatically
- To test the OpenSpace plugin, go to "Content Drawer -> Plugins -> OpenSpace Content -> Maps -> L_Expance_OpenSpace"
- To show the contents of this streaming level in the Editor go to "Window -> Window Partition -> Window Partition Editor", draw a box to select the level geometry, "Right-click -> Load Region from Selection".  Then your should see a copy of the Expance level, with the OpenSpace plugin activated.
- Click the GreenArrow to play the L_Expance_OpenSpace level.
- Use these keys to use the functions:
  - "N", to clear inventory, drop the pistol
  - "Z", to drop a metal box, for building
  - "X", to drop a "16x9" picture which loads "https://bit.ly/random169" by default.  You can approach the picture to see the URL field where you can copy'n'paste in any Image URL.
  - "P", to pickup an metal box or picture actor.
  - "I", to view your players inventory.
<img width="1250" alt="screenshot1" src="https://user-images.githubusercontent.com/3343322/202642941-67e6cf91-ce61-4aab-92cd-01d1abf984ef.png">


## To build new binaries of the game with the Unreal Editor:
- Click on the Platforms menu -> Choose "Mac" or "Windows" -> Package Project -> Choose a folder that's outside of the project folder.  (E.g. "../OpenWorld_Builds/OpenWorld_Mac_0.0.1/"
- Click on "Show Output Log" to watch the output of the build processes
- Once the Build is complete, you should be able to double-click on the binary executable files to play.
- Once open, you can choose "Play Lyra -> Start a Game -> OpenSapce" to play the customized Expanse level with the additional functions mentioned above.
- If you want to play this newly build version with others, simply zip the folder and share (e.g. on Dropbox, Google Drive, etc).![2](https://user-images.githubusercontent.com/118783344/228934001-7fff6b62-5d5f-4c7b-869d-1c827c60410b.jpg)

![1](https://user-images.githubusercontent.com/118783344/228933995-46cc431a-3384-4729-921a-29f1f4c46c90.jpeg)
![2](https://user-images.githubusercontent.com/118783344/228934140-e05c4c02-06fe-4c40-aa3a-39177dbd53d5.jpg)
![3](https://user-images.githubusercontent.com/118783344/228934006-931c621a-36c6-4cd5-a7f0-28d008ca4f48.jpg)
![4](https://user-images.githubusercontent.com/118783344/228934014-9bb308ba-f35c-4a1a-a40f-3b397f0475ba.jpeg)
![5](https://user-images.githubusercontent.com/118783344/228934019-d5057a7f-01c6-4040-a76a-ba66b301150d.jpeg)

