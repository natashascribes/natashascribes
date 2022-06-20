# Docsify Features


## Embed a YouTube video

iFrames from YouTube are now supported, allowing videos from that domain to be embedded into markdown documents. 

><span style="color:red">**Important:**</span> You must check that your youtube link is set to **embed**. For example, https://youtu.be/ehKXKAX3TSo and Windows: https://youtu.be/Cvb7lppxFqs should be replaced with https://youtube.com/embed/ehKXKAX3TSo and https://youtube.com/embed/Cvb7lppxFqs. 

**iFrames sample:**
https://stg.docs.developer.tech.gov.sg/docs/test-repo/#/?id=iframes-test

https://www.developer.tech.gov.sg/products/categories/devops/ship-hats/subscription

**Sample code:**

<iframe src="https://www.youtube.com/embed/ksUEnR78m4w?showinfo=0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<ifigure> 
<iframe title="YouTubeVideoPlayer" src="https://www.youtube.com/embed/ksUEnR78m4w?showinfo=0" height="315" width="560" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</ifigure>

---
<iframe src="https://www.youtube.com/embed/ehKXKAX3TSo?showinfo=0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<ifigure> 
<iframe title="YouTubeVideoPlayer" src="https://www.youtube.com/embed/ehKXKAX3TSo?showinfo=0" height="315" width="560" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</ifigure>
https://www.youtube.com/watch?v=ehKXKAX3TSo

---

<iframe src="https://www.youtube.com/embed/Cvb7lppxFqs" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<ifigure> 
<iframe title="YouTubeVideoPlayer" src="https://www.youtube.com/embed/Cvb7lppxFqs" height="315" width="560" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</ifigure>

https://www.youtube.com/watch?v=Cvb7lppxFqs

## Docsify hyperlink colors

Docsify hyperlink colors are now in blue allowing clickable links to be more obvious 



**Docsify hyperlinks sample:**  
https://stg.docs.developer.tech.gov.sg/docs/test-repo/#/excel-download

## Content Reuse

1. Create a folder called `snippets` in your repo. 
2. Add any snippet markdown files within this repo. For example, snippet-resusefilename.md
3. You can reuse this content in multiple ways:
- **Option 1: Add content within an existing markdown file**  
    
    To do this, open the file where you want to reuse this content and this code
    
    The following would render as text in the reusable markdown file. This may appear as a link in source preview bit would render as embedded text in output. Please verify in output.  
     
    [Add a suitable name](snippets/snippet-resusefilename.md ':include')

    The following would render as a code: 

    [Add a suitable name](snippets/snippet-resusefilename.md ':include :type=code')
- **Option 2: Use the file as regular markdown file**  

    To do this, use the following syntax:
    - [Snippet Sample](snippets/snippet-resusefilename)


## To embed an MP4 file into the doc

[filename](snippets/example.mp4 ':include :type=video controls width=100%')