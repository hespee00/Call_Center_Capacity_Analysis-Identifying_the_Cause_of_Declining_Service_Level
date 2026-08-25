# Call Center Capacity Analysis - Identifying the Cause of Declining Service Level

## Project Context
I worked on a call center dataset to investigate a decline in service-level performance.

The call center had a 90% service-level target, meaning calls should be answered within 60 seconds. However, performance had fallen below this target and continued to decline.

I wanted to understand what was driving the decline and what could be done about it.


## Problem Statement
The problem I set out to investigate was:
Why is the call center failing to maintain its 90% service-level target?


## Key Findings
- My analysis showed that call volume was increasing while the number of available agents remained at 4.

- As incoming calls increased, the existing agents had to handle a larger workload. This was accompanied by a decline in the percentage of calls answered within the required 60 seconds.

- I also investigated whether the problem was concentrated around particular days or times, but these did not show a meaningful pattern that changed my conclusion.

- The strongest contributor I identified was therefore increasing call volume against a fixed agent capacity.

- More importantly, I compared the average number of calls handled per agent during periods when the 90% service-level target was being met with periods when it was not. The difference was relatively small. This suggested that the operation was not far beyond its effective capacity; rather, it was being pushed slightly beyond the level at which the 4-agent team could consistently maintain the target.


## Tools Used
- Excel Power Query - Data cleaning and preparation
- Tableau - Analysis and visualizations


## Analysis Process
### Establish the Problem

I first measured the call center's service level against the 90% target. This confirmed that the call center was performing below the required standard and that performance was deteriorating over time.

  <img width="719" height="559" alt="Service Level D" src="https://github.com/user-attachments/assets/dfac70b9-91ff-4893-8e3e-7a6da7641cd4" />

### Look for What Was Changing

I then examined the main operational measures available in the dataset to identify what was changing alongside the decline in service level. The most noticeable pattern was an increase in incoming call volume.

I knew the call center had 4 agents available at any given time. With call volume increasing but agent capacity remaining fixed, I examined whether the growing demand could explain the decline in service level. The data showed that as call volume increased, the service level declined.

<img width="719" height="559" alt="Call Volume vs Service Level D" src="https://github.com/user-attachments/assets/8018092a-b540-400e-b329-7b9a66807d74" />

### Measure the Capacity Gap

I then compared the average calls handled per agent during periods when the call center was still meeting the 90% target with periods when it was falling below the target.

The difference was relatively small. This was important because it showed that the call center was not facing an enormous capacity shortfall. The operation was relatively close to the level of demand it could handle while maintaining the target.

<img width="719" height="559" alt="Avg Call Volume per agent D" src="https://github.com/user-attachments/assets/b5474ce5-5d96-4694-9dd8-3600733ef7e5" />

## Main Takeaways
The main takeaway from my analysis is that the call center's service-level problem appears to be a capacity-versus-demand issue.

Call volume is increasing, but the number of available agents remains fixed at 4. As demand increases, the existing capacity becomes less able to maintain the 90% service-level target.

However, the capacity gap is relatively small. My comparison of calls handled per agent showed that the operation is close to the workload level at which it can maintain the target.

This suggests that the problem may not require a major staffing increase. One additional agent could potentially provide the capacity needed to bring performance back into line with the service-level target.


## Recommendations
Based on my findings, I would recommend that management:

- Evaluate adding one additional agent to determine whether the additional capacity is sufficient to consistently maintain the 90% service-level target.
- Investigate the reason behind the increase in call volume. My analysis identifies the increase in demand, but the available data does not explain what is causing it.


## Limitations
The biggest limitation of my analysis is that the dataset does not explain why call volume increased. Further investigation would require additional operational and business data.




















