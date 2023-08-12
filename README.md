# அறிவிலி-நீட்டிப்புகள்-சாளரஒன்றிணை

- git submodule add https://github.com/247i/Git அறிவிலி
- git submodule add https://github.com/247i/GitExt.git நீட்டிப்புகள்
- git submodule add https://github.com/247i/WinMerge32.git சாளரஒன்றிணை32
- git submodule add https://github.com/247i/WinMerge64.git சாளரஒன்றிணை64
- git submodule add https://github.com/247i/WinMergeARM64.git சாளரஒன்றிணைகை64

# To get all files in submodules
git submodule update --init --recursive

Then git commit all the files added

git submodule update --remote --recursive


When cloning this project:

git clone --recursive https://github.com/UniThamizh/Git-Ext-Merge.git

when making changes to submodules use the following command to update 

git submodule update

if any files inside the submodules changed then first commit them and push them then 
commit the super project. 

