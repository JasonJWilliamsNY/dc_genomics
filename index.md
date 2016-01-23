---
layout: lesson
root: .
lastupdated: January 21, 2015
contributors: ["Jon Badalamenti","Amanda Charbonneau","Shari Ellis","Chris Fields","Bob Freeman","Chris Hamm","Randall Hayes","Josh Herr","Kate Hertweck","Adina Howe","Hilmar Lapp","Michael Linderman","Andréa Matsunaga","Blaine Marchant","Sue McClatchy","Sheldon McKay","Susan Miller","Jeramia Ory","Deborah Paul","Mary Shelley","Mike Smorul","Sara Stevens","Tracy Teal","Juan Ugalde","Jason Williams","Laura Williams","Ryan Williams", "Greg Wilson"]
maintainers: ["TBD"]
domain: Genomics
topic: Skills for working with sequence data
software: Linux Shell, R
dataurl: ["","",""]
status: In-development
---

#Data Carpentry - Working with genome-scale sequence data 
<br>
<br>
**The purpose of Data Carpentry**<br>
Data Carpentry's aim is to teach researchers basic concepts, skills, and tools for working with data so that they can get more done in less time, and with less pain. 

**Purpose of these lessons**<br>
These lessons teach fundamental data management and analysis skills needed to work with genomic data. Example workflows are used to illustrate the researchers skills needed to handle files, use bioinformatics tools, and analyze their output.

**Teaching layout**<br>
Lessons are a series of modules designed for use at a two-day Data Carpentry workshop. They can also be covered by learners independently on their own - provided they follow the **Doing this on your own** setup requirements. Most lessons include work at the command line in the Unix shell (particularly the [Bash shell](https://en.wikipedia.org/wiki/Bash_%28Unix_shell%29)). We will also cover visualization of datasets in R and with some other common genome visualization tools. 

**Intended audience**<br>
We created for learners who are just starting to analyze a genomic dataset - which we define as any project that takes high-throughput (next-generation) sequence data to any number of endpoints (genome/transcriptome assembly, variant detection, RNA/ChIP-Seq, etc.). 

Lessons introduce and reinforce basic skills in the Unix shell and R, and are **designed for learners with no programming experience.** The general topics covered include:

- Organizing a computational biology project
- Understanding important file formats (FastQ, etc.)
- Evaluation and quality control of data
- Using the shell to automate, build pipelines, and explore data
- Visualization of genomics data
- Management and analysis of large data sets with high-performance and cloud computing

**Content Contributors: {{page.contributors | join: ', ' %}}**


**Lesson Maintainers: {{page.maintainers | join: ', ' %}}**


**Lesson status: {{ page.status }}**

<!--
  [Information on Lesson Status Categories]()
-->

<!-- ###### INDEX OF LESSONS ON THIS TOPIC ###### -->

## Lessons:

1. [Lesson 00 Introduction to the dataset](https://jasonjwilliamsny.github.io/datadescription-genomics/)
2. [Lesson 01 Before you download/import - Metadata and tidiness]()
3. [Lesson 02a Connecting to the cloud in 5 min or less]()
4. [Lesson 02b Connecting to the cluster in 5 min or less]()
5. [Lesson 03 Getting started with the data - Importing/Downloading]()
6. [Lesson 04 Unix Shell I - file system basics]()
7. [Lesson 05 Unix Shell II - searching files and metadata]()
8. [Lesson 06 Organizing and documenting your project - markdown]()
9. [Lesson 07 File formats I - FastQ]()
10. [Lesson 08 Quality control of sequence data - scaling with 'for' loops]()
11. [Lesson 09 Building your first shell script - automating a QC pipeline]()
12. [Lesson 10 Advanced shell script - automating and documenting your workflow]()
13. [Lesson 11 File formats II - Other common bioinformatics file formats]()
14. [Lesson 12a Visualization of genomics data I - browsers (IGV)]()
15. [Lesson 12b Visualization of genomics data I - browsers (JBrowse?)]()
16. [Lesson 13a Visualization of genomics data in R - R Shiny Apps]()

---
## R Lessons
1. [Lesson 14 Introduction to R and R-Studio]()
2. [Lesson 15 Summarizing and exploring genomics data in R - dplyr]()
3. [Lesson 16 Plotting genomics data in R - ggplot]()

## Data

Data files for the lesson are available here: 

1. SRA Dataset: [https://www.ncbi.nlm.nih.gov/bioproject/PRJNA188723](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA188723)
2. Paper [Nature]: [http://www.nature.com/nature/journal/v489/n7417/full/nature11514.html](http://www.nature.com/nature/journal/v489/n7417/full/nature11514.html)
3. Dryad Figures: [http://datadryad.org/resource/doi:10.5061/dryad.8q6n4](http://datadryad.org/resource/doi:10.5061/dryad.8q6n4)


### Requirements

Data Carpentry's teaching is hands-on. *These lessons assume no prior knowledge of the skills or tools*, but you will need to follow our setup instructions so that you can connect to a virtual server (either an computing cluster or cloud virtual machine) your instructors will provide. Pease make sure to install everything *before* working through this lesson.

<!--
{% if page.software == "Python" %}
{% include pythonSetup.html %}
{% elsif page.software == "Spreadsheets" %}
{% include spreadsheetSetup.html %}
{% elsif page.software == "R" %}
{% include rSetup.html %}
{% else %}
{% include anySetup.html %}
{% endif %}
-->

<p><strong>Twitter</strong>: @datacarpentry</p>




