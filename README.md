# Workforce Presence Analytics

An Workforce Presence analytics dashboard built in **Microsoft Power BI** to explore
employee attendance patterns, work-from-home activity, and sick-leave
trends across April--June 2022.

![Workforce Presence Analytics
Dashboard](https://github.com/Himanshu584/Workforce-Presence-Analytics/blob/main/Dashboard.png))

## Project Overview

Workforce Presence Analytics provides an interactive view of employee
attendance and working preferences. The dashboard focuses on three key
indicators:

-   **Presence %** --- employee presence percentage.
-   **WFH %** --- work-from-home percentage.
-   **SL %** --- sick-leave percentage.

Users can select a month and review the indicators through daily trends,
weekday comparisons, and employee-level attendance details.

## Business Problem

The HR team wanted to understand employee working preferences and
attendance behaviour, including:

1.  What is the employee presence percentage, and how does it change
    over time?
2.  How does work-from-home activity vary by date and weekday?
3.  How frequently is sick leave recorded, and on which days does it
    occur?
4.  How do attendance patterns differ across employees?

## Project Objectives

-   Consolidate key attendance indicators in an interactive report.
-   Track Presence %, WFH %, and SL % for the selected month.
-   Compare daily trends and weekday-level patterns.
-   Provide employee-level attendance summaries and date-wise attendance
    details.

## Dataset

The source workbook contains monthly attendance worksheets for **April
2022, May 2022, and June 2022**, along with an attendance-key worksheet.

The monthly sheets include: - Employee code and employee name - Daily
attendance status for each date - Monthly present-day and leave-category
summary fields

### Attendance Status Codes

The workbook's attendance key includes the following codes:

  Code   Meaning
  ------ -------------------------
  P      Present
  WFH    Work From Home
  SL     Sick Leave
  PL     Paid Leave
  HPL    Half-day Paid Leave
  HSL    Half-day Sick Leave
  WO     Weekly Off
  HO     Holiday Off
  BL     Birthday Leave
  FFL    Floating Festival Leave
  BRL    Bereavement Leave
  LWP    Leave Without Pay
  ML     Menstrual Leave

Refer to the source workbook's attendance key when interpreting the
status codes.

## Dashboard Features

  -----------------------------------------------------------------------
  Component                           Description
  ----------------------------------- -----------------------------------
  Monthly selector                    Switch between April, May, and June
                                      2022

  KPI cards                           Presence %, WFH %, and SL % for the
                                      selected month

  Presence % by Date                  Daily presence trend

  WFH % by Date                       Daily work-from-home trend

  SL % by Date                        Daily sick-leave trend

  Weekday summaries                   Weekday comparison for Presence %,
                                      WFH %, and SL %

  Employee summary                    Employee-level attendance
                                      percentages

  Daily attendance detail             Date-wise attendance status by
                                      employee
  -----------------------------------------------------------------------

## Snapshot: April 2022

The current dashboard screenshot shows April 2022 selected, with the
following displayed KPI values:

-   **Presence:** 94.05%
-   **WFH:** 9.08%
-   **Sick Leave:** 0.43%

These figures represent the April view shown in the dashboard
screenshot. They should not be interpreted as combined results for all
three months.

## Key Takeaways

The dashboard brings together several levels of attendance analysis:

-   Overall monthly indicators provide a quick summary of the selected
    period.
-   Daily trend charts show how presence, WFH, and sick leave change
    over time.
-   Weekday tables make it possible to compare the three indicators
    across days of the week.
-   Employee-level tables allow the viewer to inspect individual
    attendance summaries and daily status entries.

The dashboard shows when patterns occur; the attendance data alone does
not establish why employees choose a particular work arrangement.
Additional employee or scheduling context would be needed to investigate
those reasons.

## Tools Used

-   **Microsoft Excel** --- attendance source data
-   **Microsoft Power BI** --- dashboard development and interactive
    reporting

## Repository Structure

``` text
Workforce-Presence-Analytics/
│
├── Dashboard.png
├── Workforce_Presence_Analytics.pbix
├── Attendance_Sheet_2022_2023_Masked.xlsx
└── README.md
```


## Project Link

-   **LinkedIn:** [View the original project
    post](https://www.linkedin.com/posts/hsharma98765_connections-powerbi-powerbidashboard-activity-7131566606089879553-tYSm)

------------------------------------------------------------------------

**Project:** Workforce Presence Analytics\
**Category:** HR Analytics \| Data Analytics \| Business Intelligence\
**Tool:** Microsoft Power BI
