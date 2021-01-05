# Use Case Overview

| Done? | UC ID  | Use Case                                            |
|-------|--------|-----------------------------------------------------|
| [x]   | UC-1.1 | Display of relevant data                            |
| [x]   | UC-1.2 | Upload of CSV files                                 |
| [x]   | UC-1.3 | Add/remove industries to lockdown/restrictions list |
| [x]   | UC-1.4 | Choose municipality                                 |
| [x]   | UC-1.5 | Lockdown/restriction indicator                      |
| [x]   | UC-1.6 | Display general restrictions                        |

# Use Cases

## Display of relevant data  - UC-1.1
<details>
<b>ID: </b> UC-1.1<br>
<b>Priority: </b> High <br>
<b>Actors: </b>Municipality worker <br>
<b>Description: </b> Dashboard for corona data. <br>
<b>Trigger:  </b> Display when municipality is selected.

---

<h4>Type: </h4>

-  [x] External 
-  [ ] Temporal 
---
<h4>Preconditions</h4>

1. Choose CSVs with up to date data.
---
<h4>Normal Course</h4>

1. Data is pulled when CSVs are chosen.
2. The relevant data is shown.
---
<h4>Alternative Courses</h4>

1. User has not chosen CSVs. 
2. Failed to load data.
---
<h4>Postconditions</h4>

1. Users can work with the data, see predictions and restrictions.

</details>
