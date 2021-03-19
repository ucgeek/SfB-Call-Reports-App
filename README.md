# SfB-Call-Reports-App
Skype for Business and Lync Call Reporting Script
     
Skype for Business and Lync Call Reports processes data from your Skype for Business or Lync Monitoring Server database (LcsCDR database) and presents it in an easy to read and searchable format. Additionally you can import vendor rate cards to calculate call costs, which get associated a users Department and Company specified in Active Directory.

  *  Search and filter results 
  *  CSV export 
  *  Ability to bill based on users Active Directory department or company field 
  *  Import vendor rate cards to perform call rate and cost calculations 
  *  Determines if the destination and callers number is in the same calling region to apply a local call rate
  *  Import vendor gateways - Determines call direction - inbound, outbound, forwarded, SfB-to-SfB
  *  Handles billing of forwarded calls using the Referred-By information

For more information see - https://ucgeek.co/call-accounting/

# History
* 1.0.0.1 - 29/06/2014 First Release
* 1.0.0.2 - 01/07/2014 Resolved issue with save CSV path selector
* 1.0.0.5 - 27/07/2014 Bug fixes, added debug mode
