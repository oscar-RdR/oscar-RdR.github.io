## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/oscar-RdR/oscar-RdR.github.io/edit/main/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/oscar-RdR/oscar-RdR.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.




<html>
  <head>
    <script type="text/javascript" src="https://www.gstatic.com/charts/loader.js"></script>
    <script type="text/javascript">
      google.charts.load("current", {packages:["calendar"]});
      google.charts.setOnLoadCallback(drawChart);

   function drawChart() {
       var dataTable = new google.visualization.DataTable();
       dataTable.addColumn({ type: 'date', id: 'Date' });
       dataTable.addColumn({ type: 'number', id: 'Won/Loss' });
       dataTable.addRows([
[new Date( 2017 , 10 , 02 ), 77],
[new Date( 2017 , 10 , 03 ), 119],
[new Date( 2017 , 10 , 04 ), 85],
[new Date( 2017 , 10 , 05 ), 94],
[new Date( 2017 , 10 , 06 ), 105],
[new Date( 2017 , 10 , 07 ), 123],
[new Date( 2017 , 10 , 09 ), 24],
[new Date( 2017 , 10 , 13 ), 100],
[new Date( 2017 , 10 , 14 ), 143],
[new Date( 2017 , 10 , 15 ), 103],
[new Date( 2017 , 10 , 16 ), 124],
[new Date( 2017 , 10 , 17 ), 161],
[new Date( 2017 , 10 , 20 ), 104],
[new Date( 2017 , 10 , 21 ), 211],
[new Date( 2017 , 10 , 22 ), 182],
[new Date( 2017 , 10 , 23 ), 197],
[new Date( 2017 , 10 , 24 ), 162],
[new Date( 2017 , 10 , 25 ), 128],
[new Date( 2017 , 10 , 26 ), 99],
[new Date( 2017 , 10 , 27 ), 162],
[new Date( 2017 , 10 , 28 ), 174],
[new Date( 2017 , 10 , 29 ), 178],
[new Date( 2017 , 10 , 30 ), 235],
[new Date( 2017 , 11 , 01 ), 129],
[new Date( 2017 , 11 , 02 ), 104],
[new Date( 2017 , 11 , 03 ), 106],
[new Date( 2017 , 11 , 04 ), 114],
[new Date( 2017 , 11 , 05 ), 133],
[new Date( 2017 , 11 , 06 ), 83],
[new Date( 2017 , 11 , 12 ), 208],
[new Date( 2017 , 11 , 13 ), 264],
[new Date( 2017 , 11 , 14 ), 347],
[new Date( 2017 , 11 , 15 ), 236],
[new Date( 2017 , 11 , 16 ), 93],
[new Date( 2017 , 11 , 17 ), 102],
[new Date( 2017 , 11 , 18 ), 212],
[new Date( 2017 , 11 , 19 ), 232],
[new Date( 2017 , 11 , 21 ), 73],
[new Date( 2017 , 11 , 22 ), 172],
[new Date( 2017 , 11 , 23 ), 95],
[new Date( 2017 , 11 , 24 ), 95],
[new Date( 2017 , 11 , 25 ), 76],
[new Date( 2017 , 11 , 26 ), 132],
[new Date( 2017 , 11 , 27 ), 120],
[new Date( 2017 , 11 , 28 ), 107],
[new Date( 2017 , 11 , 29 ), 121],
[new Date( 2017 , 11 , 30 ), 95],
[new Date( 2017 , 11 , 31 ), 57],
[new Date( 2017 , 9 , 25 ), 158],
[new Date( 2017 , 9 , 26 ), 124],
[new Date( 2017 , 9 , 27 ), 95],
[new Date( 2017 , 9 , 28 ), 8],
[new Date( 2017 , 9 , 30 ), 127],
[new Date( 2017 , 9 , 31 ), 63],
[new Date( 2018 , 0 , 01 ), 73],
[new Date( 2018 , 0 , 02 ), 115],
[new Date( 2018 , 0 , 03 ), 196],
[new Date( 2018 , 0 , 04 ), 181],
[new Date( 2018 , 0 , 05 ), 8],
[new Date( 2018 , 0 , 08 ), 123],
]);

       var chart = new google.visualization.Calendar(document.getElementById('calendar_basic'));

       var options = {
         title: "Number of tweets",
         height: 350,
         calendar: { cellSize: 10 }
       };

       chart.draw(dataTable, options);
   }
    </script>
  </head>
  <body>
    <div id="calendar_basic" style="width: 500px; height: 350px;"></div>
  </body>
</html>
