# Linked-List-Cycle-II
Given the head of a linked list, return the node where the cycle begins. If there is no cycle, return null

There is a cycle in a linked list if there is some node in the list that can be reached again by continuously following the next pointer. Internally, pos is used to denote the index of the node that tail's next pointer is connected to (0-indexed). It is -1 if there is no cycle. Note that pos is not passed as a parameter.

https://leetcode.com/problems/linked-list-cycle-ii/

![image](https://user-images.githubusercontent.com/109743699/184211505-60fe4f95-7c65-428a-998f-15118bb011d0.png)

Input: head = [3,2,0,-4], pos = 1

Output: tail connects to node index 1

Explanation: There is a cycle in the linked list, where tail connects to the second node
