---
# required metadata

title: This topic provides a description of Anomaly detection policies and provides reference information | Microsoft Docsfffff
description: This topic provides a description of Anomaly detection policies and provides reference information about the building blocks of an anomaly detection policy.
keywords:
author: rkarlin
ms.author: rkarlin
manager: mbaldwin
ms.date: 11/6/2016
ms.topic: article
ms.prod: article
ms.service: cloud-app-security
ms.technology:
ms.assetid: ab9bc377-d2f5-4f4c-a419-f1728a15d1c7

# optional metadata

#ROBOTS:
#audience:
#ms.devlang:
ms.reviewer: reutam
ms.suite: ems
#ms.tgt_pltfrm:
#ms.custom:

---

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
