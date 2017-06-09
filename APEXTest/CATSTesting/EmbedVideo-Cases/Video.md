## Verify video width is not greater than article body

### Normal video 01
<iframe width="420" height="315" src="https://www.youtube.com/embed/iyT1uILEI2U" frameborder="0" allowfullscreen></iframe>

### Verify video width is not greater than article body
<iframe width="1420" height="315" src="https://www.youtube.com/embed/iyT1uILEI2U" frameborder="0" allowfullscreen></iframe>

### Verify video source is available
<iframe width="420" height="315" src="https://www.youtube.com/embed/iyT1uILEI2" frameborder="0" allowfullscreen></iframe>
    
### Verify embed video player button is clickable (pending)
<iframe width="420" height="315" src="https://www.youtube.com/embed/iyT1uILEI2U" frameborder="0" allowfullscreen></iframe>


### video with type of link (normal)
>[!VIDEO https://sec.ch9.ms/ch9/f882/07d5474f-4235-4d89-90bc-ed008b98f882/WAMFAAnnimated_high.mp4] 
 
### video with type of link (invalid url) 
>[!VIDEO https://sec.ch9.ms/ch9/07d5474f-4235-4d89-90bc-ed008b98f882/WAMFAAnnimated.mp4] 


### video nest in table(with text)
>|1|2|
>| ------------- | ----------- |
>|<iframe width="420" height="315" src="https://www.youtube.com/embed/iyT1uILEI2U" frameborder="0" allowfullscreen></iframe>| This is table|

### video nest in table(only video in table)
>|<iframe width="420" height="315" src="https://www.youtube.com/embed/iyT1uILEI2U" frameborder="0" allowfullscreen></iframe>|
>| ------------- | 
>|<iframe width="420" height="315" src="https://www.youtube.com/embed/iyT1uILEI2U" frameborder="0" allowfullscreen></iframe> |

### video nest in list(with text)
>1. <iframe width="420" height="315" src="https://www.youtube.com/embed/iyT1uILEI2U" frameborder="0" allowfullscreen></iframe> 
>2. This is list

### video nest in list(only video in list)
>1. <iframe width="420" height="315" src="https://www.youtube.com/embed/iyT1uILEI2U" frameborder="0" allowfullscreen></iframe>

### video nest in code(with text)
>```
>This is code text
>[!VIDEO https://sec.ch9.ms/ch9/f882/07d5474f-4235-4d89-90bc-ed008b98f882/WAMFAAnnimated_high.mp4]
>```

### video nest in code(only video)
>```
>[!VIDEO https://sec.ch9.ms/ch9/f882/07d5474f-4235-4d89-90bc-ed008b98f882/WAMFAAnnimated_high.mp4]
>``` 

### Another md syntax foe inserting video(normal-01)
> [!VIDEO https://channel9.msdn.com/Events/TechEd/Europe/2014/EM-B313/player]
>
>

### Another md syntax foe inserting video(normal-02)
> [!VIDEO https://www.youtube.com/embed/iyT1uILEI2U]
>
>

### Another md syntax foe inserting video(normal-03)
> [!VIDEO https://sec.ch9.ms/ch9/f882/07d5474f-4235-4d89-90bc-ed008b98f882/WAMFAAnnimated_high.mp4]
>
>

### Another md syntax foe inserting video and invalid link
> [!VIDEO https://channel9.msdn.com/Events/TechEd/Europe/2014/EM-B313/play]
>
>

### Test video
> [!VIDEO https://hubs-video.ssl.catalog.video.msn.com/embed/acea5c8e-8699-483b-87f0-f65f80065470/IA?csid=ux-en-us&MsnPlayerLeadsWith=html&PlaybackMode=Inline&MsnPlayerDisplayShareBar=false&MsnPlayerDisplayInfoButton=false&iframe=true&QualityOverride=HD]
>
>

### Invalid video source02
> [!VIDEO https://hubs-video.ssl.catalog.video.msn/embed/acea5c8e-8699-483b-87f0-f65f80065470/IA?csid=ux-en-us&MsnPlayerLeadsWith=html&PlaybackMode=Inline&MsnPlayerDisplayShareBar=false&MsnPlayerDisplayInfoButton=false&iframe=true&QualityOverride=HD]
>
>
