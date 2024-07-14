<<<<<<< HEAD

# FULL PROJECT - HR ANALYTICS - POWER BI

---

## 1. Context, business problem, and questions we want to answer:

- Working preferences for people: working from home or office
- Presence of employees at work
- Percentage of overall sick leave to monitoring employee wellness
- Show visualizacions and trendings and compare KPI during month or days of week

![header_photo](https://github.com/CarlEstP/attendance_work/blob/main/media/powerbi_capture.PNG)

## 2. Prepare dataset in Powerquery

- Load excel data
- Duplicate original dataset
- Promoted headers and delete first row
- Pivot the date columns to get only one column for date
- Change date column to date type to delete errors due to different data type
- Create a new parameter to set the the filtered rows dinamically
- Create a function from the template
- Add column and invoke the custom function just created
- Expand all the new columns and delete the columns that are not necesaries
- Rename columns and check data types

## 3. Metrics in PowerBI

- total working days (not 'WO', 'HO' wekkly off, holiday off)
- present days ('P' Present + 'WFH' + 'HWFH')
- percentage of work from home (presence % is present days / total working days)
- percentage of sick leave
- Measure WFH % ( divide wfh / present days)
- Measure SL Count (SL + HSL) sick leave
- Measure SL % ( divide sl count / total working days)

## 4. Dashboard visualization elements

- KPI Presence %
- KPI WFH %
- KPI SL %
- Lineal chart: Presence % by day of month (filtering all values except HO 'Holydays off, and final date 17/06)
- Lineal chart: WFH % by day of month (filtering all values except HO 'Holydays off, and final date 17/06)
- Lineal chart: SL % by day of month (filtering all values except HO 'Holydays off, and final date 17/06)
- Table: day of week - presence %
- Table: day of week - WFH %
- Table: day of week - SL %

## 5. Dashboard visualization elements

- The attendance at work decreases as the summer months approach.</li>
- Remote work increases as the summer months approach.</li>
- The employee sick leave increases as summer approaches.</li>
- Employees prefers remote work on friday, followed by monday, and then the rest of the days</li>

## 6. Scope and future requeriments

- Sending alerts: automatic emails to alert, for example, a high value of non presence workers.
- Automatic data refresh: update the data automatically.
- Setting security levels for data: two kind of reports where managers can view all the details, and employees only the trending.

---

### FONT

https://www.youtube.com/playlist?list=PLeo1K3hjS3uuVQccZa7yFwK3ltoGQOWbM

Codebasics.io
