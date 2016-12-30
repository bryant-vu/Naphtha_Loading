# Naphtha_Loading
SAM Reporting
Naphtha_Loading.exe is intended for use during LTR”s SAM reporting.

#The following provides background information:

1) LTR’s Scale Reports program records data on naphtha loading via Racks 7 and 8 (D136).

2) LTR reduces throughput data each semi-annual period to ensure no throughput (C1.33) exceedances.

3) The program will output an Excel file titled “YYYY-MM-DD to YYYY-MM-DD_Naphtha Loading_C1.33” at the location of the ‘rptDailyReportEnviro_naphtha’ file. (For example, if the ‘rptDailyReportEnviro_naphtha’ file is located in a folder titled “Data”, the program will create “YYYY-MM-DD to YYYY-MM-DD_Naphtha Loading_C1.33” in the “Data” folder).

4) The program will also accept a file with the name “rptDailyReportEnviro’” but be sure the file contains data for distillate loading.

5) In LTR’s Scale Reports, be sure to export the distillates data using the Compliance button. No filtering of the data is required – the application does that for you.


