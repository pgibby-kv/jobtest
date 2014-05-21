job related repo 
current files (May 21, 2014)
show an lsdyna job that tries to run a post (lsprepost) command file

This runs from the command line on Oakley:

ssh -X Oakley "cd `pwd`; . /rundyna"

an lsdyna job is run from the dyna-mpp_oaktest script
then when it completes the script does a module load lspp and tries
to run the lsprepost command file c=postgraphics.cfile

Run from an intereactive terminal on Glenn this script works. But from
a webserver on Glenn, not.

Paul Gibby pgibby-kv/awe0002
