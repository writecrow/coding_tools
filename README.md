# Coding Tools
Crow tools to assist human coders with coding and tag checking. We recommend you download these tools to your computer, and open each tool by click on the index.html file in each individual folder. If using the links provided below, make sure you wait a few seconds for your browser to load the CSS (i.e., style sheet).


## Subset tag Checker for the Biber Tagger

[Open Tag Checker](http://htmlpreview.github.io/?https://github.com/writecrow/coding_tools/blob/master/subset_tag_checker/index.html)

Input file: a text file tagged with the original Biber tagger (one token per line, each line contains token and Biber tag separated by space)

Output file: tab separated text file that can be opened using Excel

The tool highlights a subset of tags. Change the regular expression in the "Regular Expression for tags" field before loading a text file. The interface calculates precision for the tags selected.

![biber tagger subset tag checker](https://github.com/writecrow/coding_tools/blob/master/subset_tag_checker/subset_tag_checker_screenshot.png)

## Stanford Tag Checker

[Open Tag Checker](http://htmlpreview.github.io/?https://github.com/writecrow/coding_tools/blob/master/stanford_tag_checker/index.html)

Input file: a text file tagged with the Stanford Dependency Parser (CoNNL format, one token per line, each column separated by tab)

Output file: tab separated text file that can be opened using Excel

## Interactive De-identifying Tool

[Open Deid tool](http://htmlpreview.github.io/?https://github.com/writecrow/coding_tools/blob/master/interactive_de-identifying_tool/index.html)

This interface was designed to assist in manual de-identification of text files.  

Input file: UTF-8 encoded text file

Output file: UTF-8 encoded text file

## Crow Output Coding Tool

[Open Coding Tool](http://htmlpreview.github.io/?https://github.com/writecrow/coding_tools/blob/master/Crow%20Output%20Coding%20Tool/index.html)

Input files: csv files exported (i.e., downloaded) from Crow online platform.

Output file: tab separated text file that can be opened using Excel


## That tag Checker
[Open Tag Checker](http://htmlpreview.github.io/?https://github.com/writecrow/coding_tools/blob/master/that_tag_checker/index.html)

Input files: text files tagged with Biber tagger (one token per line, each line contains token and Biber tag separated by space)

Output file: tab separated text file that can be opened using Excel

The tool highlights all "that" tags (every tag that contains that, omitted or not) and lists all possible that tags, in case the human tag checker needs to change that tag. Multiple text files can be loaded at once.

![alt text](https://github.com/writecrow/coding_tools/blob/master/that_tag_checker/screenshot.png)

## Citation Coder
[Open Citation Coder](http://htmlpreview.github.io/?https://github.com/writecrow/coding_tools/blob/master/citation_coder/index.html)

Input files: plain text files with optional metadata (i.e., all information between angled brackets: <metadata>)
  
Output file: tab separated text file that can be opened using Excel
  
The tool separates the texts into individual sentence. Each sentence can be coded as containing a reference to an external source. Then, if that is the case, it can be codes as Integral, Non-Integral, or Hybrid. References can also be tagged

![alt text](https://github.com/writecrow/coding_tools/blob/master/citation_coder/screenshot_citationcoder.png)
