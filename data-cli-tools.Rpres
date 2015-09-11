Command-line Tools for Data Analysis
========================================================
author: Matt Pettis
date: 2015-09-14


Motivation: Why care about command line tools at all?
========================================================
incremental: true

- Data aquisition, transformation, and cleaning are often cited as taking the bulk of data analysis time.
- Availability of tools vary widely.  Tools you may like may not run where you need them to.
- Command-line tools (CLI) are often composable into pipelines.
- Often, data ETL needs to be scriptable, with different but analagous datasets.
- Analysis also often needs to be scriptable, for auditablility and reproducibility.


Common examples where CLI is helpful 
========================================================
incremental: true

- You are given a large number of small CSV files with identical tabular structure, and you want to combine them into one file.
- Your data is stored in XML/JSON/CSV/a database, and you need to get it into XML/JSON/CSV/a database.
- You have XML/JSON/CSV, and it has a regular table-like structure that would be easy to work with if you could issue SQL-like commands against it as if it were a SQL database.
- You are confined to a stty-type terminal where the data resides, and you'd just like to look at it in a readable format (like an Excel-like table).


What are good command-line tools for data, and where can you find them?
========================================================
incremental: true

- Most Linux/Unix builds come with standard tools like *grep*, *sed*, *awk*, *perl*, *python*, and a host of other utilities.
- Jeroen Janssens wrote a hugely popular blog post listing [7 command-line tools for data science](http://jeroenjanssens.com/2013/09/19/seven-command-line-tools-for-data-science.html) that list out some very popular tools, examples of their use, and where to get them.  He also wrote a nice book about the topic: [Data Science at the Command Line](http://datascienceatthecommandline.com/).


Overview of some of the tools
========================================================
incremental: true

- Bash tools *grep*, *sed*, *awk*, *perl*, *python* already mentioned, could take up days about how to use them.
- [csvkit](http://csvkit.readthedocs.org/en/latest/).  Tools centered on CSV files.  How to take in from many formats to CSV (sql databased, json, Excel workbooks), and export from CSV to different formats.  How to view, filter, and validate CSV files.  How to treat CSV files like SQL tables.
    - I gave a [talk](https://github.com/mpettis/csvkit_talk) on it at a local data conference that is a more expansive tutorial on most of the tools.  You can download it at that previous link.
- [jq](https://stedolan.github.io/jq/).  Processing JSON with a XPATH like syntax.  Handy for large transformations or extractions from JSON.


Overview of some of the tools
========================================================
incremental: true

- [Rio](https://github.com/jeroenjanssens/data-science-at-the-command-line/blob/master/tools/Rio). Makes assumptions about format of data flowing into a command prompt stdin and allows you to issue R commands and outputs against it to leverage R to mutate data.
- [xmlstarlet](http://xmlstar.sourceforge.net/).  XPATH functionality and much more against XML input.  Also does formatting and other nice things.  Sadly, development has stalled, but still works.


Overview of some of the tools
========================================================
incremental: true

- [ora2out](https://github.com/mpettis/ora2out).
A tool I built mainly for my own purposes (read: needs better documentation and API considerations).  But is what I use to script dumps of Oracle SQL queries right to CSV (or XML) output on the command line.
Very nice when I don't want to fire up SQLDeveloper or some such when I have a simple query to run.  Or when I have a longer-running query that I want output from but don't want to tie up SQLDeveloper.


Conclusion
========================================================
incremental: true

- I really wrote this up as as reference and resource for great command line tools, and hopefully to share with others.
- Mastering command-line tools can really increase your efficiency with many data analysis tasks.  This allows you to get to the actual modeling of data much faster.


Questions?
========================================================

... and thank you!

Location of this presentation:

https://github.com/mpettis/data-cli-tools
