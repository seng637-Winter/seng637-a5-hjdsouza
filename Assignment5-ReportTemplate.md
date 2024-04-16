**SENG 637- Dependability and Reliability of Software Systems***

**Lab. Report \#5 – Software Reliability Assessment**

| Group \#:       |   |
|-----------------|---|
| Student Names:  |   |
|                 |   |
|                 |   |
|                 |   |

# Introduction

# 

# Assessment Using Reliability Growth Testing 

# Assessment Using Reliability Demonstration Chart 

## Explain your evaluation and justification of how you decide the MTTFmin
The corresponding visual depiction in Figure 1 indicates that the system's threshold for a satisfactory Mean Time To Failure (MTTF) is 2 time units. This was established by observing where the failure points intersect with the 'accept' boundary on the RDC graph. Figure 2, which presents an MTTF of 1 time unit, places the system predominantly in the 'reject' area, suggesting an insufficient reliability level at this value. Conversely, Figure 3, illustrating an MTTF of 4 time units, demonstrates a conservative estimate, as the system remains within the 'accept' region across the entire duration.

To pinpoint the MTTFmin, a sensitivity analysis was performed on the available failure data. This method allowed for an investigation into how changes in the MTTF value influenced the system's projected reliability on the Reliability Demonstration Chart (RDC). By adjusting the MTTF value and observing the system's response on the RDC—specifically, whether the observed failures fell within the accept, continue testing, or reject regions—we could determine the most suitable MTTF value.

Through this analysis, we found that an MTTF of 2 units kept the observed failures within the RDC's accept region, suggesting this as the system's minimum reliable operational interval. An MTTF of 1 unit, which pushed the failure line into the reject region, was deemed too frequent and therefore unacceptable. On the other hand, an MTTF of 4 units, which maintained the failure line within the accept region, indicated a more robust than necessary reliability level.

# Comparison of Results

# Discussion on Similarity and Differences of the Two Techniques

# How the team work/effort was divided and managed

# 

# Difficulties encountered, challenges overcome, and lessons learned

# Comments/feedback on the lab itself
