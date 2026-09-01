# DOCUMENTATION
## Connections to GitHub
`Due to Fallout being reliant on GitHub for game file retrieval and version checking, not being able to connect to GitHub due to lack of Internet or GitHub being blocked results in Fallout being non-functional.`
### Version
The version number is set in two places: *index.html* and *version.txt*. If the code in *index.html* detects that the text in *version.txt* is different that what is present on the website, an alert will pop up encouraging you to update to the newest version. Note that usually this is not strictly necessary, just a recommendation.
### Games
All game files should have names like *1.html*, *2.html*, *3.html*, etc. These are then loaded in on demand when you select games on the site. This is done to reduce client load, and make sure the downloadable version of Fallout remains mostly standalone and is not bloated with game files.

## Secrets
There are two secret game tabs in Fallout. I will give them out on occasion. Please do not pester me about it.
