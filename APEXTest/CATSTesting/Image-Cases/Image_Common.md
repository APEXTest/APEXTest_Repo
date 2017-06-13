---
# required metadata
title: This topic provides a description of Anomaly detection policies, title is more than 83 charator | Microsoft Docs
description: This topic provides a description of Anomaly detection policies and provides reference informati on about the building blocks of an anomaly detection policy.
keywords: list&meta
author: Ruixiang
ms.author: Ruixiang
manager: Yingjie
ms.date: 11/06/2016
ms.topic: article, title, English
ms.prod: .net-core
ms.service: 
ms.technology: Visual C++
ms.assetid: ab9bc377-d2f5-4f4c-a419-f1728a15d1c7

# optional metadata
#ROBOTS:
#audience:
#ms.devlang: en1111111
ms.reviewer: reutam
ms.suite: ems

#ms.tgt_pltfrm:
#ms.custom:
---

# Image

### The image displayed normal with Alt text

> ![I am flower](./../Reference-Files/Images/flower.jpg "This is title")

### The image displayed normal with no Alt text
  ![](./../Reference-Files/Images/flower.jpg)
  ![](./../Reference-Files/Images/flower.jpg)
  ![](./../Reference-Files/Images/flower.jpg)
    
### The image displayed normal with reference insert
  ![Flower][Flower]
  [Flower]: ./../Reference-Files/Images/flower.jpg
  
### invalid insert style
![flower][./../Reference-Files/Images/flower.jpg]


### invalid image source
![flower](./../Reference-Files/Images/flowers.jpg)

### Empty image source
![flower]()

### The normal image with too greater width (External image)
<img src="http://pic33.nipic.com/20130916/3420027_192919547000_2.jpg" width = "860" height ="645"/>


### The normal image with nornal width (External image)
<img src="http://pic33.nipic.com/20130916/3420027_192919547000_2.jpg" width = "200" height ="100"/>


## Image in table

| ![smile](./../Reference-Files/Images/Flower.jpg) | Only images on Row/Column |
| ------------- | ----------- |
| ![smile](./../Reference-Files/Images/Flower.jpg)  | Display the help window. |
| ![smile](./../Reference-Files/Images/Flower.jpg)  | _Closes_ a window        |
| ![smile](./../Reference-Files/Images/Flower.jpg)    | ![smile](./../Reference-Files/Images/Flower.jpg)   |

## Image in alert
> [!NOTE] 
>  Text before Image 
> ![I am flower](./../Reference-Files/Images/flower.jpg "This is title")
>  Text after Image

## Image in alert no alt message
> [!WARNING] 
> ![](./../Reference-Files/Images/flower.jpg)
>  Text after Image

## image in alert with no title
> [!TIP] 
>  Text before Image 
> ![](./../Reference-Files/Images/flower.jpg "")


## Image in alert no alt message
> [!WARNING] 
> ![I am flower][111]
> [111]:(./../Reference-Files/Images/flower.jpg)
>  Text after Image

## External image
> [!IMPORTANT] 
> External image
> <img src="http://pic33.nipic.com/20130916/3420027_192919547000_2.jpg" width = "860" height ="645"/>

## Invalid source
> [!CAUTION] 
> invalid Image source
> ![flower](./../Reference-Files/Images/flowers.jpg)

## Image in list
1. aaa
	* bbb
	* eee
	*  ![Flower](./../Reference-Files/Images/flower.jpg)
    
    
## image in list
1.  ![Flower](./../Reference-Files/Images/flower.jpg)
2. aaaa
4. cccc

### Error image in list
1. ![Flower](./../Reference-Files/Images/flowers.jpg)
2. bbb

## External image wider than main content 
> [!IMPORTANT] 
> External image
> <img src="http://pic33.nipic.com/20130916/3420027_192919547000_2.jpg" width = "1860" height ="1245"/>


[comment]: <> (![INT access rules (inbound)](./../Reference-Files/Images/flower.png))
[comment]: <> (![INT access rules (outbound)](./../Reference-Files/Images/flowerssss.png))


