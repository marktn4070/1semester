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
*Edit on 05/01/2020*
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

## Upload of CSV files - UC-1.2
<details>
<b>ID: </b> UC-1.2<br>
<b>Priority: </b> High <br>
<b>Actors: </b>Municipality worker <br>
<b>Description: </b> Ability to upload CSV files with corona data. <br>
<b>Trigger:  </b> When the user clicks upload data files.

---

<h4>Type: </h4>

-  [x] External 
-  [ ] Temporal 
---
<h4>Preconditions</h4>

1. The CSV upload page is shown correctly.
2. CSV files are downloaded and usable.

---
<h4>Normal Course</h4>

1. User chooses CSV upload to pull the data.
2. User picks CSVs in file explorer.

---
<h4>Alternative Courses</h4>

1. User has not chosen CSVs.
2. Failed to load data/locate the files.
3. CSV upload is unresponsive.

---
<h4>Postconditions</h4>

1. Files are successfully uploaded and the data can be used.

</details>
