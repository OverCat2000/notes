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

if not full
	only rear is changed
	rear is at last added element
	rear is increased and new element added
	if front = -1
		then changed to 0
	
	