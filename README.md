# This is a netlink socket test file.
## manipulate process
1. key in make to get the .ko file.
2. gcc netlinkUser.c -o netlinkUser
3. sudo insmod netlinkKernel, type this to load kernel module into kernel
4. ./netlinkUser, then you can get the msg from kernel
5. sudo rmmod netlinkKernel, type this to remove kernel module into kernel
6. make clean, type to clean the folder file
