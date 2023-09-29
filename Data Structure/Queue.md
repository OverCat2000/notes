## class
```
public class MyQueue {  
int arr[];  
int front;  
int rear;  
  
public MyQueue(int size) {  
this.arr = new int[size];  
this.front = -1;  
this.rear = -1;  
}
```

## enqueue

only rear is changed
rear is at last added element
if not full
	rear is increased and new element added
	when rear goes to end (when full)
		rear is set to 0 
	at start if front = -1
		then changed to 0

## dequeue

only front is changed
front is always at first added element
if not empty
	front value is stored in temp
	front value is set to 0
	**in the special case occur when only one element is added
	front = rear = 0
	and the case when last element **
	front and rear is set to default value -1
	otherwise front is increased
	when front reaches end (when empty)
		front is set to 0