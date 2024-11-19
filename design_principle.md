# Design Principles Overview: A User-Friendly Dashboard for Specimen Tracking  

## 2.1 User Identification  
The primary users of this dashboard are **managerial staff**, though its design ensures accessibility and usability for all laboratory employees. This inclusive approach influenced choices in layout, structure, and data visualization, catering to diverse user needs.  

## 2.2 Data Selection  
Selecting relevant data was critical to ensuring the dashboard served its purpose effectively. The chosen metrics include:  
- **Time Outstanding**: Tracks the average time a specimen remains outstanding to monitor lab progress.  
- **Distribution of Outstanding Times**: Highlights the common timeframes for delayed specimens.  
- **Urgent vs. Routine Specimens**: Provides insight into varying processing times, enabling informed prioritization.  

Time outstanding was chosen as the key performance indicator (KPI) to pinpoint areas requiring improvement and enhance overall efficiency. Detailed analysis of specimen types and sub-specialities helps address challenges such as staffing levels, ultimately reducing turnaround times and improving service.  

## 2.3 Layout/Data Hierarchy  
The dashboard’s layout was refined to prioritize simplicity and ease of use. Key considerations included:  
- **Textual Data at the Top**: Aligning with the "Z pattern" of eye scanning, key performance indicators (KPIs) are prominently displayed.  
- **Critical Charts Placement**:  
  - The **timeline of average outstanding time** appears in the top-left corner.  
  - The **comparison of urgent vs. routine specimens** is on the top-right corner.  
  - The histogram of specimen types is placed at the bottom, reflecting its secondary importance.  

This structure balances essential insights with clarity, ensuring a seamless user experience. The horizontal design supports both desktop viewing and larger management presentation screens.  

## 2.4 Charts  
Each chart was carefully chosen to convey specific insights:  
- **Timeline (Trendline)**: Tracks changes in specimen outstanding time over a specified period.  
- **Histogram (Distribution of Times)**: Visualizes the most common timeframes for delayed specimens.  
- **Stacked Bar Chart**: Compares the journey of urgent vs. routine specimens through the lab.  
- **Histogram (Specimen Types)**: Highlights outstanding times for different specimen types, useful for evaluating sub-specialties.  

Initially, histogram bins displayed exact values, but this cluttered the appearance. Users can now hover over bins for precise data, maintaining clarity.  

## 2.5 Interactive Design  
Interactivity enhances usability, allowing users to:  
- **Filter Data**: Isolate specific metrics across graphs for focused analysis.  
- **Drill Down**: Access detailed information, such as patient cases or specimen sub-specialties, empowering users to take targeted actions.  
For example, selecting the "Urgent" bin in the histogram reveals detailed specimen data, enabling timely intervention.  

## 2.6 Colour Scheme  
The dashboard predominantly uses shades of **blue**, chosen for its neutral and professional tone, supplemented by light and dark grey for contrast. The timeline's average line is highlighted in **orange**, ensuring it stands out and draws attention to critical insights.  

---

# Challenges and Considerations  
The biggest challenge was prioritizing information, as all data seemed equally important. Aligning the dashboard with its core purpose—tracking specimen time outstanding—helped determine focus areas. Each element supports the overarching narrative, providing a comprehensive view of delays and insights for improvement.  

---

# Summary  
The user-centred design approach ensures this dashboard is accessible, visually clear, and focused on tracking specimen time outstanding. Each feature, from chart selection to interactivity, enhances understanding and informs decisions to improve laboratory efficiency. The end result benefits both staff and patients by optimizing specimen management.  

---

# Recommendations  
Future iterations could include a secondary dashboard tailored to laboratory staff, leveraging advanced digital pathology and tracking systems. This would:  
- Provide precise, real-time updates on specimen locations.  
- Enable tracking of specimens over extended periods.  
- Enhance staff decision-making with detailed journey insights.  
Such innovations would further optimize specimen management and turnaround times.  

# References  

- **Bernardita Calzon (2023).** BI Blog | Data Visualization & Analytics Blog | datapine.  
  [Available at](https://www.datapine.com/blog/dashboard-design-principles-and-best-practices/).  

- **Mads Soegaard (2022).** Visual Hierarchy: Organizing content to follow natural eye movement patterns.  
  [Available at](https://www.interaction-design.org/literature/article/visual-hierarchy-organizing-content-to-follow-natural-eye-movement-patterns).  

- **Malnik, J. (2022).** Why Are Dashboards So Important for Your Business? 8 Ways They Help Improve Business Performance | Databox Blog.  
  [Available at](https://databox.com/why-are-dashboards-important).  

- **Priddy, S. (2021).** Best practices for building effective dashboards. Tableau.  
  [Available at](https://www.tableau.com/blog/best-practices-for-building-effective-dashboards?cq_cmp=20663578515&cq_net=x&cq_plac=&gad=1&gclid=CjwKCAjwnOipBhBQEiwACyGLunD1gVvg5KarHaMgTfYjAELi1YgRe28kmpDWaO-xLpcsKnv-JmIdkxoCcdYQAvD_BwE&gclsrc=aw.ds) [Accessed 27 Oct. 2023].  
