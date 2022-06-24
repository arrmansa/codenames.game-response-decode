# codenames.game-response-decode
Decodes Network responses of https://codenames.game/ and reveals answers.

## Instructions
Go to game url in chrome <br>
open developer tools using one of<br>
1. command + option + i 
2. ctrl + shift + i
3. tools > more tools > developer options

Select Network tab<br>
Refresh page <br>
Filter packets by 'transport=polling' and/or Fetch/XHR <br>
Find the latest one with more than 2kb of data <br>
Copy the response and paste it into response variable with single quotes or triple quotes <br>
