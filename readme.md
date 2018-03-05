# Prototyping Dashboards with Google Sheets as the Data Source

## About

Wanted a way to produce readable JSON from a Google Sheet.

### Parameters

**id (required):** The ID of your document. This is the big long aplha-numeric code in the middle of your document URL.

**sheet (optional):** The number of the individual sheet you want to get data from. Your first sheet is 1, your second sheet is 2, etc. If no sheet is entered then 1 is the default.

**q (optional):** A simple query string. This is case insensitive and will add any row containing the string in any cell to the filtered result.

**integers (optional - default: true)**: Setting 'integers' to false will return numbers as a string.

**rows (optional - default: true)**: Setting 'rows' to false will return only column data.

**columns (optional - default: true)**: Setting 'columns' to false will return only row data.
