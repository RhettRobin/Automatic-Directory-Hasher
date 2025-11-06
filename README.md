# Automatic-Directory-Hasher

This hashing tool uses BLAKE-3 to monitor and hash files by chunks into hexidecimal values. An observer is set to watch a directory while the tool is ran, and during this process any files / file types that are passed into this directory will automatically be hashed by the tool, and a Parquet (.par) file will be updated with the metadata from the file as well as the hashing process.

# Use 

To use this program, install dependancies from main

Set the value of HASH_DIR equal to the directory that the observer should be watching

Set the value of META_DIR equal to the directory where you would like the .par file to be written and updated 

# Future functionality

-Multi directory selection
-GUI including a STOP/RUN button and directory manager


