# splunk_ukriverlevels_training
The UK River levels App without dashboards and data that need parsing

To add a river goto http://apps.environment-agency.gov.uk/river-and-sea-levels/ and browse though until you loacate the river you are intrested in.

Once at the rivers page extract the stationId, for example;
http://apps.environment-agency.gov.uk/river-and-sea-levels/120734.aspx?stationId=6016
Would have stationId 6016

Now enter this stationId in this file on a new line;
$splunkhome/etc/app/splunk_ukriverlevels_training/bin/rivers
