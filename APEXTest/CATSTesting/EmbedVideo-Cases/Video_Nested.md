# Video of nested
## video nest in table(with text)
>|1|2|
>| ------------- | ----------- |
>|<iframe width="420" height="315" src="https://www.youtube.com/embed/iyT1uILEI2U" frameborder="0" allowfullscreen></iframe>| This is video playable well|
>|<iframe width="420" height="315" src="https://www.youtube.com/embed/iyT1uIL" frameborder="0" allowfullscreen></iframe>| This is video can't play well|

## video nest in table(only video in table)
>|<iframe width="420" height="315" src="https://www.youtube.com/embed/iyT1uILEI2U" frameborder="0" allowfullscreen></iframe>|
>| ------------- | 
>|<iframe width="420" height="315" src="" frameborder="0" allowfullscreen></iframe> |

## video nest in list(with text)
>1. <iframe width="420" height="315" src="https://www.youtube.com/embed/iyT1uILEI2U" frameborder="0" allowfullscreen></iframe> 
>2. This is list
>3. <iframe width="420" height="315" src="https://www.youtube.com/embed/iyT1" frameborder="0" allowfullscreen></iframe> 

## video nest in list(only video in list)
>1. <iframe width="420" height="315" src="https://www.youtube.com/embed/iyT1uILEI2U" frameborder="0" allowfullscreen></iframe>
>1. <iframe width="420" height="315" src="https://www.youtube.com/embed/iyT1" frameborder="0" allowfullscreen></iframe>

## video nest in code(with text)
>```
>This is code text
>[!VIDEO https://sec.ch9.ms/ch9/f882/07d5474f-4235-4d89-90bc-ed008b98f882/WAMFAAnnimated_high.mp4]
>```

## video nest in code(only video)
>```
><iframe width="420" height="315" src="https://www.youtube.com/embed/iyT1uILEI2U" frameborder="0" allowfullscreen></iframe>
>``` 

## video nest in Alert(video)
> [!NOTE] 
> [!VIDEO https://sec.ch9.ms/ch9/f882/07d5474f-4235-4d89-90bc-ed008b98f882/WAMFAAnnimated_high.mp4]

## video nest in Alert(iframe)
> [!NOTE] 
> <iframe width="420" height="315" src="https://www.youtube.com/embed/iyT1uILEI2U" frameborder="0" allowfullscreen></iframe>

## Invalid video nest in Alert(iframe)
> [!NOTE] 
> <iframe width="420" height="315" src="https://www.youtube.com/embed/iyT" frameborder="0" allowfullscreen></iframe>
