# List
## Unordered list
### Bulleted list with empty item
* aaa
* bbb
* 
* ccc


### Bulleted list start with "*+-" 
* aaa
+ bbb
- ccc
*   ```On July 3, the Black Knights, a squadron of Marine Corps F/A-18 Hornets, participated```
+ 

### Verify error when no indenting after "*"/"+"/"-" 
* | Normal table | Description          |
  | ------------- | ----------- |
  | 1_Help      | Display the help window.|
  | Close     | _Closes_ a window     |
* b
* | Normal table | Description          |
  | ------------- | ----------- |
  | 1_Help      | Display the help window.|
  | Close     | _Closes_ a window     |

### Verify error when no indenting after "*"/"+"/"-" 
* aaa
	1. test1
	2. test2			
* bbb
* ccc

## Ordered list
### ordered list with empty item
1. aaa
2. 
3. bbb
4. ccc


### Verify image as nested list item
1. aaa1
	* ![I am flower](./Images/flower.jpg "This is A/t text")
	* ![I am flower](./Images/flower.jpg "This is A/t text")
	* 
3. test
	7. hhh
	9. 
4. test
5. 
	
### Verify Image as list item
1. ![I am flower](./Images/flower.jpg "This is A/t text")
2. aaaa
3. 
4. cccc

### Verify nested list
1. aaa
	* bbb
	* eee
	*  

### Verify list nested alert
1. aaa
	3. > [!NOTE] Sample Notification Message
	2. 
2. 
2. bbb

### Verify nested list
1. aaa	
* bbb	
* eee	
*  ![Flower](/Image/Flower.jpg)
3. ccc
	7. hhh
	9. kkk
	
### Verify Image list
1.  ![Flower](/Image/Flower.jpg)
2. aaaa
3. 
4. cccc

### Verify alert nested list
> [!TIP] 
>Bulleted list with empty item
>* aaa
>* bbb
>* 

### Verify list nested alert
1. aaa
	>3. > [!NOTE] 
		> Sample Notification Message
	>2. > [!WARNING] 
		> Sample Warning Message
2. 
2. bbb

### Code snippet
1. abc
	>1. 
		test1
	>2. 
		test2
	>3. 

2. abc

### Verify table nested list
|Table nest List|Description|Supported templates|
|-------------|-----------|-------------------|
|Project templates|Types of projects available in the **New Project** dialog box.|<ul><li>F# Application<br /></li><li><br /></li><li>F# Tutorial<br /></li><li>F# Portable Library<br /></li><ul/>|
	
	
### List nest with alert 1
* item 1
* item 2
> [!NOTE] 
> Sample Notification Message
* item 3


### List nest with alert 2
1. item 1
2. item 2
> [!NOTE] 
> Sample Notification Message
3. item 3

### List nest with alert 3
1. item 1
2. item 2

> [!NOTE] 
> Sample Notification Message
3. item 3
