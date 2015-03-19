Introduction

> this is a toy file system implemented when I learned how to structure data on raw device with the file concept. I referenced to the EXT2 and UXFS source code but I still made simplification compared with Ext2 and UXFS; and more operations are supported compared with UXFS. I decided to rewrote totally a simpler file system because there are several bugs in UXFS and at the time I am able to simplify deeply the layout of file system in disk. SO I did it.

Details
> this file system is very simple.
  * there are about 1000+ lines C code.
  * operations supported:
    * create/delete file and I/O on file
    * rm/mk directory
    * ln/unlink hard link
    * mv
  * this size of file system is 145\*512 bytes;
  * max number of file and directory in all is 16;
  * and max size of each file is 8\*512 bytes.


Happy hacking!