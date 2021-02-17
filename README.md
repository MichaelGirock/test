Have the 3 files app.py, index.html, styles.css (for styles.css use the styles with the most s's, CSS is broken where i had to make new one everytime) index.html should be in a template folder styles.css should be in static folder

import requests, os, bs4 for BeautifulSoup

make a .env with { export CLIENT_ID = '' export CLIENT_SECRET = '' export GENIUS_ACCESS_TOKEN = '' }

Problems is using CSS, i had to remake the file everytime I changed it Another is uploading to GIT, it doesnt seem to update when I git add, commit, and push

Problems I fixed

Couldnt get token for genius, i made a seperate .py to keep running it and testing it, and eventually realized my get_uri was wrong and the way i searched, to where i just did more and more reading a googling till i found what i was looking for (dont have the website :( )
The start of the project i really struggled with getting info from the API and how to navigate. This was mainly solved by reading the page over and over again and looking through slack
Had problems with css and changing things. This was fixed to when i did my interview, that was actaully one of the questions, i got wrong but the TA told me how to fix it and be able to implement CSS to persoanlized things
