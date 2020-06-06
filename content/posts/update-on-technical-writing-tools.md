+++
canonical_url = ""
content_img_path = "/images/tutorials.jpg"
date = 2020-06-04T14:00:00Z
excerpt = "This post starts a series of posts on technical writing tools that I use or plan to use."
layout = "post"
subtitle = ""
thumb_img_path = "/images/tutorials.jpg"
title = "Update on technical writing tools"

+++
# Technical Writing Tools

> **_You_**'**_ll never know until you try_**.

It's been only 3 months since I've started experimenting with static site generators, Markdown, AsciiDoc, and other interesting things. In these posts I want to tell you about my experience in this area: what I liked and where I failed.

## Visual Studio Code

{{< figure src="/images/vscode.png" >}}

<br>

This is a multi-purpose tool: developers use it for coding as an IDE. However, I found out that some technical writers use VSCode for writing and editing their documents.

Here are some basics that I use in VSCode:

1. Download and install VSCode:  
   [https://code.visualstudio.com/download](https://code.visualstudio.com/download "https://code.visualstudio.com/download")
2. Open your project folder: `Ctrl+O`
3. Use VSCode for git commands:  
    {{< figure src="/images/vscode-git.png" >}}
4. Toggle word wrap: `Alt+Z`
5. Open **Extensions** from **View** in the main menu:  
   {{< figure src="/images/vscode-extensions.png" >}}

**Note.** In case of a merge conflict, merge your changes and use:

    git add .
    git commit -m "fix merge issue"
    git push