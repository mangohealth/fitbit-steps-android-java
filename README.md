
## Requirements
Create an Android application that displays steps information from Fitbit.

Build your UI according to this mock: https://drive.google.com/file/d/0B64OB33WYv7JMG1Mb2VBdUJWanc/view

The app should:
* Authenticate with Fitbit API using OAuth2 Implicit Grant Flow
* Fetch today's data from Fitbit on app start
* Fetch today's data from Fitbit periodically while app is in foreground
* Persist data to database
* Display list of historical step data
* Pre-fetch data as user scroll through the list of historical step data

## Guidelines
* Don't be too concerned with satisfying all requirements above. We're more
interested in seeing how you solve problems and your work style given the time constraint.  
* Write production quality code with an emphasis on maintainability
* Write tests  
* Refactor existing code if necessary
* It's OK to use Google or other online resources
* It's OK to use 3rd party libraries
* When done, push your solution as a new branch

## Resources
* Fitbit API doc: https://dev.fitbit.com/reference/web-api/basics/
* Fitbit API OAuth doc: https://dev.fitbit.com/build/reference/web-api/oauth2/
* Client ID: 22BCNN
* Client Secret: 9404b49ceedf5c3113da7a52e8776a18
* Auth URI: https://www.fitbit.com/oauth2/authorize
* Access/Refresh token request URI: https://api.fitbit.com/oauth2/token
* Callback URL: app://fitbitsteps/oauth-callback (handle using Android App Link)
