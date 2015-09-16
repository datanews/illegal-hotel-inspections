# Illegal Hotel Inspections

Through a Freedom of Information request, WNYC obtained records of the 2,684 inspections made between October 2013 through April 2015 looking for rentals that violate local laws.

**This data is only inspections and does not equate to any actual wrong-doing.**

The repository includes a parsed CSV of that data as `inspections.csv`.  The data originally came as a set of Microsoft Word documents (see `report-screenshot.png` for example).These were converted to HTML and then each report was parsed out into the CSV where each row is a report.

All data was parsed from the original document besides all the Apparent Person In Charge (APIC) fields excluding the *Sex* and *Race* fields. A few auxiliary fields were added for easier analysis.

Once parsed, we manually removed rows that were obviously not related to illegal hotels.
