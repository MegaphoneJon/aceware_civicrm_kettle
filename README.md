# aceware_civicrm_kettle
An example Pentaho Kettle job script that migrates contribution/membership data from Aceware Student Manager to CiviCRM

1. Open the program “Pentaho Kettle”.
2. If it's not already open, open the script called “Run Me First”.
3. Double-click the “Set Report Dates” icon.  Set the begin and end date (in 4-year date format, e.g. 3/4/2015) to pull from Aceware and press “OK”.
4. Press the “Run” button (green arrow), then press “Launch”.
5. Open the script called “Aceware Cleanup”
6. Press the “Run” button, then press “Launch” (will take 2 sec per record). Once finished, you’ll find a green check by the “Civi Clean Data” box.
7. At this point, you will have three Excel files in the “aceware exports” folder - “contact export.xls”, “gift export.xls”, and “clean data for CiviCRM.xls”.  The first two are exact copies of what you would get if you ran the “Lesley test” reports from within Aceware.  You don't need them; they're just there so you can feel confident that the data is the same as the old way!
8. Review the data in “clean data for CiviCRM”.  You can make edits directly here; you may also want to make those edits in Aceware.
9. Open the script called “Import into CiviCRM”
10. Press the “Run” button.  This takes about 4 seconds per record.
