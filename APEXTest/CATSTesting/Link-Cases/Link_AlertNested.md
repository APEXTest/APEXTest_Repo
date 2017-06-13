# Link_AlertNested1

> [!NOTE] 
> | Link | Is Vaild | Markdown Style | Is Bookmark | Domain |
> |:----:|:--------:|:--------------:|:-----------:|:-----------:|
> | [Link1](#BookMarkTarget) | true | in line | true | Internal |
> | [Link2](https://www.google.com#sbtc) | false | in line | true | Internal |
> | [Link3][VaildInternalBookMark] | true | reference | true | Internal |
> | [Link4][InvaildInternalBookMark] | false | reference | true | Internal |
> | [Link5](TestLink.md) | true | in line | false | Internal |
> | [Link6](/123/456) | false | in line | false | Internal |
> | [Link7](https://www.google.com#sbtc) | true | in line | true | External |
> | [Link8](https://www.google.com#UnavaliableBookMark) | false | in line | true | External |
> | [Link9][VaildInternalLink] | true | reference | false | Internal |
> | [Link10][InvaildInternalLink] | false | reference | false | Internal |
> | [Link11](https://www.google.com/) | true | In line | false | External |
> | [Link12](https://www.google.com/404) | true | In line | false | External 
> | [Link13][VaildExternalLink] | true | reference | false | External |
> | [Link14][InvaildExternalLink] | false | reference | false | External |
> | [Link15][VaildExternalBookMark] | true | reference | true | External |
> | [Link16][InvaildExternalBookMark] | false | reference | true | External |  

## BookMarkTarget

[VaildInternalLink]: TestLink.md 
[InvaildInternalLink]: /123/456  
[VaildExternalLink]: https://www.google.com/  
[InvaildExternalLink]: https://www.google.com/404
[VaildInternalBookMark]：#BookMarkTarget
[InvaildInternalBookMark]: #UnavaliableBookMark 

[VaildExternalBookMark]: https://www.google.com#sbtc  
[InvaildExternalBookMark]: https://www.google.com#UnavaliableBookMark  
