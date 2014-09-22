---
layout: post
title: "[leetcode] Symmetric Tree 题解"
description: "[leetcode] Symmetric Tree 题解"
category: leetcode 
tags: [leetcode, c++, binary tree, recursion]
---
{% include JB/setup %}


题目来源：[Symmetric Tree](https://oj.leetcode.com/problems/symmetric-tree/)

>
	Given a binary tree, check whether it is a mirror of itself (ie, symmetric around its center).
	
解题思路：
左节点的左子树 ＝ 右节点的由子树。 
解题方法跟[same tree](TODO_PRE/same-tree.html)差不多。

####0.递归

{% highlight cpp %}
	
	bool isSymmetric(TreeNode* node1, TreeNode* node2)
{% endhighlight %}

####1.迭代
{% highlight cpp %}

	bool isSymmetric(TreeNode *root)

 