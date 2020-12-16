# FASTQC was installed by downloading the FastQC.zip file 
# then the command
# unzip fastqc_v0.11.9.zip

# now FastQC is a directory that is available to work from

# java must be installed for FASTQC to work
# this was done by the following command:
# sudo apt-install default-jre
# the version can be checked by:
# java -version

# a script was written (called fastqc_files.py) 
# firstly the modules had to be imported and directories set up
# then the batch execution would be implemented on the FASTQC files
# these FASTQC files were then moved to a dedicated directory 
# and once these steps were executed the script would print "done"
 
# installing trimmomatic
# this was done via conda as follows:
# conda install -c bioconda trimmomatic 

# then to run trimmomatic on files the command is:
# python "file_name.py"

# So in this case the file is trimmomatic_script.py
# and this resulted in a file being generated called trim_out
