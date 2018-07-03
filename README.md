# eoxquery
Simple Query Application for Cisco Smartnet Total Care EOX API

## Requirements
This application requires access to the "EOX API" provided at [https://apiconsole.cisco.com/](https://apiconsole.cisco.com/).  Note, this API is actually provided by the SmartNet Total Care Service.  

Details of the API is documented at the following link: [https://developer.cisco.com/docs/support-apis/#!eox](https://developer.cisco.com/docs/support-apis/#!eox)

You will need to register for an account.   This will allow you to request access to the API which allows you to query for Cisco Access.   In addition when you register, you can generate client credentials that will then be used within the package_config.ini file.   A smaple file is provided.

## Usage
eoxquery is a very simple application that allows you to query either by serial number or by product pid.

An example is shown below.   The application will prompt you for either a "pid" or a "serial" number.

```Cisco EOX Query Engine Starting...

Enter search string (ex: 'serial {serialnumber}' or 'pid {pid}' or 'quit'): pid C2801-10UC-VSEC/K9
Performing pid search for: 'C2801-10UC-VSEC/K9':
Search Value:C2801-10UC-VSEC/K9 
Product ID: C2801-10UC-VSEC/K9
Product Description: 2801 w/PVDM2-32,AIM2-CUE,10 CME/CUE/Ph lic,Adv IP,128F/384D
End of Sale Date ................. 2011-11-01
End of Software Maint Date ....... 2014-10-31
End of Security Vul Support Date . 2014-10-31
End of Routine Failure Date ...... 2012-10-31
End of Service Contract Date ..... 2016-01-30
Last Date of Support Date ........ 2016-10-31
End of Service Attach Date ....... 2012-10-31
Migration PID: C2901-VSEC-SRE/K9
