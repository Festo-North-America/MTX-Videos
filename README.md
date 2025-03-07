# MTE-Videos
This repo contains the supporting integration files for the Festo North America Mechatronics Technology playlist videos. 

General Folder Naming Convention
XXX_FullNameOfVideo

where
XXX = the number of the video folder on the MTE Teams Channel. This should be the exact same number as the Teams Channel video main folder
FullNameOfVideo = the name of the video folder on the MTE Teams Channel. This should be the exact same name as the Teams Channel video main folder. 

General Folder Structure
00_ChangeHistory - this folder containts 1 text file detailing the changes made to video folders. All notes here should pertain to the video itself, not the content within the video. THe content will have its own ChangeHistory.txt document and Documentation.txt document. 
99_CurrentFullZip - this folder contains 1 single zipped folder with all the pertinent files, archives, etc. to execute the recorded MTE video.

Within sub-folder 99_CurrentFullZip, there should only be 1 single zipped folder. Within that single zipped folder, the files should adhere to the following structure. 
Standard Folder Template Naming Conventions
00_ChangeHistory - includes the change history of the entire sub-directory
10_Documentation - includes any documentation that has been developed, usually includes the HQ AppNote, may include additional files
20_Library/AOI/FB - depending on the environment, this will include the "building blocks" for that environment
30_SampleCode/SampleProject - PC or PLC code with sequencing included
40_FAS - Festo Automation Archive or Project if available
50_TargetSupportPackages - support packages primarily for CODESYS IDE

Example
00_ChangeHistory
10_Documentation
20_Libary
30_SamplePLCProject
40_FAS
