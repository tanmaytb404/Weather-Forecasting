# Weather-Forecasting
 python script to fetch weather details (from AccuWeather API) at any pincode and log it to google sheets

Step1: 
Login/Register in AccuWeather API(https://developer.accuweather.com/apis) and goto MyApps.
Add a new sample app and the key will be generated.
Copy the unique key and store it in a variable.

Step2:
Visit the Current Conditions API tab and copy the url.
Now request for the url and store the in the json format.
Create temporary data structure and store the desired records from the json file.

Step3:
Create google sheet api.
i) To create google sheet api visit the Google Devepolers Console(https://console.developers.google.com/) and create a new project.
ii) Go to APIs overview -> Library -> Enable google sheet.
iii) Goto credentials and copy the Service Accounts Email.
iv) Download the api key from the Service Accounts Tab.

Step4:
Create a google sheet and share with the copied email.

Step5:
Call the Sheets API and write the data fetched from the Accuweather API.
