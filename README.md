#  Get daily oil price

This program allows you to view the oil price on a certain day of the year or in interval of a days

## Structur of software
The software is a webservice that share a mehtod call GetOilPriceTrend. It recives one string of json and, then after downloading of all price of history trend, it returnes the oil price of the day or days requests.

## How test it
You need to open the project WebTest and launch a debug. The program opens the WebService.asmx on your website with localHost url.
Then you can launch a AppTest.exe or open the second project and run it.
On AppTest you have to choose the days and press "Invio Richiesta" button.
The program show you in the left textbox the input json ( that is send on webservice ) , center text shows you the output json and in the grid there are a date and price convert for user.


