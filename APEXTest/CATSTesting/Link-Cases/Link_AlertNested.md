# Link_AlertNested1

> [!NOTE] 
> | Link | Is Vaild | Markdown Style | Is Bookmark | Domain |
> |:----:|:--------:|:--------------:|:-----------:|:-----------:|
> | [#ookMarkTarget](#BookMarkTarget) | true | in line | true | Internal |
> | [https://www.google.com#sbtc](https://www.google.com#sbtc) | false | in line | true | Internal |
> | [VaildInternalBookMark][VaildInternalBookMark] | true | reference | true | Internal |
> | [InvaildInternalBookMark][InvaildInternalBookMark] | false | reference | true | Internal |
> | [TestLink](Link_AlertNested.md) | true | in line | false | Internal |
> | [/123/456](/123/456) | false | in line | false | Internal |
> | [https://www.google.com#sbtc](https://www.google.com#sbtc) | true | in line | true | External |
> | [https://www.google.com#UnavaliableBookMark](https://www.google.com#UnavaliableBookMark) | false | in line | true | External |
> | [VaildInternalLink][VaildInternalLink] | true | reference | false | Internal |
> | [InvaildInternalLink][InvaildInternalLink] | false | reference | false | Internal |
> | [https://www.google.com/](https://www.google.com/) | true | In line | false | External |
> | [https://www.google.com/404](https://www.google.com/404) | true | In line | false | External 
> | [VaildExternalLink][VaildExternalLink] | true | reference | false | External |
> | [InvaildExternalLink][InvaildExternalLink] | false | reference | false | External |
> | [VaildExternalBookMark][VaildExternalBookMark] | true | reference | true | External |
> | [InvaildExternalBookMark][InvaildExternalBookMark] | false | reference | true | External |  

## BookMarkTarget

[VaildInternalLink]: Link_AlertNested.md 
[InvaildInternalLink]: /123/456.md  
[VaildExternalLink]: https://www.google.com/  
[InvaildExternalLink]: https://www.google.com/404
[VaildInternalBookMark]: #BookMarkTarget
[InvaildInternalBookMark]: #UnavaliableBookMark 

[VaildExternalBookMark]: https://www.google.com#sbtc  <br />
[InvaildExternalBookMark]: https://www.google.com#UnavaliableBookMark   <br />
