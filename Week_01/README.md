<!--
 * @Description: Daisy's work
 * @Author: Daisy
 * @Date: 2020-06-28 12:16:33
 * @LastEditTime: 2020-06-28 20:52:31
 * @LastEditors: Daisy
--> 
学习笔记：
                   prepend append lookup delete insert
  数组的时间复杂度： O(1)    O(1)    O(1)  O(n)   O(n)
  链表的时间复杂度： O(1)    O(1)    O(n)  O(1)   O(1)
  跳表的时间复杂度： O(1)    O(1)  O(lgn) O(lgn)  O(lgn)

  跳表对标：平衡二叉树和二分查找，在redis和levelDB中替代平衡树。

                             insert  delete  lookup
  stack(栈，FILO):           O(1)    O(1)    O(n)
  queue(队列，FIFO):          O(1)   O(1)    O(n)
  dequeue(双端队列):          O(1)   O(1)    O(n)
  priority queue(优先队列):   O(1)   O(lgn)

  优先队列：定义|按元素优先级取出
           实践|vip贵宾优先
           实现|heap，bst，treap