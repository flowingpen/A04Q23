A04Q23
======
void delete(struct node *head)
{
// if node to be deleted is first node //
{
head=head->next;
head->prev=NULL;
}

//if node to be deleted is the last node//
{
current->prev->next=NULL;
free(current);
}

//if node to be deleted is in the middle//
{
temp->prev->next=temp->next;
temp->next=prev=temp->prev;
}
}
