# 🌳 Trees

The thing you are seeing is a tree. DOM(Document Object Model) is a tree. Even though it doesn't look like one. let's take a look at the tree representation of what you are seeing right now.

![](https://res.cloudinary.com/practicaldev/image/fetch/s--w-SljISv--/c\_limit%2Cf\_auto%2Cfl\_progressive%2Cq\_auto%2Cw\_880/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/u174nbjgwf4qjyk60vhu.png)

First, we have something called an HTML tag. Inside the HTML tag, there are two more tags called `head` and `body`. Inside `head` and body tags there are more tags. And again inside them, there are more tags. You can also notice that these tags are getting nested more and more. Each tag is connected to a previous tag without the first tag. And you might have noticed some hierarchy in here. This is what we call a `tree` data structure.

### What is a tree data structure? <a href="#what-is-a-tree-data-structure" id="what-is-a-tree-data-structure"></a>

\
A tree data structure is a structure where each node is connected to a previous or parent node in a hierarchical order.

![](https://res.cloudinary.com/practicaldev/image/fetch/s--CiEHiEfr--/c\_limit%2Cf\_auto%2Cfl\_progressive%2Cq\_auto%2Cw\_880/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/va0ihsvg87l7hs92bi72.png)

Ok. But that doesn't look like a tree. Let me prove it to you.

\
I hope this picture looks like a tree to you.

![](https://res.cloudinary.com/practicaldev/image/fetch/s--Na8OidPo--/c\_limit%2Cf\_auto%2Cfl\_progressive%2Cq\_auto%2Cw\_880/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/k23617ma4vpoespmzkft.png)

let's apply some CSS.\


```
.tree {
    transform: rotate(180deg);
}
```

\
We have just rotated our tree to 180 degrees. But it is still a tree. We have just rotated our tree to 180 degrees.

![](https://res.cloudinary.com/practicaldev/image/fetch/s--Bn2tNUkC--/c\_limit%2Cf\_auto%2Cfl\_progressive%2Cq\_auto%2Cw\_880/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/4ioca1n46ykqmtcx6x1j.png)

Let's see the properties and features of trees.

* Node: You can think of a node as a leaf in a tree. A node is nothing but just an element of a tree.\

* Root Node: A root node is a top node that you see in the tree. It does not have any previous node.\

* Parent Node: The parent node is the immediate previous node connected to the current node. It is just like our real-life parents. A parent can have multiple children.\

* Child Node: The child node is the children of the parent node. And that makes sense right. A child can also be a parent.\

* Leaf Node: Less node is a child node but not a parent node. Or simply, a leaf node is a child node that no other node is connected to it from the bottom.\

* Sibling Node: A sibling node is a child node connected to the same parent node. And that's what sibling means.\

* Direction: The connection direction of a tree is always unidirectional or one way. It always goes from top to bottom. From root node to child node and its child node and so on. If you notice the picture you will get that.\

* Edge: An edge in a tree is the connection between two nodes. Suppose the connection between you and your parent.\

* Path: A path is nothing but consecutive edges between the source node to the given node.\

* Ancestor Node: All the nodes that are in the path of a source node and the target node are called Ancestor nodes. Like your Father ----> GrandFather -----> Great GrandFather -----> so on
* Descendant Node: Every node in the path of your current node to the leaf nodes is called an ancestor node.

![](https://res.cloudinary.com/practicaldev/image/fetch/s--TWFjtjzM--/c\_limit%2Cf\_auto%2Cfl\_progressive%2Cq\_auto%2Cw\_880/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/er8qxmjketios3iucpdl.png)

![](https://res.cloudinary.com/practicaldev/image/fetch/s--QLOUX455--/c\_limit%2Cf\_auto%2Cfl\_progressive%2Cq\_auto%2Cw\_880/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/qcdtct5ssyanqsssqkbw.png)

![](https://res.cloudinary.com/practicaldev/image/fetch/s--m2Ce\_yJ7--/c\_limit%2Cf\_auto%2Cfl\_progressive%2Cq\_auto%2Cw\_880/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/vzpxwbvavcumi255w3y9.png)

![](https://res.cloudinary.com/practicaldev/image/fetch/s--vwo2Gr3C--/c\_limit%2Cf\_auto%2Cfl\_progressive%2Cq\_auto%2Cw\_880/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/spv9282gk7wz9rdrcih3.png)

![](https://res.cloudinary.com/practicaldev/image/fetch/s--KhlmVjnT--/c\_limit%2Cf\_auto%2Cfl\_progressive%2Cq\_auto%2Cw\_880/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/kieg4fc6398fpmufyivq.png)

![](https://res.cloudinary.com/practicaldev/image/fetch/s--RNjzDSr2--/c\_limit%2Cf\_auto%2Cfl\_progressive%2Cq\_auto%2Cw\_880/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/lw908mtmnt8t8ceiccvk.png)

![](https://res.cloudinary.com/practicaldev/image/fetch/s--BJAZkSB2--/c\_limit%2Cf\_auto%2Cfl\_progressive%2Cq\_auto%2Cw\_880/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/xrl21gcy7aravavx0m1u.png)

![](https://res.cloudinary.com/practicaldev/image/fetch/s--5R57q0vA--/c\_limit%2Cf\_auto%2Cfl\_progressive%2Cq\_auto%2Cw\_880/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/u4ykbxgd253l1iave5bj.png)

![](https://res.cloudinary.com/practicaldev/image/fetch/s--dxz0hGl---/c\_limit%2Cf\_auto%2Cfl\_progressive%2Cq\_auto%2Cw\_880/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ai0k4001hxp3k0du7pz4.png)

![](https://res.cloudinary.com/practicaldev/image/fetch/s--IyLwt6g2--/c\_limit%2Cf\_auto%2Cfl\_progressive%2Cq\_auto%2Cw\_880/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/73sp1sjxv627hvh8kpp8.png)

* Level: Count the number of edges in the path from the root node to your current node. That number of edges is called level.\

* Depth of Node: From the root node to the given node path, count the number of edges. The total number of edges is the depth of that node.\

* Height of Node: The total number of edges on the path from your current node to the most distant leaf node is the height of the node.\

* Degree of a node: The total number of children of a node is the degree of a node.\

* Height of Tree: Maximum number of edges from the root node to the leaf node. A tree might have many leaf nodes. But you have to look for the most distant node. Then count the edges.\


![](https://res.cloudinary.com/practicaldev/image/fetch/s--ptyrL0SG--/c\_limit%2Cf\_auto%2Cfl\_progressive%2Cq\_auto%2Cw\_880/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ypjn9r7cwa32qph6sb45.png)

![](https://res.cloudinary.com/practicaldev/image/fetch/s--eQ0ZNbIN--/c\_limit%2Cf\_auto%2Cfl\_progressive%2Cq\_auto%2Cw\_880/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/0s5p12imn9mgl083d4ot.png)

![](https://res.cloudinary.com/practicaldev/image/fetch/s--rpcOUlH0--/c\_limit%2Cf\_auto%2Cfl\_progressive%2Cq\_auto%2Cw\_880/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/058sr2y1snhpbmqdf3i0.png)

![](https://res.cloudinary.com/practicaldev/image/fetch/s--wLnOfP-v--/c\_limit%2Cf\_auto%2Cfl\_progressive%2Cq\_auto%2Cw\_880/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/86jz7v9sbrkp6vxzdyp5.png)

![](https://res.cloudinary.com/practicaldev/image/fetch/s--31Ko89me--/c\_limit%2Cf\_auto%2Cfl\_progressive%2Cq\_auto%2Cw\_880/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/4p2geod72z363ccsctdn.png)

**Some facts about Tree**

* The height of a tree is always equal to the level of the tree
* Number of edges in the tree = (n - 1) \[where n is the total number of the tree]

**Common types of tree Data Structures.**

* General tree data
* Binary tree
* Binary Search Tree
* AVL tree
* Red-Black tree
* Splay tree
* Treap tree and ...so on

That's it for this blog.
