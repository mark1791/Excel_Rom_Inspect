A Excel file that allows you to create Rom files *.bin for flashing to 1/2Mbit SST39010/020 Flash IC's and 27C512

**4 Macros**

**Scan for Rom Images** - Lets the user search a directory for Rom images and loads this into Sheet ROM a list of filenames and location 

**Create Bin File** - This will create a appended bin file with the files selected in Bank 1 and Bank 2, Bank 2 will only work if the Rom type SST39S020A is selected files are appended in order in the list.

**Check File** - Will look at a .bin/.rom file and extract the first 40bytes and convert to ASCII the contents to check the file is create correctly or any rom file, this is stored in sheet Import

**Split file into Roms** - This will split a file into byte chunks as defined in Import Rom Size.

![Alt text](https://github.com/mark1791/Excel_Rom_Inspect/blob/main/ROM_File_Generator.JPG)
