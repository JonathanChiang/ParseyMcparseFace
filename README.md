# ParseyMcparseFace
Exploring Google's SyntaxNet: Neural Models of Syntax.

# General Notes on Installation

terminal commands sequentially and successfully used 
1)

export ALL_PROXY=$http_proxy:relevant proxy

2) Issue with path links on brew.1, (Deletes path)

rm -rf /usr/local/share/man/man1/brew.1

3) pip installation (pip install numpy was already installed) 

pip install asciitree
pip install mock

4) From tutorial (Once you completed the above steps, you can build and test SyntaxNet with the following commands:)

 git clone --recursive https://github.com/tensorflow/models.git
 cd models/syntaxnet/tensorflow 
 ./configure (asked about Google Cloud Platform and configuration of GPU and cuda)
 
Ended up with a errors in the build tests

# Attempting Docker installation 



 

