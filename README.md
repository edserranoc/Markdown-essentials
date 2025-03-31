# Markdown-essentials
🚀 Master Markdown in Minutes! A complete guide with examples, tips, and tricks.


## Introduction

Markdown is a lightweight markup language that allows you to format text easily using a plain-text editor. It is widely used in documentation, Jupyter Notebooks, GitHub repositories, and blogging platforms due to its simplicity and readability.

This guide will help you master Markdown with practical examples, useful tips, and tricks. You will learn how to modify Markdown cells in Jupyter Notebooks to create well-structured and visually appealing documents.

Whether you are a beginner or looking to enhance your Markdown skills, this tutorial will provide everything you need to make your content stand out. 

> [!NOTE]
> ⭐ **If you find this repository helpful, consider giving it a star!** It helps others discover the project and motivates further improvements. :frog::dog:✨


## Markdown for Jupyter Notebooks

Jupyter Notebooks support Markdown cells, allowing users to add formatted text, images, equations, and more to enhance documentation within notebooks. This feature is particularly useful for creating well-structured reports, tutorials, and interactive documents.

> [!IMPORTANT]
> All content related to formatting Markdown in Jupyter Notebooks is available in the following notebook: 🔗 [Markdown Formatting in Jupyter Notebooks](https://github.com/edserranoc/Markdown-essentials/blob/main/Markdown%20Formatting%20in%20Jupyter%20Notebooks.ipynb). Download the file and open the cells to see the syntax.


### Basic Level Content

- Text Formating
    - Strikethrough
    - Color Font
    - Highlighting Text
- Tex Formulas
- Embedding Code in Markdown
- Header Formatting
    - Hierarchy
    - Alignment
    - Color
- Creating List
    - Ordered Lists
    - Unordered Lists
    - Table of Contents

**Examples:**

<style>
ss { color: #4F959D}
</style>

<ss>Highlighting Text:</ss>
- <mark>Highlighted text</mark> <br>
- <mark style="background-color: #4F959D">Highlighted text</mark> <br> 
- `Highlighted text`

<font color="#4F959D">Embedding Code in Markdown</font>
    
```python
import numpy as np

def sum(a:float,b:float)->float:
    return a+b
```

<font color="#4F959D">Tex Formulas:</font>

$$ f(\mathbf{x}) = \sum_{i=1}^{n-1} \left[100(x_{i+1} - x_i^2)^2 + (1-x_i)^2 \right],
\quad n\geq 2.$$


### Intermediate Level Content

- Check Box
- Inserting Tables
- Nested Block Quoting
- Colored Note Boxes
- Hyperlinks
- Displaying Images in Markdown
    - Insert a single image
    - Insert multiple images
    - Table with Images   

**Examples:**

<font color="#4F959D">Nested Block Quoting:</font>

> Dorothy followed her through many of the beautiful rooms in her castle.
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

<font color="#4F959D">Table with Images:</font>

<center>
<table>
<tr>
<td> <center><font size="5" color="#4F959D" >Golden Poison Frog </font></center> </td>
<td> <img src="https://www.treehugger.com/thmb/FMhCaytYSaXVh1h5ftgN_aoBeqE=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc()/GettyImages-115042394-19c9bc12e4b241ea94c4fac4130fcb8f.jpg" alt="Drawing" style="width: 200px;"/> </td>    
</tr>
<tr>
<td> <center><font size="5" color="#4F959D" > Glass Frog</font></center> </td>
<td> <img src="https://imagenes.elpais.com/resizer/v2/https%3A%2F%2Fep01.epimg.net%2Felpais%2Fimagenes%2F2017%2F05%2F29%2Fciencia%2F1496047502_788600_1496059078_noticia_fotograma.jpg?auth=ef2cf30ce01c6a9482ec147c0e8c64cbd1d607a68357b185291e0d082420b6e7&width=1960&height=1103&smart=true" alt="Drawing" style="width: 200px;"/> </td>    
</tr>
</table>
</center>

<font color="#4F959D">Check Boxes:</font>
- [x] Design
    - [ ] Stage 1
    - [x] Sub-Stage 2
- [x] Mockups
- [x] Development


## Markdown for Github Repositories

Markdown is widely used in GitHub repositories to create structured and visually appealing documentation. It is essential for writing README files, contributing guidelines, issue templates, and wikis. With Markdown, you can format text, include images, create tables and add checklists.

By mastering Markdown, you can improve the readability and professionalism of your GitHub projects.

> [!IMPORTANT]
> All content related to formatting Markdown in Github Repositories is available in the following notebook:  🔗 [Markdown Formatting for GitHub](https://github.com/edserranoc/Markdown-essentials/blob/main/Format%20-%20Markdown.md) *(Still in Progress)* Download the file and open the cells to see the syntax.

### Content 
- Markdown VSCode Extensions
  - Markdown All in One
    - Markdown Checkboxes
    - Markdown Emojis :colombia: :space_invader:
  - Markdown Preview for Github Alerts
- Future Content (still in progress)
  - Add tables with technical skills
  - Create Gif descriptions of your profile.
  - \<details\>: The Details disclosure element.


## License
This project is licensed under the Apache-2.0 icense. See the LICENSE file for details.

