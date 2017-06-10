---
layout: post
title:  "Creating documents efficiently with markdown"
date:   2017-06-10
categories: markdown productivity document publishing
---
<script src="https://unpkg.com/mermaid@7.0.3/dist/mermaid.min.js"></script>

## What is markdown

We always have a need to create documents, whether to create simple memos, checklists, todos or even writing tutorials, product documentation or academic papers. Nowadays, we have multiple softwares like wordprocessors, typsetters like latex allowing us to do those tasks but my favorite is by using markdown.

Markdown is a simple and efficient way to write documents using simple and quick syntax. The structure of a document created with markdown is created on using text. It's not a new thing as Latex allows to do the same. However the main advantage of using markdown is it's simple and quick syntax. For more precise and complex documents, latex could be the best choice and already have mature packages covering graphics and a lot of types of content.

For example to create an article with a title (h1), subtitle(h2) and text, the following syntax could be used: 
```
# This is my title

## This is my subtitle

This is my content

And below is a table : 

|Column1|Column2|
|-------|-------|
|data1|data2|
```

More details about common markdown syntax can be found on [Daring Fireball website](https://daringfireball.net/projects/markdown/syntax) and [Markdown tutorial](http://www.markdowntutorial.com/).

## Useful markdown and markdown-likes

Many kinds of markdowns exists, giving possibilities to create textual and graphical content.

Some of the most commons are 
- [GitHub Flavored Markdown](https://help.github.com/articles/about-writing-and-formatting-on-github/) - Used for GitHub README.md and project documentation.
- [Gitbook](https://www.gitbook.com/) - One the the best tool out there to create and share documents ! 
- [mermaid](https://knsv.github.io/mermaid/) - For flowcharts, gantt, sequence diagram and more
- [plantUML](http://plantuml.com/) - UML and non UML diagrams such as gantt and sequence diagrams.
- [Graphviz](http://www.graphviz.org/) - Most focused on graphs

## Rendering markdown ? 

As markdown is simply just text defining structure and content. We still need a way to render those documents.

For that we have a lot of tools that allows editing, exporting and sometimes live previews of the documents.

Some of my favorites
- [Zim](http://zim-wiki.org/manual/Start.html) - Seems to not be evolving.
- [Typora](https://typora.io/) - Simple and efficient supporting mermaid and other markdowns.
- [pandoc](http://pandoc.org/) - Multi markdown conversion. Can even generate slides for your markdown using beamer or HTML interactive slides. 
- [Jekyll]() - Static website generator focusing on blogs. I'm using it for this blog ! 
- Online services
  - [dillinger](http://dillinger.io/) - Can link to cloud drives and export to PDF
  - [gravizo](http://www.gravizo.com/) - Supports mutli markdown and sharing.
  - [stackedit](https://stackedit.io/editor) - Yet another online editor which can push to github and other sites.

## Rendering some mermaid diagrams

<div class="mermaid">
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->E;
</div>
