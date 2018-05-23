import-3d-models-to-unity
This program aims for the automatic importing of 3d models to unity .

Importing of a new object to unity is simply copying it to the Asset folder of working project of unity.when unity is opened it imports the file.But let me warn you this process is simple if we are working only with little number of objects,more often all gaming/designing companies deal with hundreds and thousands of objects .Where this conventional method is a tedious work.

Here I came up with a simple bash script programs that make this process automatically.

prerequisite: I have used fswatch a program that tracks all the changes made to a program or file .It is taken from a open source project https://github.com/emcrisostomo/fswatch . This software works for macOS as well as linux/ubuntu. A similar program called readchangesdirectoryw can be installed for windows. This is the only prerequisite

The following are the instructions

Place both the scripts in the model export folder of any software.
Run the fswatch.sh script
Mention the path to assets folder of working project in assets.sh
How it works once the fswatch.sh script is made to run from terminal it will constantly monitor for any changes in the directory and copies all the models to assets folder of working project in unity automatically.


