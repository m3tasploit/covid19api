# covid19api
restful api for covid19 data<br>

endpoints:<br>
/ : prints "Covid19 status API version 1.0.0" and available endpoints<br>
/reports : world wide report, includes country wise covid status<br>
/reportsIndia: current status of India, extracted from /reports response.<br>
/deaths: world wide death count for each day...can be used for graphing<br>
/fatalityRateAge: probability of death rate for age groups. ie chance for an age group infected by covid to die.<br>
/fatalityRateSex: probability of death rate for gender. ie chance for gender infected by covid to die.<br>
/countryList: list of countries infected<br>
/countryWiseData/country: country wise status for given country, country can be chosen from /countryList endpoint<br>


