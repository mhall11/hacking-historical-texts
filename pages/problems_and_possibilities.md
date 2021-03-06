# Problems and Possibilities
---

<figure>
    <p>
        <a href="{{site.baseurl}}/index.html">Home</a> |
        <a href="{{site.baseurl}}/pages/background.html">Background</a> |
        <a href="{{site.baseurl}}/pages/initial_findings.html">Initial Findings</a> |
        <a href="{{site.baseurl}}/pages/problems_and_possibilities.html">Problems and Possibilities</a> |
        <a href="{{site.baseurl}}/pages/source_analysis.html">Source Analysis</a> |
        <a href="{{site.baseurl}}/pages/workflow.html">Workflow</a>
        <a href="{{site.baseurl}}/pages/bibliography.html">Bibliography and Credits</a>
    </p>
</figure>
---

### Roadblocks:
- Scraping the Glasnevin PDF
  - The PDF provided by the Glasnevin Trust, which contains the names of 485 people who died during the Easter Rising with the ability to add more as they are given the data, was hard to properly scrap and turn into a CSV/Excel file to run through Tableau. We worked with Professor Thomas to find a good program to turn the PDF file into a workable TXT file and ended up using the program Xpdfreader and the EXE tool provided by the company to scrape pdfs and turn them into just the text of the PDF. At first, this seemed to be good enough to run through a code which Professor Thomas created for us to turn the TXT into a workable CSV, but because the records held within the PDF weren't complete and left blank lines which the xpdfreader EXE would not read properly and combine multiple lines. This led to the original code returning errors and not being able to turn the TXT into CSV. Professor Thomas augmented his code to properly turn the TXT into CSV which could then be used for the creation of the Tableau sheet showing the affiliation of those who died during the Easter Rising.


- Getting mapping to work in Tableau
  - After reorganizing the information through Openrefine, the dataset was now ready to use in creating the visualization part of our project. Tableau was used for the first attempt in creating any kind of visualization based on the dataset. When creating the map concerning the deaths of people during the Easter Rising of 1916 Tableau was lacking the proper tools. Even though we were able to upload the data, Tableau did not allow us the mapping tools necessary for the type of visualization we were trying to make. There were multiple attempts to upload Dublin map packs to Tableau to support our project but there were too many problems. After spending hours in Tableau, a more simplistic mapping tool was used in the end to make our maps.

- Transcribing literature for Analysis
  - On the outset of this project, we had planned to do a literature analysis of the speeches during the Rebellion and the speeches from the Gaelic Revival to notice similarities and differences as well to see how much the Gaelic Revival influenced the Easter Rising. The problem with this plan is that there is not a source of TXT files for the speeches and other writings and a comprehensive list of even PDFs could not be found during the scope of this class. Thus, as stated below in the possibilities, this is an area that can easily be added in at a later date, once we are able to either transcribe or find PDFs to scrap using Xpdfreader to make them able to be used in a text analysis program.


- Changed project idea because of data availability
  - Originally, this project started as a compare and contrast with the effects and outcomes of the French Revolution, the Russian Revolution, and the Cuban Revolution, but we realized that this type of a project would be far too much work for the span of time given. This led to us boiling the project to exclusively the Cuban Revolution, but without a proper question. After some time for deliberation, Lauren came up with the idea of reworking the project to look at the effects and causes of the Easter Rising, as this was a subject she knew had both digital projects already in existence and plenty of new scholarship as the Centennial was in 2016, two years prior to this project. We all agreed this would be the best plan of action as it gave as a defined position to start from and we would have someone, Lauren, who knew the topic well making the analysis portion easier to manage and correct.

### Possibilities:
- Literature Analysis
  - As an added depth to this project, we could do a literary analysis of the works inspiring the speeches and literature leading up to the Rebellion, an analysis of the works of the Rebellion, or an analysis looking at how the two are similar and different. An analysis into the speeches and literature of the Rebellion can help understand the narrative of the Irish resistance and possibly find new questions about the mentality and worldview of the Irish through their use of certain words or language.


- Better data sources
  - A bit of an odd point to touch on, but this project could benefit from a more complete data source. This would take likely a good bit of research and scraping, but the CSVs that were used for this project either lack breadth or depth (the ArcGIS CSV and the Glasnevin Trust Necrology PDF respectively). With a data source that has the breadth of the Glasnevin Trust Necrology and the depth of the ArcGIS CSV, we could do a more in-depth analysis of gender roles, class in society based on career, religion, and more that currently cannot be done even with a combination of the two sources.
