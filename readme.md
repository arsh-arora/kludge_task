# Submission by Arsh Arora
## Modi-Gandhi Steg with esolang
## Method of Solving

### Restoring image
First, as a classic move, the beginning magic number of png, 89 has been changed to 69 which needs to be changed back. After that we will receive an image of Rahul Gandhi

### LSB De-Steg
The image indicates The file is hidden in R0,G0,B0 planes using lsb steganography which will give us an image of Modi refusing to tell us the answer. 

### Using Exiftool to find comment
Simultaneously we will notice that the comments of the png file with Rahul Gandhi hosts a comment saying a number which needs to be inserted into the code given to us. 

### Running Modi Script and password steg on image
That number in Modi script will give us the password and that image will then be ran through a password steganograph with the password obtained through the Modi script and through that we will receive our final flag for the question