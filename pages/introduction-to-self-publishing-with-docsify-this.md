# An Introduction to Self-Publishing with Docsify-This

Welcome to the 'Empowering Self-Publishing with Docsify-This: A Digital Literacy Workshop'! This online resource summarizes key concepts and provides resources to help you explore further.

<h2> Unlocking the Power of Self-Publishing </h2>

This overview introduces Markdown publishing using **Docsify-This**, an open-source project available at https://Docsify-This.net (built with the magical documentation site generator https://docsify.js.org) that turns Markdown files into web pages. It covers the basics of Markdown, its advantages, and various tools and scenarios for publishing Markdown files as standalone web pages or embedded content.

---

## BASICS

### Fundamental Elements

#### Plain Text Files
- **Overview**: Plain text files are simple, unformatted text files that can be read and edited with any text editor. They are the foundation for Markdown documents used in Docsify-This.
- **Activity**: Create and edit a plain text file using TextEdit (Mac), Notepad (Windows) or any available text editor.
- **Resources**:
  - [What is a Plain Text File?](https://en.wikipedia.org/wiki/Plain_text)

#### Markdown Format
- **Overview**: Markdown is a lightweight markup language for creating formatted text using a plain-text editor. It's simple to learn and widely used for documentation and web content.
- **Activity**: Write a document in Markdown with headings, lists, links, and images.
- **Resources**:
  - [Markdown Guide](https://www.markdownguide.org/)
  - [Interactive Markdown Tutorial](https://www.markdowntutorial.com/)

#### URL Parameters
- **Overview**: URL parameters help specify how content is accessed and displayed in Docsify-This. They can define the base URL, homepage, visual appearance and which elements are visible within the site. An example URL created by Docsify-This would be https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-one-page-article/main&homepage=home.md&sidebar=true.
- **Activity**: Edit a URL created by Docsify-This to change the visual appearance of the page displayed.
- **Resources**:
  - [What is a URL - Parameters](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics/What_is_a_URL#parameters)
  - [Docsify-This Page Appearance URL Parameters](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/publishing-with-docsify-this/main&sidebar=true&browser-tab-title=Markdown%20Publishing%20with%20Docsify-This&edit-link=https://github.com/hibbitts-design/publishing-with-docsify-this/blob/main/README.md&edit-link-text=Suggest%20an%20Edit%20for%20this%20Page&maxLevel=3&coverpage=_coverpage.md&zoom-images=true&dark-mode=true#/?id=docsify-this-web-page-appearance)

### Using Markdown Content

#### Publishing Markdown Files
- **Overview**: Display Markdown files as published web pages using Docsify-This. This allows for presentation and styling of web content.
- **Activity**: Publish a Markdown file of your choice as a web page using Docsify-This.net.
- **Resources**:
  - [Docsify⁠–⁠This.net](https://docsify-this.net)
  - [Publishing with Docsify⁠–⁠This Guide](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/publishing-with-docsify-this/main&sidebar=true&browser-tab-title=Markdown%20Publishing%20with%20Docsify-This&edit-link=https://github.com/hibbitts-design/publishing-with-docsify-this/blob/main/README.md&edit-link-text=Suggest%20an%20Edit%20for%20this%20Page&maxLevel=3&coverpage=_coverpage.md&zoom-images=true&dark-mode=true)

#### Desktop Markdown Editors
- **Overview**: Various tools can enhance the experience of writing and editing Markdown. These editors provide features like live preview, syntax highlighting, and integration with other tools.
- **Key Points**:
  - **Features**: Look for live preview, syntax highlighting, and ease of use.
- **Activity**: Try out different Markdown editors to find one that appeals to you.
- **Popular Editors**:
  - **[Visual Studio Code (VS Code)](https://code.visualstudio.com/)**: Powerful, with extensive Markdown support.
  - **[Typora](https://typora.io/)**: Distraction-free, WYSIWYG Markdown editor.
  - **[MarkdownPad](http://markdownpad.com/)**: Windows-based editor with live preview and export options.

#### GitHub or Codeberg Editors
- **Overview**: [GitHub](https://github.com/) and [Codeberg](https://codeberg.org/) offer built-in Web editors for creating and editing Markdown files directly in your repository. These platforms can also support [Git](https://en.wikipedia.org/wiki/Git) version control and collaboration of the Markdown files displayed by Docsify-This.
- **Requirements**: A GitHub or Codeberg account.
- **Key Points**:
  - **Convenience**: Edit Markdown files directly in your repository without needing external tools.
  - **Collaboration**: Use built-in features to collaborate with others on Markdown documents.
  - **Version Control**: Automatically track changes and maintain version history.
- **Activity**: Edit a Markdown file directly in a GitHub or Codeberg repository and commit your changes.
- **Resources**:
  - [GitHub: Working with Markdown Files](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
  - [Codeberg Documentation](https://docs.codeberg.org/)

#### Embedding vs. Duplicating Content
- **Overview**: Embedding allows you to include content from other files dynamically, avoiding duplication and maintaining consistency.
- **Activity**: Embed the content of a Markdown file using Docsify-This into another platform, such as an LMS or CMS.
- **Resources**:
  - [Embedding Docsify-This Pages](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/publishing-with-docsify-this/main&sidebar=true&browser-tab-title=Markdown%20Publishing%20with%20Docsify-This&edit-link=https://github.com/hibbitts-design/publishing-with-docsify-this/blob/main/README.md&edit-link-text=Suggest%20an%20Edit%20for%20this%20Page&maxLevel=3&coverpage=_coverpage.md&zoom-images=true&dark-mode=true#/?id=embedding-docsify-this-pages)

---

## ADVANCED

### Version Control & Collaboration

#### GitHub and Codeberg Git Services
- **Overview**: [Git](https://en.wikipedia.org/wiki/Git) version control systems like [GitHub](https://github.com/) and [Codeberg](https://codeberg.org/) are essential for managing changes and collaborating on Docsify-This projects. They track file history and facilitate collaboration.
- **Requirements**: A GitHub or Codeberg account.
- **Activity**: Set up a repository on GitHub or Codeberg, and then collaborate on one or more Markdown files within that repository.
- **Resources**:
  - [GitHub Guides](https://guides.github.com/)
  - [Codeberg User Documentation](https://docs.codeberg.org/)

#### HedgeDoc Collab Editor
- **Overview**: [HedgeDoc](https://hedgedoc.org/) is an open-source, real-time collaborative Web Markdown editor. It allows multiple users to edit a document simultaneously, making it an excellent tool for collaborative writing and content creation.
- **Requirements**: Your own Hedgedoc server and your own instance of Docsify-This configured with your HedgeDoc server URL (both documented on the https://Docsify-This.net web page).
- **Key Points**:
  - **Real-Time Collaboration**: Multiple users can edit the same document at the same time, with changes visible instantly.
  - **Markdown Support**: HedgeDoc provides robust Markdown support with live preview, making it easy to see the formatted output as you write.
  - **Ease of Use**: With its user-friendly interface, HedgeDoc is accessible to users of all skill levels, requiring no prior experience with Markdown or version control systems.
- **Activity**: Create a document on the [demo HedgeDoc server](https://hedgedoc.org/demo/), invite a collaborator, and work together on the doc. Then, copy the document URL (e.g. `https://demo.hedgedoc.org/oisWMy9ZS36PE6TvYhJC4A`) and display that document using the Docsify-This instance at https://hibbitts-design.github.io/hedgedoc-docsify-this.
- **Resources**:
  - [HedgeDoc Official Site](https://hedgedoc.org/)
  - [HedgeDoc Documentation](https://docs.hedgedoc.org/)

### Technical Aspects

#### Client vs Server Rendering
- **Overview**: CSR (Client-side Rendering) renders content in the browser, avoiding any required build process, while SSR (Server-side Rendering) pre-renders content on the server side, leading to faster initial loads and more search engine friendly static HTML pages.
- **Activity**: Explore how Docsify-This uses CSR via [Docsify](https://docsify.js.org) to dynamically render Markdown content vs such SSR platforms such as [Jekyll](https://jekyllrb.com/) and [Docusaurus](https://docusaurus.io/) that render Markdown content to static HTML pages.
- **Resources**:
  - [Server Side Rendering vs Client Side Rendering vs Server Side Generation](https://www.geeksforgeeks.org/server-side-rendering-vs-client-side-rendering-vs-server-side-generation/)

---

## ADDITIONAL RESOURCES

### Videos

 - Open Publishing Ecosystems: Docsify This (courtesy of [Reclaim Hosting](https://www.reclaimhosting.com/))
  - https://www.youtube.com/embed/EjeqxOJ2ZxE

### Articles and Guides

- Basic Syntax | Markdown Guide
  - https://www.markdownguide.org/basic-syntax
- Improving The Accessibility Of Your Markdown
  - https://www.smashingmagazine.com/2021/09/improving-accessibility-of-markdown
- OER on GitHub What, Why, & How
  - https://evanwill.github.io/make-oer

### Desktop Apps

- Markdown Desktop Editors
  - https://code.visualstudio.com/
  - https://typora.io
- GitHub Desktop App (can also be used with Codeberg)
  - https://desktop.github.com

_This educational resource was partially created with the assistance of ChatGPT, an AI language model developed by OpenAI. ChatGPT provided suggestions, draft content, and ideas which were reviewed and adapted by the author._
