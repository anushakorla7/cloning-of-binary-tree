# cloning-of-binary-tree
Here the code is on Cloning a Binary Tree with Random Pointers.

Given a Binary Tree where every node has the following structure. 

struct node
{  
    int key; 
   
   struct node *left,*right,*random;

} 

The random pointer points to any random node of the binary tree and can even point to NULL, clone the given binary tree.

Method 1 (Use Hashing) 
The idea is to store a mapping from given tree nodes to clone tree nodes in the hashtable. Following are detailed steps.

Method 2 (Temporarily Modify the Given Binary Tree)

Now we are solving through hashing method.
