# Machine Learning for China Life Expectancy
## Project information
- **Author**: Yiyang Zhang, Computation and Design with tracks in Digital Media, Class of 2025, Duke Kunshan University
- **Instructor**: Prof. Luyao Zhang, Duke Kunshan University
- **Disclaimer**: Submissions to the Problem Set 2 for STATS201 Introduction to Machine Learning for Social Science, 2023 Spring Term (Seven Week - First) instructed by Prof. Luyao Zhang at Duke Kunshan University.
- **Acknowledgments**: Thanks for Xintong Wu's encouragement and Shiran Yuan's suggestion on the selection of timeline.
- **Project Summary**: 
  - [Summarize the Background/Motivation]
  - [Research Questions]
  - [Application Scenario (Data Source)]
  - [Methodology]
  - [Results]
  - [Intellectual Merits and Practical impacts of your project.]

## Table of Contents
<table class="MsoTableGrid" border="1" cellspacing="0" style="border-collapse:collapse;border:none;mso-border-left-alt:0.5000pt solid windowtext;
mso-border-top-alt:0.5000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;
mso-border-insideh:0.5000pt solid windowtext;mso-border-insidev:0.5000pt solid windowtext;mso-padding-alt:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;"><tbody><tr><td width="426" valign="top" style="width:426.1000pt;padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:1.0000pt solid windowtext;
mso-border-left-alt:0.5000pt solid windowtext;border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;
border-top:1.0000pt solid windowtext;mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;
mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal"><span style="font-family:Calibri;mso-fareast-font-family:宋体;mso-bidi-font-family:'Times New Roman';
font-size:10.5000pt;mso-font-kerning:1.0000pt;"><a href="https://github.com/Rising-Stars-by-Sunshine/stats201-PS2-Yiyang/tree/main/data">data</a></span><span style="font-family:Calibri;mso-fareast-font-family:宋体;mso-bidi-font-family:'Times New Roman';
font-size:10.5000pt;mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td></tr><tr><td width="426" valign="top" style="width:426.1000pt;padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:1.0000pt solid windowtext;
mso-border-left-alt:0.5000pt solid windowtext;border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;
border-top:none;mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;
mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal"><span style="font-family:Calibri;mso-fareast-font-family:宋体;mso-bidi-font-family:'Times New Roman';
font-size:10.5000pt;mso-font-kerning:1.0000pt;"><a href="https://github.com/Rising-Stars-by-Sunshine/stats201-PS2-Yiyang/tree/main/code">code</a></span><span style="font-family:Calibri;mso-fareast-font-family:宋体;mso-bidi-font-family:'Times New Roman';
font-size:10.5000pt;mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td></tr><tr><td width="426" valign="top" style="width:426.1000pt;padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:1.0000pt solid windowtext;
mso-border-left-alt:0.5000pt solid windowtext;border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;
border-top:none;mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;
mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal"><span style="font-family:Calibri;mso-fareast-font-family:宋体;mso-bidi-font-family:'Times New Roman';
font-size:10.5000pt;mso-font-kerning:1.0000pt;"><a href="https://github.com/Rising-Stars-by-Sunshine/stats201-PS2-Yiyang/tree/main/spotlight">spotlight</a></span><span style="font-family:Calibri;mso-fareast-font-family:宋体;mso-bidi-font-family:'Times New Roman';
font-size:10.5000pt;mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td></tr></tbody></table>


## Data
- Data Source:https://ourworldindata.org/life-expectancy
<table class="MsoNormalTable" border="0" cellspacing="0" style="border-collapse:collapse;margin-left:6.7500pt;mso-table-layout-alt:fixed;
border:none;mso-padding-alt:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;"><tbody><tr style="height:31.1000pt;"><td width="104" valign="top" rowspan="3" style="width:104.0000pt;padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;
mso-border-left-alt:none;border-right:none;mso-border-right-alt:none;
border-top:none;mso-border-top-alt:none;border-bottom:none;
mso-border-bottom-alt:none;"><p class="MsoNormal" style="mso-pagination:widow-orphan;"><span style="font-family:'Times New Roman Regular';mso-fareast-font-family:宋体;font-size:10.5000pt;
mso-font-kerning:1.0000pt;">Explanation</span><span style="font-family:'Times New Roman Regular';mso-fareast-font-family:宋体;font-size:10.5000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td width="339" valign="top" style="width:339.7500pt;padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;
mso-border-left-alt:none;border-right:none;mso-border-right-alt:none;
border-top:none;mso-border-top-alt:none;border-bottom:none;
mso-border-bottom-alt:none;"><p class="MsoNormal" style="mso-pagination:widow-orphan;"><span style="font-family:'Times New Roman Regular';mso-fareast-font-family:宋体;font-size:10.5000pt;
mso-font-kerning:1.0000pt;"><a href="https://github.com/Rising-Stars-by-Sunshine/stats201-PS2-Yiyang/blob/main/data/Queried_Data/life-expectancy.csv">life-expectancy</a></span><span style="font-family:'Times New Roman Regular';mso-fareast-font-family:宋体;font-size:10.5000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td></tr><tr style="height:31.1000pt;"><td width="339" valign="top" style="width:339.7500pt;padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;
mso-border-left-alt:none;border-right:none;mso-border-right-alt:none;
border-top:none;mso-border-top-alt:none;border-bottom:none;
mso-border-bottom-alt:none;"><p class="MsoNormal" style="mso-pagination:widow-orphan;"><span style="font-family:'Times New Roman Regular';mso-fareast-font-family:宋体;font-size:10.5000pt;
mso-font-kerning:1.0000pt;"><a href="https://github.com/Rising-Stars-by-Sunshine/stats201-PS2-Yiyang/blob/main/data/Queried_Data/HL.csv">Queried Data</a></span><span style="font-family:'Times New Roman Regular';mso-fareast-font-family:宋体;font-size:10.5000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td></tr><tr style="height:31.1000pt;"><td width="339" valign="top" style="width:339.7500pt;padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;
mso-border-left-alt:none;border-right:none;mso-border-right-alt:none;
border-top:none;mso-border-top-alt:none;border-bottom:none;
mso-border-bottom-alt:none;"><p class="MsoNormal" style="mso-pagination:widow-orphan;"><span style="font-family:'Times New Roman Regular';mso-fareast-font-family:宋体;font-size:10.5000pt;
mso-font-kerning:1.0000pt;"><a href="https://github.com/Rising-Stars-by-Sunshine/stats201-PS2-Yiyang/blob/main/data/Processed_Data/CHL.csv">Processed Data</a></span><span style="font-family:'Times New Roman Regular';mso-fareast-font-family:宋体;font-size:10.5000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td></tr><tr style="height:31.1000pt;"><td width="104" valign="top" rowspan="2" style="width:104.0000pt;padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;
mso-border-left-alt:none;border-right:none;mso-border-right-alt:none;
border-top:none;mso-border-top-alt:none;border-bottom:none;
mso-border-bottom-alt:none;"><p class="MsoNormal" style="mso-pagination:widow-orphan;"><span style="font-family:'Times New Roman Regular';mso-fareast-font-family:宋体;font-size:10.5000pt;
mso-font-kerning:1.0000pt;">Prediction</span><span style="font-family:'Times New Roman Regular';mso-fareast-font-family:宋体;font-size:10.5000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td width="339" valign="top" style="width:339.7500pt;padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;
mso-border-left-alt:none;border-right:none;mso-border-right-alt:none;
border-top:none;mso-border-top-alt:none;border-bottom:none;
mso-border-bottom-alt:none;"><p class="MsoNormal" style="mso-pagination:widow-orphan;"><span style="font-family:'Times New Roman Regular';mso-fareast-font-family:宋体;font-size:10.5000pt;
mso-font-kerning:1.0000pt;"><a href="https://github.com/Rising-Stars-by-Sunshine/stats201-PS2-Yiyang/blob/main/data/Processed_Data/Regression_Train.csv">Regression Train</a></span><span style="font-family:'Times New Roman Regular';mso-fareast-font-family:宋体;font-size:10.5000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td></tr><tr style="height:16.7500pt;"><td width="339" valign="top" style="width:339.7500pt;padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;
mso-border-left-alt:none;border-right:none;mso-border-right-alt:none;
border-top:none;mso-border-top-alt:none;border-bottom:none;
mso-border-bottom-alt:none;"><p class="MsoNormal" style="mso-pagination:widow-orphan;"><span style="font-family:'Times New Roman Regular';mso-fareast-font-family:宋体;font-size:10.5000pt;
mso-font-kerning:1.0000pt;"><a href="https://github.com/Rising-Stars-by-Sunshine/stats201-PS2-Yiyang/blob/main/data/Processed_Data/Regression_Test.csv">Regression Test</a></span><span style="font-family:'Times New Roman Regular';mso-fareast-font-family:宋体;font-size:10.5000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td></tr></tbody></table>

## Code
- Query Data
- Process Data
- Analyze Data
- ...

## Spotlight
- Figures
- Posters
- Slides
- Presentations
- Review articles
- Media appearance

## References

### Data Source
- Data Source Title and URL
### Code Source
- Code Source Title and URL
### Articles
- Article Source Title and URL
### Literature
- Literature References in [Chicago Author-Date](https://www.chicagomanualofstyle.org/tools_citationguide/citation-guide-2.html) Style and [BibTex](https://scholar.google.com/) 

Levin, Dan, and Luyao Zhang. 2020. “Bridging Level-K to Nash Equilibrium.” *The Review of Economics and Statistics* 104 (6): 1329–40. https://doi.org/10.1162/rest_a_00990.

