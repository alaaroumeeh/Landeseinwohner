# Landeseinwohner
Simple commands interface to manipulate Excel sheet of world countries and their corresponding nationality and residents name in German language.

Usage:

The interface defines five commands, namely: show, add, remove, modify, exit/quit.

Enter the desired command then follow it's prompts. Here you find a separate description and usage for each command:

1) show:
   
	prints the full table, row contents, or cell content.
	
	usage:
	
		/>show
	
		Enter land name or cell index: 

	to print the full table, simply press enter
	
	to print row contents, enter the correct country name you want.

	to print cell content, enter it's excel index, for example C3.


2) add:

	adds a new row to the table in alphabetical order for country names.
	
	prompts for six fields, which are the new row's content in the table.
	
	usage:
	
		/>add
	
		Landesname:
	
		Nationalität:
	
		Einwohner (m):
	
		Einwohnerin (f):
	
		Einwohner (m pl.):
	
		Einwohnerinnen (f pl.):


3) remove:
	
	removes one or more rows from the table via country name while preserving alphabetical order of country names.
	
	usage:
	
		/>remove
		
		Enter land name #1:
		
		Enter land name #2:
		
		...

	Empty input stops asking for further country names and executes the command.
			
4) modify:

 	modifies row contents via country name.
	
	Note: It's not possible to modify the country name through this command, rather only the fields that follow it. To modify a country name remove it's row 			first then re-add it with the desired information.
	
	usage:

		/>modify
	
		Enter land name:

		Nationalität:

		Einwohner (m):

		Einwohnerin (f):

		Einwohner (m pl.):

		Einwohnerinnen (f pl.):


5) exit/quit:
	
	Saves changes and terminates the program. Both words "exit" and "quit" work the
	same.


	Mit herzlichen Grüßen

	Alaa Roumeih, 15.08.2026
