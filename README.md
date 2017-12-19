# Coding Tools
Crow tools to assist human coders with coding and tag checking.

## That tag Checker
Input files: text files tagged with Biber tagger (one token per line, each line contains token and Biber tag separated by tab)
Output file: tab separated text file that can be opened using Excel

The tool highlights all "that" tags (every tag that contains that, omitted or not) and lists all possible that tags, in case the huma tag checker needs to change that tag. Multiple text files can be loaded at once.

## Citation Coder
Input files: plain text files with optional metadata (i.e., all information between angle brackets: <metadata>)
Output file: tab separated text file that can be opened using Excel
  
The tool separates the texts into individual sentence. Each sentence can be coded as containing a reference to an external source. Then, if that is the case, it can be codes as Integral, Non-Integral, or Hybrid. References can also be tagged
