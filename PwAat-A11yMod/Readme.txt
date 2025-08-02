## Unfinished accessibility mod for Phoenix Wright: Ace Attorney Trilogy.

https://forum.audiogames.net/topic/56815/unfinished-accessibility-mod-for-phoenix-wright-ace-attorney-trilogy/


#1 2025-07-08 21:14:52

Hello everyone, I'm not sure how many people here are interested in Ace Attorney.
I personally love the Ace Attorney series, so I really hope that Ace Attorney can have accessibility features. By chance, I learned that Phoenix Wright: Ace Attorney Trilogy on Steam was developed using the Unity engine, so I kept wondering if anyone would create an accessibility mod for it. Later, I actually managed to get an accessibility mod for that version, but its accessibility features were incomplete. Furthermore, due to an issue with our communication platform, our private messages were lost, leading to some misunderstandings. As a result, this mod later became one that uses natural voice narration. However, the mod's developer, having spent too much effort, expressed that they no longer wanted to maintain it. I found this very regrettable. So, my friend and I tried to bridge the voices, and now NVDA and some Chinese screen readers can read it, but its functionality is incomplete. I have plans to try rewriting it, but I'm unable to set up my programming environment. Although this mod is incomplete, it does have the necessary conditions to allow you to complete the game. Therefore, would anyone like to try this mod? I haven't made it fully public for download, so if anyone is interested, please contact me directly.
Additionally, if anyone is willing to rewrite a mod, that would be fantastic!
"Alternatively, if someone could make a request to Capcom, asking them to add accessibility features to the game, that might also be worth a try."
Here's the link to the mod:
https://chikutaku-luyi.itch.io/pwaatwzamod


#2 2025-07-08 21:16:33

"Since I haven't made it fully public for download, if you're interested, please contact me directly through any means."
How to Use:
Open the unzipped folder. Select and copy all the files inside. Paste them into:
Your Ace Attorney game directory\PWAAT_Data\Managed
This will replace the existing files. It's recommended to back up the original Assembly-CSharp.dll before replacing it. If you wish to stop using this patch, simply revert to the original file.
Default Game Hotkeys:
Up, Down, Left, Right arrow keys and W, S, A, D keys: Navigate menus.
Enter key: Confirm selection.
Backspace key: Go back.
Tab key: Most of the time, opens the Court Record.
During story segments:
Enter key: Advance to the next line of dialogue.
Hold Backspace key: Fast-forward through dialogue.
ESC key: Open the menu.
In the Court Record:
Left/Right arrow keys: Select evidence.
E key: Present evidence at a suitable location.
R key: Switch between Character Profiles and Court Record. Operations for Character Profiles are the same.
During Cross-Examination:
Enter key or Down arrow key: Advance to the next line of testimony.
Backspace key or Up arrow key: Go back to the previous line of testimony.
Q key: Press (also known as "Pursue"). When you find the statement where you need to present evidence, press Tab to open the Court Record, find the appropriate evidence, and press E to present it.
In the Scene Screen:
Left/Right arrow keys: Select actions.
Enter key: Confirm.
Backspace key: Go back.
ESC key: Open the menu.
In the Investigation Screen:
Up, Down, Left, Right arrow keys: Move the magnifying glass.
Enter key: Investigate.
Backspace key: Exit.
Q key: Sometimes switches screens.
In the Blueprint/Map Screen:
Directional keys: Move.
E key: Point out the location of the cursor.
Personal Recommended Play Order:
Ace Attorney 1 (first four chapters), all of Ace Attorney 2, all of Ace Attorney 3. After completing all of these, then play Ace Attorney 1 (Chapter 5).
About Voice Acting:
This mod includes a feature for switching voice acting. The default is Japanese. You can change this in ModConfig.ini. The comments within the file state that leaving it blank will select the voice acting based on your system language, but in reality, leaving it blank causes errors with Chinese. Therefore, if you need Chinese voice acting, please manually modify the following line in ModConfig.ini:
Language=0
The default 0 is Japanese. You can change the number: 1 for English, 2 for French, 3 for German, 4 for Korean, 5 for Simplified Chinese, 6 for Traditional Chinese. Although stated as separate, Simplified and Traditional Chinese actually share the same voice acting.
Okay, I hope you enjoy using it. Some settings in the mod currently cannot be read. This is because I used someone else's pre-made mod for screen reader bridging, so there are some issues. Also, due to certain reasons, development on the mod has stopped. However, it's perfectly fine for completing the game and at least experiencing it.
Original Author: DONOKO
