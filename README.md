# Hotel Booking Analysis \| Microsoft Excel

## Project Overview

This beginner-level data analytics project explores hotel booking
records using Microsoft Excel. It uses booking data, Pivot Tables, and
summary metrics to examine hotel types, guest categories, monthly
booking patterns, and cancellations.

The workbook contains three sheets: - `hotel_bookings` -- booking-level
dataset - `Pivot` -- summary tables used for analysis - `Dashboard` --
dashboard worksheet

## Objectives

-   Compare bookings for City Hotels and Resort Hotels.
-   Examine cancelled bookings and cancellation rates.
-   Compare booking and cancellation counts across guest categories.
-   Explore monthly booking and cancellation patterns.
-   Summarize the results using Excel Pivot Tables.

## Dataset

The dataset contains **119,390 records** and **22 columns**.

Important fields include: - `hotel` -- hotel type - `is_canceled` --
cancellation indicator - `arrival_date_year` and `arrival_date_month` --
arrival period - `adults`, `children`, and `babies` -- guest counts -
`country` -- guest country - `reserved_room_type` and
`assigned_room_type` -- room types - `deposit_type` -- deposit
category - `customer_type` -- customer category

The CSV version of the dataset is stored in the `Dataset/` folder. The
Excel workbook contains the dataset and the Pivot Table summaries.

## Tools Used

-   Microsoft Excel
-   Pivot Tables
-   Basic data analysis
-   Data summarization

## Analysis and Findings

The Pivot Table summaries in the workbook show:

### Hotel type

  Hotel Type       Total Bookings   Cancelled Bookings
  -------------- ---------------- --------------------
  City Hotel               79,330               33,102
  Resort Hotel             40,060               11,122
  **Total**           **119,390**           **44,224**

### Guest category

  Guest Category     Total Bookings   Cancelled Bookings
  ---------------- ---------------- --------------------
  Couples                    81,560               32,424
  Family                     15,253                5,245
  Single                     22,577                6,555

### Key observations

-   City Hotels account for more bookings than Resort Hotels in this
    dataset.
-   Couples are the largest guest category in the Pivot Table summary.
-   The workbook also includes monthly booking and cancellation
    summaries.
-   Cancellation counts can be compared across hotel types and guest
    categories.

*Note: These figures are reproduced from the workbook's Pivot Table
summaries.*

## Repository Structure

``` text
Hotel-Booking-Analysis/
│
├── Dataset/
│   └── hotel_bookings.csv
│
├── Project Hotel_Booking.xlsx
│
├── Screenshots/
│   └── hotel-dashboard.png
│
└── README.md
```

If you have not added a dashboard screenshot yet, you can leave the
`Screenshots/` folder out until one is available.

## How to Explore the Project

1.  Download or open `Project Hotel_Booking.xlsx`.
2.  Open the `hotel_bookings` sheet to view the booking records.
3.  Open the `Pivot` sheet to explore the summary tables.
4.  Use the CSV file in `Dataset/` if you want to work with the raw data
    in another analysis tool.

## Skills Practiced

-   Working with structured datasets in Excel
-   Creating and interpreting Pivot Tables
-   Summarizing booking and cancellation data
-   Comparing categories and identifying patterns
-   Communicating findings from data

## Future Improvements

-   Complete and refine an interactive Excel dashboard.
-   Add charts and slicers for interactive filtering.
-   Explore the dataset using Python and Pandas.
-   Add further analysis of booking trends and customer behaviour.

## Author

**Arpita Kamboj**\
Computer Science Engineering Student \| Aspiring Data Analyst

[GitHub Profile](https://github.com/arpita7819)
