## qurestion: 二叉树的层序遍历（中等）

给你二叉树的根节点 root ，返回其节点值的 层序遍历 。 （即逐层地，从左到右访问所有节点）。

来源：力扣（LeetCode）
链接：https://leetcode-cn.com/problems/binary-tree-level-order-traversal

示例 1：

![示例1](https://assets.leetcode.com/uploads/2021/02/19/tree1.jpg)
```text
输入：root = [3,9,20,null,null,15,7]
输出：[[3],[9,20],[15,7]]
```

示例 2：
```text
输入：root = [1]
输出：[[1]]
```

示例 3：
```text
输入：root = []
输出：[]
```

提示：
```text
树中节点数目在范围 [0, 2000] 内
-1000 <= Node.val <= 1000
```