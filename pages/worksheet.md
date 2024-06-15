<h1><b>Empowering Self-Publishing with Docsify-This:</b><br>A Digital Literacy Workshop</h1>

<h2>Interactive Worksheet</h2>

The open-source web app [Docsify-This.net](https://Docsify-This.net), built with the unique no-build site generator [Docsify.js.org](https://docsify.js.org), provides a quick way to publish one or more online Markdown files as standalone web pages without needing to set up your own website.

1. Display the following Markdown file URL as a standalone Web page  
   `https://github.com/paulhibbitts/github-demo-markdown-file/blob/main/README.md`
      
    <details>
      <summary>Show solution</summary>

      1. Copy and then paste the above URL into the **Markdown File URL** field  
      2. Tap the **Publish as a Standalone Web Page** button  
      ![Screenshot of solution](images/solution-1.png ':class=image-25-border')

      <a class="navpill" href="https://docsify-this.net/?url-field=https://github.com/paulhibbitts/github-demo-markdown-file/blob/main/README.md" title="Load Docsify-This with the Markdown file URL github.com/paulhibbitts/github-demo-markdown-file/blob/main/README.md" target="_blank"><i class="fas fa-check-square fa-fw"></i>Open Docsify-This with Solution</a>

   </details>

2. Display a Markdown file URL of your choice as a standalone Web page. If you do not have a Markdown file URL handy you can use the following URL  
   `https://codeberg.org/Codeberg/Documentation/src/branch/main/README.md`

    <details>
      <summary>Show solution</summary>

      1. Copy and then paste the above URL into the **Markdown File URL** field  
      2. Tap the **Publish as a Standalone Web Page** button  
      ![Screenshot of solution](images/solution-2.png ':class=image-25-border')

      <a class="navpill" href="https://docsify-this.net/?url-field=https://codeberg.org/Codeberg/Documentation/src/branch/main/README.md" title="Load Docsify-This with the Markdown file URL codeberg.org/Codeberg/Documentation/src/branch/main/README.md" target="_blank"><i class="fas fa-check-square fa-fw"></i>Open Docsify-This with Solution</a>  

    </details>

3. Visually style a displayed Markdown file using the Web Page Builder, for example change the page font family and link color  

    <details>
      <summary>Show solution</summary>

      1. Tap on **Show More Page Appearance Options** link  
      ![Screenshot of solution](images/solution-3a.png ':class=image-25-border')<br><br>
      2. Change **Page Font Family** and **Page Link Color** options  
      3. Tap the **Publish as a Standalone Web Page** button  
      ![Screenshot of solution](images/solution-3b.png ':class=image-25-border')

      <a class="navpill" href="https://docsify-this.net/?url-field=https://github.com/paulhibbitts/github-demo-markdown-file/blob/main/README.md&font-family=Merriweather,Georgia,serif&link-color=cc0000" title="Load Docsify-This with the Markdown file URL github.com/paulhibbitts/github-demo-markdown-file/blob/main/README.md, page font family Merriweather and link color cc0000" target="_blank"><i class="fas fa-check-square fa-fw"></i>Open Docsify-This with Solution</a> 

    </details>

4. Share the URL of a Web page created by Docsify-This Web Page Builder  

    <details>
      <summary>Show solution</summary>

      https://docsify-this.net/?basePath=https://github.com/paulhibbitts/github-demo-markdown-file/blob/main/README.md&font-family=Merriweather,Georgia,serif&link-color=cc0000
      
    </details>

5. Decode the URL parameters of the following raw Docsify-This Web Page URL  
`https://docsify-this.net/?basePath=https://raw.codeberg.page/paulhibbitts/codeberg-demo-markdown-file&homepage=README.md&sidebar=true&link-color=cc0000`

    <details>
      <summary>Show solution</summary>
      
      URL Parameters:  
      **basePath** = `https://raw.codeberg.page/paulhibbitts/codeberg-demo-markdown-file` (set the path containing the Markdown file to display)  
      **homepage** = README.md (set the name of the Markdown file to display)  
      **sidebar** = true (show the Sidebar)  
      **link-color** = cc0000 (set the link color to red)  
      
    </details>

6. Change the visual style of the above Web page displayed by Docsify-This using URL parameters (and not the Web Page Builder), for example set the link color to 0000ff (blue)  

    <details>
      <summary>Show solution</summary>
      
      https://docsify-this.net/?basePath=https://raw.codeberg.page/paulhibbitts/codeberg-demo-markdown-file&homepage=README.md&sidebar=true&link-color=0000ff
      
    </details>

7. Modify the below iFrame code to display the URL `https://docsify-this.net?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-lms-content-pages/main&homepage=home.md`


    ```html
    <p><iframe style="overflow: hidden; border: 0px #ffffff none; background: #ffffff;" src="https://docsify-this.net/?basePath=https://raw.codeberg.page/paulhibbitts/codeberg-demo-markdown-file&homepage=README.md&hide-credits=true" width="800px" height="1400px" allowfullscreen="allowfullscreen"></iframe></p>
    ```

    <details>
      <summary>Show solution</summary>

      ```html
      <p><iframe style="overflow: hidden; border: 0px #ffffff none; background: #ffffff;" src="https://docsify-this.net?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-lms-content-pages/main&homepage=home.md&hide-credits=true" width="800px" height="1400px" allowfullscreen="allowfullscreen"></iframe></p>
      ```
      
    </details>

STRETCH GOAL

- Create a Markdown file on either [GitHub.com](GitHub.com) or [Codeberg.org](Codeberg.org) and display it with Docsify-This

<br><p xmlns:cc="http://creativecommons.org/ns#" >This work by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://hibbittsdesign.org">Paul Hibbitts</a> is licensed under <a href="https://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""></a></p>
