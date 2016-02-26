#### Introduction
In computer science, a binary tree is a tree data structure in which each node
has at most two children, which are referred to as the left child and the right child.
 Binary tree's typically are not used solely for their structure and are a part of
a large family of data types. One example of this structure's application is a Binary
 search tree.

 Here is what a binary tree could look like:

 ```ruby
Binary Tree - >  100
                /   \
              20     40  
             /  \    / \
           10   15 32   8
```

Or this:

```ruby
Binary Tree - > 100
               /   \
             20     40  
            /       / \
          10      32   8
         /          \
       163          56
```

The first tree displayed is known as a complete tree and a perfect tree. The second
 tree shown is neither of the two.

**What is a complete tree?**
- A complete binary tree is defined as having all levels of the tree fully filled
except possibly the last one
- If the last level of the complete binary tree is not filled.
The nodes are filled from left to right

**What is a perfect tree?**
- A perfect binary tree is defined as all nodes have two children and all leaves
have have the same depth or level
- As seen above a complete tree can also be perfect (but this is not always the case)


#### Challenge

![No Pain. No Gain](http://network.napco.com/target-marketing/wp-content/uploads/sites/3/2016/02/job_inteview_funny.jpg)

**Mild**

Take the two trees above and create a function that can tell whether the tree is
valid, complete or perfect

**Medium**

Create a function that can compare the elements of two trees. The function will
return a boolean on the result

**Spicy**

Create a function that can invert a binary tree

Binary tree from above inverted:
```ruby
Inverted   - >  100
               /   \
             40     20  
            /  \    / \
          8    32 15  10
```
