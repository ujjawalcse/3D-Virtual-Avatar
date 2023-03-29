# 3D-Virtual-Avatar
  *This repository includes some of my works done in 3D Virtual Avatar Reconstruction field*

## Full Human Body Reconstruction and Animation using single image/Video :

+ Used PIXIE along with DECA to reconstruct complete 3D body model with detailed facial texture
  and pre-assigned body texture.

+ Used the Pose,Shape and Expression parameters generated for video clips to retarget full body animation along with facial expressions.

+ Wrote Blender script using bpy python package to achieve a complete automated way for generating full body animation
  in AR/VR suitable file format like .FBX/.GLB

Refernces :
+ https://github.com/yfeng95/PIXIE
+ https://github.com/yfeng95/DECA


## 3D Face Reconstruction using single image :

+ Used DECA model to reconstruct 3D face with detailed textures and normals for wrinkles,poses and expressions.

+ Used the Pose,Shape and Expression parameters generated for video clips to retarget facial expressions.

+ Tried Spectre and EMOCA models to improve the facial expressiveness

+ Wrote Blender script using bpy python package to achieve a complete automated way for facial animation
  in AR/VR suitable file format like .FBX/.GLB

Refernces
+ https://github.com/yfeng95/DECA
+ https://github.com/radekd91/emoca
+ https://github.com/filby89/spectre


## Rigged 3D Avatar Generation:

+ Used the 3D reconstructed face upto the neck like FLAME head model.

+ Generated Blendshapes using Nvidia Omniverse Audio2Face for the 3D face model.

+ Wrote Blender script using bpy python package to join and merge (with threshold) the 3D head model with blendshapes 
  and the correctly rigged lower body in clothing. Then,Exported AR/VR ready to use 3D Avatar in .FBX/.GLB format. 

References
+ https://github.com/TimoBolkart/TF_FLAME
+ https://github.com/Rubikplayer/flame-fitting
+ https://www.nvidia.com/en-us/omniverse/apps/audio2face/


## Audio Driven 3D Facial Animation:

+ Tried VOCA model to generate 3D vertices displacement based facial animation for FLAME head model.

+ Tried FaceFormer model to generate 3D vertices displacement based facial animation for FLAME head model.
  Also tried to train it on facial blendshapes data by customizing the whole pipeline.

+ Trained Viseme based 3D facial animation model on blendshapes data and tested via maya python scripting

+ Explored the Nvidia Omniverse Audio2Face for generating blendshapes for custom head model using
  Character Transfer Pipeline and tried the speech to facial speaking animation

References
+ https://github.com/TimoBolkart/voca
+ https://github.com/EvelynFan/FaceFormer
+ https://www.nvidia.com/en-us/omniverse/apps/audio2face/


## Generating Automatic Skinning Weight:

+ Used Neural Blend Shapes for automatic skinning weight generation for T-Pose humanoid character
  based on SMPL rigging system.

+ Tried the provided blender script for generating smooth animation

References
+ https://github.com/PeizhuoLi/neural-blend-shapes


## Real-time 3D Character Animation
+ Tried ROMP model to generate 3D SMPL joints in real-time and feed into blender running
  on different port to experience real-time humanoid character animation.

References
+ https://github.com/Arthur151/ROMP

