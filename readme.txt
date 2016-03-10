How to delete a file with too long file name :

	mkdir empty_dir
	robocopy empty_dir the_dir_to_delete /s /mir
	rmdir empty_dir
	rmdir the_dir_to_delete

Delete all files from folder containing certain characters
	
	del /s *certaincharacters*.extension
