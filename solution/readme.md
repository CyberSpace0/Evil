evil challenge | medium
vulnerablity is php injection

in source code we see <a href="?a=guest"></a> click it and you will see
the data in parameter a will Reflected in the body to solve the challenge you need to add this payload 
system('ls')
by this way you will have command injection and you need to find the file flag and raed it 
system('cat FJHAFISHDFIH247JSF843HSNMFH4BF2S8MFBVNWX8C2_flag.txt')
