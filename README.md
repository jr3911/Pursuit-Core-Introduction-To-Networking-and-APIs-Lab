# Pursuit-Core-Introduction-To-Networking-and-APIs-Lab

# Part One

Status Code Scavenger Hunt!

Use Postman to find each of the following HTTP codes:

```swift
1. 200
https://httpstat.us/200
Status code 200 means that the request was successful.
No need to resolve.

2. 301
https://httpstat.us/301
Status code 301 means that the domain has moved permanently. Redirects.
No need to resolve.

3. 400
https://httpstat.us/400
Status code 400 means bad request. The url is incorrect and the domain does not have that page.
Fix the url and find a valid page.

4. 401
https://httpstat.us/401
Status code 401 means that the user is not authorized to access that page.
Get authorization or give up, or hack it idk.

5. 403
https://httpstat.us/403
Status code 403 means that the page is absolutely forbidden and cannot be accessed by the user.
Give up.

6. 404
https://httpstat.us/404
Status code 404 means that the page was not found on server. Client-side error, page was removed or moved.
Resolve by checking url.

7. 418
https://httpstat.us/418
Status code 418 indicates server refuses to brew coffee because its a teapot.
Resolve by giving up and accepting the natural order of things.

8. 500
https://httpstat.us/500
Status code 500 means internal server error, server cannot process the request for an unknown reason.
Is a generic response.

```

For each of the questions below, write:

1. The website which generated the HTTP status code
2. A description of what the status code means
3. If an app you were writing encountered this status code, what would you do (if anything) to resolve any issues?


For reference, see:

https://en.wikipedia.org/wiki/List_of_HTTP_status_codes (Links to an external site.)
https://http.cat


# Part Two

API Scavenger Hunt!

For each of the questions below, identify a website and search query that will give you the appropriate JSON.  Paste the url and the json below.  Googling the category + API will generally take you to where you need.  Ex. https://lmgtfy.com/?q=cat+fact+api

```swift
0. A random cat fact - https://catfact.ninja/fact?max_length=140
    {
    
    "fact": "Abraham Lincoln loved cats. He had four of them while he lived in the White House.",
    "length": 82
    
    }

1. A list of 150 random users in English. - https://randomuser.me/api/?results=150
    <details>
    <summary> Example of user </summary>
    {

    "results": [
    {
    "gender": "male",
    "name": {
    "title": "mr",
    "first": "raymond",
    "last": "fowler"
    },
    "location": {
    "street": "60 the avenue",
    "city": "bray",
    "state": "cork city",
    "postcode": 99907,
    "coordinates": {
    "latitude": "16.7593",
    "longitude": "-69.4323"
    },
    "timezone": {
    "offset": "-2:00",
    "description": "Mid-Atlantic"
    }
    },
    "email": "raymond.fowler@example.com",
    "login": {
    "uuid": "c460d22f-575e-497c-a207-4b5f238d06aa",
    "username": "angrykoala338",
    "password": "brooke",
    "salt": "wDu3KEXA",
    "md5": "1d1370ed23166f37c278444281779f67",
    "sha1": "68c66a2ececc3ba8b80c1b69c3711c75c9d9cfb7",
    "sha256": "871aec21e68c991f3b4dff9ff1639a52425fa969c6033d1f16d7799ad2921a96"
    },
    "dob": {
    "date": "1982-08-08T07:01:40Z",
    "age": 37
    },
    "registered": {
    "date": "2008-01-21T09:13:03Z",
    "age": 11
    },
    "phone": "021-158-0366",
    "cell": "081-028-9753",
    "id": {
    "name": "PPS",
    "value": "7995935T"
    },
    "picture": {
    "large": "https://randomuser.me/api/portraits/men/98.jpg",
    "medium": "https://randomuser.me/api/portraits/med/men/98.jpg",
    "thumbnail": "https://randomuser.me/api/portraits/thumb/men/98.jpg"
    },
    "nat": "IE"
    },
    
    </details>

2. The current stock price of Microsoft. (IEX API) - https://www.alphavantage.co/query?function=GLOBAL_QUOTE&symbol=MSFT&apikey=demo
    <details>
    <summary> Example </summary>
    {
    "Global Quote": {
    "01. symbol": "MSFT",
    "02. open": "111.8000",
    "03. high": "112.2100",
    "04. low": "110.9100",
    "05. price": "111.7500",
    "06. volume": "25644105",
    "07. latest trading day": "2018-11-08",
    "08. previous close": "111.9600",
    "09. change": "-0.2100",
    "10. change percent": "-0.1876%"
    }
    }
    </details>


3. The 5 year history of Apple stock prices (IEX API)
    <details>
    <summary> Example </summary>
    
    </details>


4. All the Swift language repos on Github with Pursuit in their name
    <details>
    <summary> Example </summary>

    </details>

5. A list of all Pokemon - https://pokeapi.co/api/v2/pokemon
    <details>
    <summary> Example </summary>
    {
    
    "count": 964,
    "next": "https://pokeapi.co/api/v2/pokemon?offset=20&limit=20",
    "previous": null,
    "results": [
    {
    "name": "bulbasaur",
    "url": "https://pokeapi.co/api/v2/pokemon/1/"
    },
    {
    "name": "ivysaur",
    "url": "https://pokeapi.co/api/v2/pokemon/2/"
    },
    {
    "name": "venusaur",
    "url": "https://pokeapi.co/api/v2/pokemon/3/"
    },
    {
    "name": "charmander",
    "url": "https://pokeapi.co/api/v2/pokemon/4/"
    },
    {
    "name": "charmeleon",
    "url": "https://pokeapi.co/api/v2/pokemon/5/"
    },
    {
    "name": "charizard",
    </details>

6. A list of all items in Fortnite
    <details>
    <summary> Example </summary>

    </details>

7. A list of all Game of Thrones Episodes.
    <details>
    <summary> Example </summary>

    </details>

8. A list of all songs with "Love" in the title.
    <details>
    <summary> Example </summary>

    </details>

9. All information about Petyr Baelish from the Game of Thrones books
    <details>
    <summary> Example </summary>

    </details>

10. All the movies Leonardo Dicaprio has acted in
    <details>
    <summary> Example </summary>

    </details>

```
