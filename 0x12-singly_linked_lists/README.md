# 0x12. C - singly_linked_lists Project #
* Resource
* Read about [data structures](https://alx-intranet.hbtn.io/concepts/120) first.
* [Linked Lists](https://alx-intranet.hbtn.io/rltoken/joxg32-tt4lUh8Afgst8tA) 2008 UNSW Lecture.
* [Linked Lists Youtube Playlist](https://alx-intranet.hbtn.io/rltoken/epKUCIcoA6XaN1T3Vtr_9w)
<hr />

* All the ```*-main.c``` files will be stored in the main directory.

* Use this data structure.

```
 /**
  * struct list_s - singly linked list
  * @str: string - (malloc'ed string)
  * @len: length of the string
  * @next: points to the next node
  *
  * Description: singly linked list node structure
  * for ALX project
 */
 typedef struct list_s
 {
 	char *str;
 	unsigned int len;
 	struct list_s *next;
 } list_t;
 ```
 