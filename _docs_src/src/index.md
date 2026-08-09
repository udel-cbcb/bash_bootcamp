# Bash & Command Line Bootcamp

Welcome to the Bash & Command Line Bootcamp!  This hands-on tutorial is beginner friendly and will walk you through the basics of using a Unix-like command line and the language Bash.

## What is Bash?  What's a Command Line?

Briefly, Bash is a ubiquitous [Unix](https://en.wikipedia.org/wiki/Unix) shell and command language that allows a user to interact with a computer using text commands rather thatn graphical user interfaces (GUIs).  If these concepts are new to you, we recommend reading [this blog post](https://www.tenderisthebyte.com/blog/2019/12/15/beginning-bioinformatics-command-line-terminal/) before moving on to the tutorial.

While GUIs can be highly useful, and are sometimes the best tool, they are more often than not outpaced by command line utilities for modern datasets.  Here are some of the reasons that command line skills are highly valuable for a scientist or researcher:

- **Expanded toolset:** Many, and perhaps even most, specialized scientific software tools are bult strictly as command-line utilities.  Learning Bash enables researchers to use those tools.
- **High-performance computing (HPC) and cloud computing:**. Many modern datasets are simply too big to store or analyze on an average (or even advanced) personal device.  In these cases, researchers must turn to high-performance computing options such as clusters and cloud computing to analyze and store data.  For example, command line skills are necessary to utilize computational infrastructure like [Biomix](https://bioinformatics.udel.edu/core/hpc/) is the University of Delaware's High Performance Computing (HPC) cluster for life sciences research.
- **Scalability and autmoation:** Processing five data files by hand in Excel is doable; processing five thousand is potentially impossible.  Bash enables automated processing of complex tasks, helping to save time and eliminate some aspects of human error.
- **Processing speed:** There are some tools that are available as GUIS and as command-line utilities.  In virutally all cases, the command line version will be significantly faster.  Take [BLAST](https://blast.ncbi.nlm.nih.gov/Blast.cgi), for example, which is perhaps the single most famous piece of bioinformatics software.  BLAST is used to identify similar nucleotide and/or amino acid sequences.  The same search that would take several minutes in the web interface womightuld take fractions of a second on the command line.

This walk-through will equip you with all the skills needed to get started with data analysis.

# Table of Cotents

- **Hands-On Bootcamp**
    - [Setup](Setup_Bash.md)
    - [Navigating the File](System: 1-Intro_Navigate_Filesystem.md)
    - [Working with Files](2-Working_with_Files.md)
    - [Working with Scripts](3-Working_with_Sripts.md)

- **Additional Resources**
    - [Bash Cheat Sheet](Commands_Vocab.md)
    - [Troubleshooting Tips](Troubleshooting_Tips.md)

## License

Copyright (c) 2026 Amelia O. Harrison

This documentation is licensed under a <a rel="license" href="https://opensource.org/license/mit">MIT License.
