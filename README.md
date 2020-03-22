# covid19api
restful api for covid19 data<br>

endpoints:<br>
<b>/</b> : prints "Covid19 status API version 1.0.0" and available endpoints<br>
<b>/reports</b> : world wide report, includes country wise covid status<br>
<b>/reportsIndia</b>: current status of India, extracted from /reports response.<br>
<b>/deaths</b>: world wide death count for each day...can be used for graphing<br>
<b>/fatalityRateAge</b>: probability of death rate for age groups. ie chance for an age group infected by covid to die.<br>
<b>/fatalityRateSex</b>: probability of death rate for gender. ie chance for gender infected by covid to die.<br>
<b>/countryList</b>: list of countries infected<br>
<b>/countryWiseData/country</b>: country wise status for given country, country can be chosen from /countryList endpoint<br>


