## question: 二叉树的最小深度（简单）

给定一个二叉树，找出其最小深度。

最小深度是从根节点到最近叶子节点的最短路径上的节点数量。

说明：叶子节点是指没有子节点的节点。

来源：力扣（LeetCode）
链接：https://leetcode-cn.com/problems/minimum-depth-of-binary-tree


示例 1：

![示例1](https://assets.leetcode.com/uploads/2020/10/12/ex_depth.jpg)
```text
输入：root = [3,9,20,null,null,15,7]
输出：2
```

示例 2：
```text
输入：root = [2,null,3,null,4,null,5,null,6]
输出：5
```

提示：
```text
树中节点数的范围在 [0, 105] 内
-1000 <= Node.val <= 1000
```