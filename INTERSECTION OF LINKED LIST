/**
 * Definition for singly-linked list.
 * struct ListNode {
 *     int val;
 *     ListNode *next;
 *     ListNode(int x) : val(x), next(NULL) {}
 * };
 */
 #include<unordered_map>
class Solution {
public:
    ListNode *getIntersectionNode(ListNode *headA, ListNode *headB) {
     unordered_map<int*,int>ans;
     while(headA!=NULL)
     {
         int *s=&headA->val;
         ans[s]++;
         headA=headA->next;
     }
     while(headB!=NULL)
     {
          int *s=&headB->val;
         ans[s]++;
         if(ans[s]==2)
         {return headB;}
         headB=headB->next;
     }
     return NULL;
    }
};
