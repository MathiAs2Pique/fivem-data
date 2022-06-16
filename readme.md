# Fivem Data
Here are some data I needed to succeed in some private projects, which I had a hard time to find, so I think it's good to put it here

## How did I get this data ?
Using their APIs, and some regex. (So there is false data sometimes, It didn't bother me.

### Description of the files

- cfx-codes : List of cfx codes (cfx.re/join/[code])
Note : I'm sorry but for this file, I could not create a json object because of its size.
Note 2 : I got this file by using regex, but there is like 0,1% of false codes, be careful by using it.

- cfx-codes-array : codes, locales, premium status, owners in json format.
Note : If no locale : "unknown-unknown". If no premium : "na"
Note 2 : There is in this file informations about 24.897 servers, those who were offline when I retrieved the information were not included