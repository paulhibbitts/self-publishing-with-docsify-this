# An Introduction to Self-Publishing with Docsify-This

Welcome to the 'Empowering Self-Publishing with Docsify-This: A Digital Literacy Workshop'! This online resource summarizes key concepts and provides resources to help you explore further.

## Unlocking the Power of Self-Publishing

This overview introduces Markdown publishing using **Docsify-This**, an open-source project available at https://Docsify-This.net (built with the magical documentation site generator https://docsify.js.org) that turns Markdown files into web pages. It covers the basics of Markdown, its advantages, and various tools and scenarios for publishing Markdown files as standalone web pages or embedded content.

---

## BASICS

### Fundamental Elements

#### Plain Text Files
- **Overview**: Plain text files are simple, unformatted text files that can be read and edited with any text editor. They are the foundation for Markdown documents used in Docsify-This.
- **Activity**: Create and edit a plain text file using TextEdit (Mac), Notepad (Windows) or any available text editor.
- **Resources**:
  - [What is a Plain Text File?](https://en.wikipedia.org/wiki/Plain_text)

#### URL Parameters
- **Overview**: URL parameters help specify how content is accessed and displayed in Docsify-This. They can define the base URL, homepage, visual appearance and which elements are visible within the site. An example URL created by Docsify-This would be https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-one-page-article/main&homepage=home.md&sidebar=true
- **Activity**: Edit a URL created by Docsify-This to change the visual appearance of the page displayed.
- **Resources**:
  - [What is a URL - Parameters](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics/What_is_a_URL#parameters)
  - [Docsify-This Page Appearance URL Parameters](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/publishing-with-docsify-this/main&sidebar=true&browser-tab-title=Markdown%20Publishing%20with%20Docsify-This&edit-link=https://github.com/hibbitts-design/publishing-with-docsify-this/blob/main/README.md&edit-link-text=Suggest%20an%20Edit%20for%20this%20Page&maxLevel=3&coverpage=_coverpage.md&zoom-images=true&dark-mode=true#/?id=docsify-this-web-page-appearance)

### Creating and Using Markdown

#### Writing in Markdown
- **Overview**: Markdown is a lightweight markup language for creating formatted text using a plain-text editor. It's simple to learn and widely used for documentation and web content.
- **Activity**: Write a document in Markdown with headings, lists, links, and images.
- **Resources**:
  - [Markdown Guide](https://www.markdownguide.org/)
  - [Interactive Markdown Tutorial](https://www.markdowntutorial.com/)

#### Markdown Editors
- **Overview**: Various tools can enhance the experience of writing and editing Markdown. These editors provide features like live preview, syntax highlighting, and integration with other tools.
- **Key Points**:
  - **Features**: Look for live preview, syntax highlighting, and ease of use.
- **Activity**: Try out different Markdown editors to find one that suits your needs.
- **Popular Editors**:
  - **[Visual Studio Code (VS Code)](https://code.visualstudio.com/)**: Powerful, with extensive Markdown support.
  - **[Typora](https://typora.io/)**: Distraction-free, WYSIWYG Markdown editor.
  - **[MarkdownPad](http://markdownpad.com/)**: Windows-based editor with live preview and export options.

#### Using GitHub or Codeberg for Markdown Editing
- **Overview**: GitHub and Codeberg offer built-in editors for creating and editing Markdown files directly in your repository. These platforms can also support version control and collaborationof the Markdown files displayed by Docsify-This.
- **Key Points**:
  - **Convenience**: Edit Markdown files directly in your repository without needing external tools.
  - **Collaboration**: Use built-in features to collaborate with others on Markdown documents.
  - **Version Control**: Automatically track changes and maintain version history.
- **Activity**: Edit a Markdown file directly in a GitHub or Codeberg repository and commit your changes.
- **Resources**:
  - [GitHub: Working with Markdown Files](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
  - [Codeberg Documentation](https://docs.codeberg.org/)

#### Publishing Markdown Content
- **Overview**: Display Markdown files as published web pages using Docsify-This. This allows for presentation and styling of web content.
- **Activity**: Publish a Markdown file as a web page using Docsify-This.net.
- **Resources**:
  - [Docsify⁠–⁠This.net](https://docsify-this.net)
  - [Publishing with Docsify⁠–⁠This Guide](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/publishing-with-docsify-this/main&sidebar=true&browser-tab-title=Markdown%20Publishing%20with%20Docsify-This&edit-link=https://github.com/hibbitts-design/publishing-with-docsify-this/blob/main/README.md&edit-link-text=Suggest%20an%20Edit%20for%20this%20Page&maxLevel=3&coverpage=_coverpage.md&zoom-images=true&dark-mode=true)

#### Embedding (Inclusion) vs. Duplication of Content
- **Overview**: Embedding allows you to include content from other files dynamically, avoiding duplication and maintaining consistency.
- **Activity**: Embed Markdown content using Docsify-This into another platform, such as an LMS or CMS.
- **Resources**:
  - [Embedding Docsify-This Pages](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/publishing-with-docsify-this/main&sidebar=true&browser-tab-title=Markdown%20Publishing%20with%20Docsify-This&edit-link=https://github.com/hibbitts-design/publishing-with-docsify-this/blob/main/README.md&edit-link-text=Suggest%20an%20Edit%20for%20this%20Page&maxLevel=3&coverpage=_coverpage.md&zoom-images=true&dark-mode=true#/?id=embedding-docsify-this-pages)

---

## ADVANCED

### Version Control & Collaboration

#### GitHub/Codeberg Basics
- **Overview**: Version control systems like GitHub and Codeberg are essential for managing changes and collaborating on Docsify-This projects. They track file history and facilitate collaboration.
- **Activity**: Set up a repository on GitHub, commit changes, and collaborate on a Docsify-This project.
- **Resources**:
  - [GitHub Guides](https://guides.github.com/)
  - [Codeberg User Documentation](https://docs.codeberg.org/)

### Technical Considerations

#### Static vs. Dynamic Websites (Including Hosting)
- **Overview**: Static websites serve pre-rendered content, while dynamic websites generate content on-the-fly. Understanding their differences helps in choosing the right solution for your project.
- **Activity**: Deploy a Docsify-This page on a static hosting platform like GitHub 

#### CSR (Client-side Rendering) vs. SSR (Server-side Rendering)
- **Overview**: CSR renders content in the browser, offering a dynamic and interactive user experience, while SSR pre-renders content on the server, often leading to faster initial loads.
- **Activity**: Explore how Docsify-This uses CSR to dynamically render content.
- **Resources**:
  - [Server Side Rendering vs Client Side Rendering vs Server Side Generation](https://www.geeksforgeeks.org/server-side-rendering-vs-client-side-rendering-vs-server-side-generation/)

_This educational resource was partially created with the assistance of ChatGPT, an AI language model developed by OpenAI. ChatGPT provided suggestions, draft content, and ideas which were reviewed and adapted by the author._