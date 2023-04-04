task
0. print list
  * 0-print_listint.c:  function that prints all the elements of a listint_t list.
  * Return: the number of nodes
1. List length
 * 1-listint_len.c:function that returns the number of elements in a linked listint_t list.
2. Add node
 * 2-add_nodeint.c:function that adds a new node at the beginning of a listint_t list.
 * If succed return the address of the new element.
 * if failed return NULL
3. Add node at the end
 * 3-add_nodeint_end.c:function that adds a new node at the end of a listint_t list.
 * Return: the address of the new element, or NULL if it failed
4. Free list
  * 4-free_listint.c: function that frees a listint_t list.
5. Free
 *5-free_listint2.c: function that frees a listint_t list.
 *The function sets the head to NULL
6. Pop
  * 6-pop_listint.c:function that deletes the head node of a listint_t linked list, and returns the head node’s data (n).
  *if the linked list is empty return 0
7. Get node at index.
  * 7-get_nodeint.c:function that returns the nth node of a listint_t linked list.
  * where index is the index of the node, which is starting at 0
  * return NULL,if the node does not exist.
8. Sum list
  * 8-sum_listint.c: function that returns the sum of all the data (n) of a listint_t linked list.
  * return 0,if the list is empty.
9. Insert
 * 9-insert_nodeint.c: function that inserts a new node at a given position.
 * where idx is the index of the list where the new node should be added. Index starts at 0.
 * Returns: the address of the new node, or NULL if it fails.
 * if it is not possible to add the new node at index idx, do not add the new node and return NULL.
10. Delete at index.
  *  10-delete_nodeint.c:function that deletes the node at index index of a listint_t linked list.
  *  where index is the index of the node that should be deleted. Index starts at 0.
  *  if it succeeded return 1.
  *  if it fails  return -1.

11. Reverse list
   * 100-reverse_listint.c: function that reverses a listint_t linked list.
   * Returns: a pointer to the first node of the reversed list
 
12. Print (safe version).
   * 101-print_listint_safe.c:function that prints a listint_t linked list.
   *Returns: the number of nodes in the list
   *This function can print lists with a loop
   *You should go through the list only once
   *If the function fails, exit the program with status 98.

13. Free (safe version)
  * 102-free_listint_safe.c: function that frees a listint_t list.
  * This function can free lists with a loop.
  * Returns: the size of the list that was free’d
  * The function sets the head to NULL.

14. Find the loop.
   * 103-find_loop.c:  function that finds the loop in a linked list.
   * Returns: The address of the node where the loop starts, or NULL if there is no loop.
  

