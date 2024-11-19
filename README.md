# Histology Specimen Time Outstanding

## 1. Introduction

The Histology Laboratory faces a notable challenge with the absence of visual performance insights. To address this, the dashboard (created using tableau) provides a comprehensive visual representation covering various specimen types for easy evaluation. It offers a quick overview for management and assists employees in identifying areas for efficiency improvements and delayed specimens. This dashboard presents a snapshot of outstanding specimen time, detailed insights into specimen types and processing times, and highlights areas needing attention. 

Design is critical, balancing key information with a clean, uncluttered appearance and interactive elements for deeper exploration (Malnik, 2022). 

[For specific laboratory terms](insert_link)

## 1.1. Objectives

The objective of this dashboard is to provide a real-time, practical snapshot of the laboratory's status. It should be understandable and valuable to personnel at all levels within the laboratory.

---

This guide aims to illustrate the various interactive functionalities present within the dashboard. Figure 1 offers a comprehensive overview of the dashboard, showcasing interactive elements within each graph, including highlighting and filtering options. These interactive elements are interconnected, meaning that modifying one graph through filtering will trigger corresponding changes in the other graphs to accurately depict the adjustment. Please see the document “Design Principles” for a glossary to clarify any terms used in this document.

**Figure 1**: Dashboard of the Specimens outstanding in histology on the 10/09/2023.

### 1. Trend graph: Timeline of specimen’s Time Outstanding
**Feature 1**: Upon clicking the trendline, it will display the date the specimen was collected, the current date and time, and the time outstanding (the total number of days a specimen has not been authorised).

**Figure 2**: The timeline of the specimen’s Time Outstanding. The dates shown in the figure are those selected by the user. The average line demonstrates the average value of all time outstanding across this specific time period.

**Feature 2**: A specific day of interest can be selected, which will in turn affect the rest of the dashboard (Figure 3). For example, the textual information at the bottom of the page changed to demonstrate that the total count of outstanding specimens taken specifically on that date is 34.

**Figure 3**: Changes occurring to the rest of the Dashboard following interaction in the timeline graph.

### 2. Histogram: Distribution of time outstanding for all specimens.
**Feature 1**: Selecting a bin in the graph will highlight information from that specific bin and also result in changes across the rest of the dashboard to reflect this selection.

**Feature 2**: Upon selecting a specific bin, a drill-down option will appear (“Drill down distribution”). Selecting this will lead to a table demonstrating all cases that are outstanding for that specific bin selected (Figure 5).

**Figure 4**: Distribution of time outstanding for all specimens.

**Figure 5**: Table of specimens that are outstanding for more than 20 days.

### 3. Textual data: Textual information on days spent at each stage.
This is the only part of the dashboard that does not have interactive features. However, the information demonstrated in **Figure 6** updates depending on the selections made in the other graphs on the dashboard. Currently, it is demonstrating that 2303 specimens are outstanding.

**Figure 6**: This is a brief overview of the number of days specimens are spending on average at each stage.

### 4. Stacked bar chart: Comparison of Urgent and Routine specimens.
**Feature 1**: Hovering the cursor over the bins will emphasize the selected value, and a numeric value will emerge, conveying the information outlined in the legend (see Figure 7).

**Feature 2**: Selecting any part of the bins will result in changes across the Dashboard, reflecting information based on this selection (Figure 8).

**Figure 7**: Comparison of routine and urgent specimens at each stage.

**Figure 8**: Dashboard with results from the selection in Figure 7. The urgent bin was selected, hence resulting in the demonstration of information relating to the urgent specimen.

### 5. Histogram: Time Outstanding of different specimen types.
**Feature 1**: Selecting a bin will result in its highlighting. Changes will also occur across the Dashboard to reflect the selection (Figure 9).

**Figure 9**: Histogram demonstrating the different specimen types and their average overall outstanding time.

**Feature 2**: Two drill-down options will appear: “Drill Down Patient” and “Drill Down Specimen” (Figure 9). They will lead the user to tables demonstrating the specimen sub-speciality (Figure 10) and patient lab numbers (Figure 11), respectively.

**Figure 10**: Demonstrates all the sub-specialties of the “Routine Histology” specimen selected in Figure 9. On the right-hand side is the average number of days each specimen sub-specialty is outstanding. For example, ANALP specimens are on average outstanding for 41.5 days.

**Figure 11**: A table demonstrating different patients, reflected in their lab numbers, and their total time outstanding (days) for the select specimen type group.
