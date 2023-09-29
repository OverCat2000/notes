## class
```
public class MyStack {  
private int[] arr;  
private int top;  
private int size;  
  
public MyStack(int size) {  
this.size = size;  
this.top = -1;  
this.arr = new int[size];  
}
```

## push

if stack not full
	increase top++
	arr[top] = data

## pop

if stack not empty
	~~return top element~~
	store top element
	**assign 0 to top position**
	then return stored value

## isFull

if 
	top element reached size

## isEmpty

if 
	top = -1

dd
