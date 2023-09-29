
## BSTnode class

```
class BinaryTreeNode {  
int data;  
BinaryTreeNode left;  
BinaryTreeNode right;  
  
public BinaryTreeNode(int data) {  
this.data = data;  
this.left = null;  
this.right = null;  
}  
}
```

## inorder traversal

fun inorder(tree)
traverse left subtree 
visit root
traverse right subtree

time complexity: O(N)

## preorder traversal

visit root
traverse left subtree
traverse right subtree

good for copying tree.
time complexity: O(N)

## postorder traversal

traverse left subtree
traverse right  subtree
visit root

good for deleting tree.
time complexity: O(N)

## level order traversal

root is added to the queue
	its left right nodes were added to the queue
		root was removed
			























