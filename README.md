# Illegal Hotel Inspections

Through a Freedom of Information request, WNYC obtained records from the Mayor's Office of Special Enforcement of 2,684 inspections looking for illegal short-term rental activity in New York City. The inspections occurred from October 2013 through April 2015.

The inspection reports include information about the property being inspected, the reason for the inspection, and any violations found.

**This data only contains inspection reports, not proof of actual wrong-doing.**

The data originally came as a set of Microsoft Word documents (see report-screenshot.png for example). These were converted to HTML and then each report was parsed for its contents.  We disregarded 193 reports of inspections that were for something other than short-term rental activity.

In `inspections.csv`, each row contains data on one inspection.  Some cells contain newline characters.

Personal information regarding the Apparent Person In Charge (APIC) is not included except for the sex and race fields.