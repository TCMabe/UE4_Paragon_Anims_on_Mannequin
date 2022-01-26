# Paragon Anims on Mannequin

This fork is based off [TCMabe's repository](https://github.com/TCMabe/UE4_Paragon_Anims_on_Mannequin) mainly to convert the repo from an Unreal Project to a Plugin.

## Install

You can download a packaged release [here](https://github.com/mklabs/UE4_Paragon_Anims_on_Mannequin/releases/latest/download/Paragon_Anims_Mannequin_1.0.0.zip).

Alternately, from the root of your project, run:

    git clone https://github.com/mklabs/UE4_Paragon_Anims_on_Mannequin.git Plugins/Paragon_Anims_Mannequin --single-branch

Start project and check / enable the plugin: `Plugins > Project > Animations > Paragon_Anims_Mannequin`

If you don't see the plugin content, make sure "Show Plugin Content" is ticked in the Content Browser view options.

## Credits

Thanks to TCMabe for creating this and retargeting all those animations in the first place!

You can find original readme content just below.

---

## UE4_Paragon_Anims_on_Mannequin

Welcome to the UE4_Paragon_Anims_on_Mannequin project. 
These animations are only for use within an Epic Unreal Engine project and their download and use from this repository acknowledges your agreement to be bound by the terms and conditions implied by the Epic Unreal Engine license agreement.

To use these animations on your character:

1. Open your character and assign the Humanoid Rig. 
2. Set the Bone Names in the assignment window. 
3. On the Skeleton Tab open the options and recursively set all to Skeleton. 
4. Set the Root to Animation. 
5. Set the Pelvis to Animation Scaled. 
6. Make sure both characters have the same pose. 
7. Make sure each character has an assigned preview mesh. 
8. Navigate to the character that you want animations from. 
9. Select the Animations and Montages you want to use. 
10. Right click the selected file(s) and choose Retarget. 
11. Select the skeleton of your character as the target. 
12. It is recommended to change the destination folder to avoid conflict.
