# DHIS2-tracker-import-PHP
clean your csv data acceptable option codes for dropdown in tracker(ie maybe your data is 23-321-2 but tracker accept 233212)<br>
import csv into DB<br>
connect db with script<br>
in this case data of each TE is in single row<br>
copy output after running script, validate using any json validater (maybe comma at the end just remove)<br>
past in postman and POST data using https://domain.abc/api/trackedEntityInstances using username password<br>
Dhis2 V2.38.1.1
