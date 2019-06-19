# Creating-files-and-directories-for-bem-by-node.js

1) install: npm i --save-dev fs prepend-file

2) Launch: open console and be inputing: node cbem.js index BlockName BlockName__ElementName_Modificator_Value __ElementName _Modificator
  
2.0) cbem.js - name file what is creating files and directories

2.1) index - entrypoint where will added commands "include BlockName__ElementName.pug " bem entities 

2.2) BlockName - name directory for block

2.3) BlockName__ElementName_modificator_Value - name file what will have created (Content__ColorName_bgColor_Red.js, Content__ColorName_bgColor_Red.scss)

2.4) __ElementName - name directory for Element

2.5) _Modificator - name directory for Modificator

2.6) And you can edit the file for yourself

3) Editing the file: Default start directory "Common.blocks/". You can change this. Just replace all "Common.blocks/" with "YourPath"

That's all)
