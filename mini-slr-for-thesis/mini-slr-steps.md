---
title: "Mini SLR guide for master's thesis"
---

# Systematic Review

This document outlines the steps to conduct a (mini) systematic literature review (SLR) as part of a master's thesis. A full systematic literature review is not undertaken due to its notorious laboriousness. As a result, several steps have been adapted to make the process more manageable.

In addition to the mini SLR, you will explore current trends related to your topic, formulate your research questions and method, and assess whether the existing literature provides any datasets or instruments that you could utilize in your master's thesis. A successful master's thesis should also encompass an empirical and/or constructive component.

## Task 1 - Topic Selection

### Step 1: Select a Software Engineering Topic 

Choose a software engineering topic to investigate.

### Step 2: Research 

Study some current topics in software engineering and determine how your chosen topic compares among them. It's good to understand your topic's history and its popularity. It is acceptable to iterate between Steps 2 and 3 until a topic is chosen. You can also investigate and present multiple topics. To research your topic, it is suggested to use multiple tools as listed below:

i. [Google Trends](https://trends.google.com/trends/explore?date=all&q=java,python) - In Google Trends, it's best to view topics over years rather than days or hours.

ii. [Stackoverflow trends](https://insights.stackoverflow.com/trends?tags=java%2Cpython) allow comparisons similar to Google Trends but focus on software-specific topics.

iii. [Scopus](https://www.scopus.com/search/form.uri?display=basic#basic) is an academic database. Access to Scopus may require a VPN or may only be available from the university network. Compare the paper counts per year for your topic against some other topics. [See the example of how to find paper counts](Scopus_paper_counts.png).

iv. Ask a large language model like [ChatGPT](https://chat.openai.com/) to compare your topic to alternative topics. Try to get it to make a judgment call and present similarities and differences between topics.

### Step 3: Keywords

Think about initial keywords that would be beneficial for researching your topic further.

### Step 4: Research Questions

Consider what your research questions are that you intend to investigate.

### Step 5: Write a Report

Compose a report about the chosen topic, which should encompass the following sections:

a. **Topic Description** - Define the topic you aim to investigate.

b. **Motivation** - Elaborate on why you or your employer find this topic significant. Why is the topic important in a broader context?

c. **Research** - Collect data and screenshots from the mentioned sources and tools: Google Trends, Stackoverflow trends, Scopus, and ChatGPT.

d. **Search Terms** - Introduce an initial list of Search terms for literature searches.

e. **Research Questions** - Propose an initial research question. (This can also be framed as a research goal or research problem.)


## Task 2 Define key words and initial search results

### Step 1: Learn About Different Literature Review Methods

Familiarize yourself with various methods for analyzing academic literature by watching these videos. The combined runtime is approximately 35 minutes: [Video Playlist](https://youtube.com/playlist?list=PLTUjKYPvVhe6t9pRm0PQDD6xMxUXjX9vP).

### Step 2: Define Search Terms 

What are your search terms? Think of all the synonyms you can imagine. Utilize a synonym engine, such as [Thesaurus.com](https://www.thesaurus.com/). Examine the related search suggestions on Google and Google Scholar. Consult ChatGPT. Identifying all possible synonyms can be challenging. Despite the availability of these tools, seeking advice from an expert is beneficial. For instance, while "testing" might synonymize with "sampling," "software sampling" does not synonymize with "software testing."

### Step 3: Refine Search Terms Based on Search Results

Do test searches and ensure your synonyms make sense. [This search finds papers with the search term "continuous integration"](Scopus_Irrelevant_paper.png). However, we can see it includes papers we should exclude as they are not about continuous integration related to software development. Exclusion can be done by adding more inclusion search terms, adding exclusion search terms, and including or excluding subject areas. [See the figure for more details](Scopus_Irrelevant_paper.png).

A search string consists of search terms, the fields where these terms are applied, and the Boolean operators connecting these terms. For example, the search string 

`TITLE-ABS-KEY ("continuous integration") AND TITLE-ABS-KEY ("software testing")` 

has:

a) two search terms: "continuous integration" and "software testing",

b) the terms are applied to the fields of title, abstract, and keywords (represented by TITLE-ABS-KEY), and

c) the terms are connected with the Boolean operator AND.


### Step 4: Conduct Initial Searches and Analyze Selected Papers

Review and discuss the top 5 papers as ranked by Google Scholar. Google Scholar ranks papers based on relevance, usually yielding accurate results. While Scopus offers more accurate search string speficition, its relevance-based rankings might not be as effective as those from Google Scholar.

Do the paper help you identify new search terms? 

Do the papers help you to improve your research questions?

Do the papers have similar methodology that you plan to use?

Do the papers have any data collection, processing or analysing instruments you could use, e.g. survey forms, interview questions, source code for data processing, algorithms.

Do the papers utilize any open data sets you could also analyze?

### Step 5: Write a Report

Compose a report with the following sections:

i.) **Benefits of SLR** - Discuss the advantages of a systematic literature review and explain why it's crucial to clearly define your search terms.

ii.) **Final Search String** - Report the final search string.

iii.) **Evolution of the Search String** - Detail the actions taken to derive the final search string. Describe the initial search string and specify which terms were added or removed during its refinement.

iv.) **Number of Papers Found** - Indicate the number of papers found in Scopus.

v.) **Five Relevant Papers** - Share insights gained from the five most pertinent papers.

vi.) **Initial Research Framework** - State your research questions, outline the research method you intend to adopt, and describe the data or data collection instruments you plan to use or collect.


## Task 3 Search results & Initial Include and Exclude criteria

### Step 1 - Finalize Search Strings and Assess Number of Papers Found

How many papers does your search string yield in Scopus? If the number of papers exceeds 400 or is fewer than 20, revert to steps 3 and 4 to refine your search strings. 

The upper boundary (≤400) is established to manage the effort required in the subsequent step, wherein each paper will be evaluated with respect to include/exclude criteria. This  involves reading the paper title, abstract, and essential sections to make inclusion/exclusion decisions. Assuming it takes approximately 5 minutes to evaluate a single paper, it will require 33 hours merely to evaluate the papers.

The lower boundary (≥20) ensures the presence of ample evidence. If, after reassessing the search strings, fewer than 20 papers are identified, you should broaden your search to encompass grey literature. In such a case, consider undertaking a (mini) [Multivocal Literature Review](https://www.sciencedirect.com/science/article/pii/S0950584918301939) ([non-paywalled version](https://arxiv.org/abs/1707.02553)).


### Step 2: Search Statistics
Within Scopus, click [analyze results](Scopus_analyze_papers.png). Report on the following:

- Documents per year
- Author
- Affiliation
- Country
- Document type
- Subject area

Include screenshots to support your findings and provide a brief description or commentary for each item.


### Step 3: Applying Inclusion and Exclusion Criteria

Develop your preliminary criteria for inclusion and exclusion. For guidance, refer to [this timestamped link for a refresher video about inclusion and exclusion criteria](https://youtu.be/kXsWuYXd_j8?t=536).

Apply these criteria to 10 selected papers by reading the paper titles, abstracts, keywords, and by performing full-text skimming. Based on the results, consider if there's a need to modify your criteria.

Once you've established the initial criteria, reflect on whether there's an opportunity to refine your search string. If any paper attribute can be automatically filtered, it's best to do so in the search string rather than during the manual inclusion/exclusion process. This can reduce manual labor. For instance, Criteria 1: "The paper must contain empirical evidence" is ambiguous and challenging to translate into a precise search string. However, Criteria 2: "The paper must provide evidence from a controlled experiment" can be specified as a search criterion by appending "... AND TITLE-ABS-KEY(Experiment)" to the search string.

Also consider: 
Do the papers help you to improve your research questions?

Do the papers have similar methodology that you plan to use?

Do the papers have any data collection, processing or analysing instruments you could use, e.g. survey forms, interview questions, source code for data processing, algorithms.

Do the papers utilize any open data sets you could also analyze?

### Step 4: Write a Report

Compose a report with the following sections:

i.) **Final Search String and Number of Papers Found**  
Explain the modifications you made to the search strings and how many papers they produced. Include a screenshot from Scopus with accompanying text.

ii.) **Initial Inclusion and Exclusion Criteria**  
Explain your inclusion and exclusion criteria. Did you find any opportunities to refine the search string? What were your experiences in applying the criteria.  Report the assessment outcomes for all 10 papers in a table format, as illustrated below:

![Include / Exclude  outcomes illustration](include_exclude_table.png)

iii.) **Research Framework**  
Report any changes made to the research framework: research questions, research methods, and the data or data collection instruments you plan to use or collect.


## Task 4 - Results of Include/Exclude Criteria and Initial Findings

In this task, you will report your final inclusion and exclusion criteria and the results of applying them. You will also report the initial findings from the papers.

### Step 1: Export Papers and Apply Inclusion/Exclusion Criteria
1) Using Scopus, export all papers (before exporting, select all papers, then click "export"). Please see the suggested fields to export [to a CSV file](What_fields_to_export.png). Add your inclusion/exclusion criteria to this CSV file. Read through all titles and abstracts, and do full-text skimming if needed. Provide a report table with the following format. You can use Microsoft Excel, Google Sheets, or any other spreadsheet program.
![Include/Exclude Outcomes Illustration](include_exclude_table.png)

### Step 2: Initial Findings
2) Start by reading five of your papers (full text). Sketch an initial presentation of your findings. Typically, this could be in the form of [mapping](https://www.youtube.com/watch?v=dS6AfLes1GI&t=404s), an [evidence table](https://www.youtube.com/watch?v=dS6AfLes1GI&t=601s), or even a [meta-analysis](https://www.youtube.com/watch?v=dS6AfLes1GI&t=776s). The links point to the timestamps in the video where these methods are introduced. Full references for the papers discussed in the videos are listed below:

a) **Mapping**: Engström E, Runeson P. "Software product line testing–a systematic mapping study." Information and Software Technology. 2011 Jan 1;53(1):2-13. [Link to the paper](https://www.sciencedirect.com/science/article/pii/S0950584910001709#f0010)

b) **Evidence Table**: Kuutila M, Mäntylä M, Farooq U, Claes M. "Time pressure in software engineering: A systematic review." Information and Software Technology. 2020 May 1;121:106257. [Link to the paper](https://www.sciencedirect.com/science/article/pii/S0950584920300045#tbl0009)

c) **Meta-analysis**: Hannay JE, Dybå T, Arisholm E, Sjøberg DI. "The effectiveness of pair programming: A meta-analysis." Information and Software Technology. 2009 Jul 1;51(7):1110-22. [Link to the paper](https://www.sciencedirect.com/science/article/pii/S0950584909000123#fig1)


### Step 3: Research Framework  
Do the papers help you to improve your research questions?

Do the papers have similar methodology that you plan to use?

Do the papers have any data collection, processing or analysing instruments you could use, e.g. survey forms, interview questions, source code for data processing, algorithms?

Do the papers utilize any open data sets you could also analyze?

### Step 4: Write a Report

Compose a report with the following sections:

i.) **Final Search String and Number of Papers Found**  
Report the assessment outcomes for all papers in a table format, as illustrated below:
![Include/Exclude Outcomes Illustration](include_exclude_table.png)

ii.) **Initial Findings**  
Sketch an initial presentation of your findings. This could be in the form of [mapping](https://www.youtube.com/watch?v=dS6AfLes1GI&t=404s), an [evidence table](https://www.youtube.com/watch?v=dS6AfLes1GI&t=601s), or even a [meta-analysis](https://www.youtube.com/watch?v=dS6AfLes1GI&t=776s).

iii.) **Research Framework**  
Report any changes made to the research framework, research questions, research methods, and the data or data collection instruments you plan to use or collect.

<!-- TODO: TOOLS for meta-analysis from email -->


## Task 5 - Final mini Systematic Literature Review

### Step 1: Report the high level findings 
This could be in the form of [mapping](https://www.youtube.com/watch?v=dS6AfLes1GI&t=404s), an [evidence table](https://www.youtube.com/watch?v=dS6AfLes1GI&t=601s), or even a [meta-analysis](https://www.youtube.com/watch?v=dS6AfLes1GI&t=776s). The links point to the timestamps in the video where these methods are introduced. Full references for the papers discussed in the videos are listed below:

a) **Mapping**: Engström E, Runeson P. "Software product line testing–a systematic mapping study." Information and Software Technology. 2011 Jan 1;53(1):2-13. [Link to the paper](https://www.sciencedirect.com/science/article/pii/S0950584910001709#f0010)

b) **Evidence Table**: Kuutila M, Mäntylä M, Farooq U, Claes M. "Time pressure in software engineering: A systematic review." Information and Software Technology. 2020 May 1;121:106257. [Link to the paper](https://www.sciencedirect.com/science/article/pii/S0950584920300045#tbl0009)

c) **Meta-analysis**: Hannay JE, Dybå T, Arisholm E, Sjøberg DI. "The effectiveness of pair programming: A meta-analysis." Information and Software Technology. 2009 Jul 1;51(7):1110-22. [Link to the paper](https://www.sciencedirect.com/science/article/pii/S0950584909000123#fig1)

### Step 2: Report More Detailed Findings

- Explain the main figure or table you created in Step 1 in detail.

- Use additional tables or figures to present more intricate findings.

- Summarize the evidence and main contributions. What have we learned about the topic you investigated? Note: Evidence should be of an empirical nature, while a tool would only be considered a contribution if no evidence is presented.

- Summarize the research methods employed in the existing literature.

- Summarize the datasets and data collection instruments used in the existing literature. Are there any datasets or instruments you could utilize?

- Identify and summarize the research gaps. What remains unknown about the topic?

### Step 3: Write a Report
Include contents of Steps 1 and 2. 

## Master's Thesis Considerations
The reports you've produced in Tasks 1 - 5 should be incorporated into your Master's thesis. However, it's not necessary to include every detail. Consider using a refined version of the reports for your thesis.
