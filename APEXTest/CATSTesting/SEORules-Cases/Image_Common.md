---
# required metadata
title: This topic provides Images verfication - SEO Rules | Microsoft Docs
description: This topic provides test cases in CATS to validate content with SEO rules - Images

# optional metadata
#ROBOTS:
#audience:
#ms.devlang: en1111111
ms.reviewer: reutam
ms.suite: ems

#ms.tgt_pltfrm:
#ms.custom:
---

# SEO Rules on Images - Alt text and file name

## Alt text for image
+ Missing image Alt text
  - Each image in any article should have an Alt text
+ Image Alt text length
  - Image Alt text should contain 30-70 characters, including spaces.
+ Duplicated image Alt text
  - Each image Alt text within an article is unique.
## Image file name
- Image file name without hyphens
  + Each image file name should contain hyphens.
- Image file name length
  - Each image file name should contain 20 or more characters, including hyphens.

### The image displayed normal with Alt text

> ![The image displayed normal with Alt text](./../Reference-Files/Images/BlackAndWhite[Cow]-512.png "This is title")

### Image Alt text length
  ![Alt text is 25 characters](./../Reference-Files/Images/Sun-Shining-On-Flower-Image.jpg)  

  ![Alt text that is 29 character](./../Reference-Files/Images/Sun-Shining-On-Flower-Image.jpg)  

  ![Alt text that is 30 characters](./../Reference-Files/Images/Sun-Shining-On-Flower-Image.jpg)  

  ![Indicate which image has an Alt text that lenth equal to 70 characters](./../Reference-Files/Images/Sun-Shining-On-Flower-Image.jpg)  

  ![Indicate that image has an Alt text that is more than 70 characters(71)](./../Reference-Files/Images/Sun-Shining-On-Flower-Image.jpg)  

  ![Indicate which image has an Alt text that is more than 70 characters, including spaces](./../Reference-Files/Images/Sun-Shining-On-Flower-Image.jpg)  

    
### The image displayed normal with reference insert
  ![Flower - with reference insert][Flower]
  [Flower]: ./../Reference-Files/Images/flower.jpg
  
### invalid insert style
![Flower - invalid insert style][./../Reference-Files/Images/Sun-Shining-On-Flower-Image.jpg]


### invalid image source
![Flower - invalid image source](./../Reference-Files/Images/Sun-Shining-On-Flower-Image.jpg)

### Empty image source
![Flower - Empty image source]()

### The normal image with too greater width (External image)
<img src="http://pic33.nipic.com/20130916/3420027_192919547000_2.jpg" width = "860" height ="645"/>


### The normal image with nornal width (External image)
<img src="http://pic33.nipic.com/20130916/3420027_192919547000_2.jpg" width = "200" height ="100"/>


## Images in table and verify file name length

| ![Alt Text "Image shows on table header"](./../Reference-Files/Images/Flower.jpg) | Only images on Row/Column |
| ------------- | ----------- |
| ![File name is tinypngmagent-image](./../Reference-Files/Images/tinypngmagent-image.jpg) | Image file name _equals_ to 19 |
| ![File name is tinypng-magent-image](./../Reference-Files/Images/tinypng-magent-image.jpg) | Image file name equals to 20 |
| ![File name is tinypng-magent-images](./../Reference-Files/Images/tinypng-magent-images.jpg) | Image file name equals to 21 |
| ![File name is tinypng-magent-image](./../Reference-Files/Images/tinypng-magent-image.jpg) | ![~`1!2@3#4$5%6^7&_-+=,.';](./../Reference-Files/Images/~`1!2@3#4$5%6^7&_-+=,.';.jpg) |

## Image in alert
> [!NOTE] 
>  Text before Image 
> ![I am flower](./../Reference-Files/Images/cartoon&baby~animals(clipart)30.jpg "This is title")
>  Text after Image

## Image in alert no alt message
> [!WARNING] 
> ![](./../Reference-Files/Images/~`1!2@3#4$5%6^7&_-+=,.';.jpg)
>  Text after Image

## image in alert with no title
> [!TIP] 
>  Text before Image 
> ![](./../Reference-Files/Images/flower.jpg "")


## Image in alert no alt message
> [!WARNING] 
> ![I am flower][111]
> [111]:./../Reference-Files/Images/flower.jpg
>  Text after Image

## External image
> [!IMPORTANT] 
> External image
> <img src="https://mvapublicstorage.microsoft.com/tiles/MVA_Homepage_Tiles-24.png" alt="Database Development" width = "860" height ="645"/>

## Invalid source
> [!CAUTION] 
> invalid Image source
> ![Error with No such image in folder](./../Reference-Files/Images/flowers.jpg)

## Image in list
1. aaa
	* bbb
	* eee
	*  ![The flower image lists in last](./../Reference-Files/Images/Sun-Shining-On-Flower-Image.jpg)
    
    
## image in list
1.  ![The flower image lists in first](./../Reference-Files/Images/Sun-Shining-On-Flower-Image.jpg)
2. aaaa
4. cccc

### Error image in list
1. ![Error with No such image in folder](./../Reference-Files/Images/flowers.jpg)
2. bbb

## External image wider than main content and no alt!
> [!IMPORTANT] 
> External image, no alt, file name contains no hyphen
> <img src="http://pic33.nipic.com/20130916/3420027_192919547000_2.jpg" width = "1860" height ="1245"/>

## Image as link text 
[![Image as link text - Internallink](./../Reference-Files/Images/Sun-Shining-On-Flower-Image.jpg)](./../Reference-Files/Images/gif.gif)

[![Image as link text - Link a MD](./../Reference-Files/Images/bmp.bmp)](./../Image-Cases/index.md)

[![Image as link text - ExternalLink](./../Reference-Files/Images/jpeg.jpeg)](http://www.baidu.com/)



