# Kopylov Nikita


## Contact information
- [Telegram](https://t.me/eruphd)
- [GitHub](https://github.com/eruph)


## About me
Hi there! I'm a 19 years old student. I'm now a third year student. I think this course will teach me important things for further development in this area.
My goal is to be better, than i was yesterday.


## Skills
- JavaScript
- C++
- C#
- SQL
- GIT
- Python
- Net Skills


## Code example

```CPP
class Solution {
public:
    ListNode* reverseList(ListNode* head) {
        if(!head){
            return nullptr;
        }
        ListNode* reversed = nullptr;
        while(head){
            ListNode* temp = head->next;
            head->next = reversed;
            reversed = head;
            head = temp;
        }
        return reversed;
    }
};
```


## Work experience
I do only laboratory works 

## Education    
### SPBSTU
- IT and programming


## Language
- Russian(native)
- English(B1)
