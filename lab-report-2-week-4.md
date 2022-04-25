# WEEK 4 LAB REPORT 

## Screenshot of Code Change

I changed the original code of `MarkdownParse.java` to accomodate a case like [this](https://github.com/Maanasa64/markdown-parser/commit/03c8bf4a407bd5305550be13e85b2709265c32a7)

![Image](CodeChange.png)

I made a [new file](https://github.com/Maanasa64/markdown-parser/commit/cf45f57b5954677481483791a5c6868996ffc8ce#diff-c1ee2d48f5f64b4463a98907818b5846f49cc9dd67f88882a8b551106ec320fb) that can show the the input that shows the failure.

![Image](newFile.png)

*Ouput*
`Exception in thread "main" java.lang.OutOfMemoryError: Java heap space
        at java.base/java.lang.StringLatin1.newString(StringLatin1.java:769)
        at java.base/java.lang.String.substring(String.java:2709)
        at MarkdownParse.getLinks(MarkdownParse.java:19)
        at MarkdownParse.main(MarkdownParse.java:30)`
       
       
 *Expected*
` [https://something.com, some-thing.html]`

