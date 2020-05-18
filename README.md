# Blockchain
# With Netbeans IDE 8.2 and a Macbook Pro with 32GB RAM and an Intel i9 processor, 
# I was able to create a JAVA program that creates virtual blocks and an actual blockchain between the blocks. 
# The blocks have a digital signature, a unique transaction and a timestamp. 
# Each block has a current hash value and a previous hash value that matches the current hash value of the previous block. 
# The first block is an empty non-real block because it has no previous hash value since there is no block before it. 
# All of this goes through the SHA-256 algorithm. 
# After the hash algorithm completes, the program outputs the block hash values. 
# The program also authenticates whether the current hash value and previous hash value of the blocks are equal or not. 
# If they are not equal, then the blockchain would not be valid. 
# If they are equal, then the blockchain is valid and ready to go. 
# The program also outputs and tells the user if the blockchain is valid or not. 
# Even if a single block in the program is not valid, the entire blockchain would be invalid and output "null".
