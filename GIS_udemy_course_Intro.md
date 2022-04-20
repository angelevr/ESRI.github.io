### GIS Introduction
We'll learn web applications such as:
- HTML
- CSS
- Bootstrap
- JavaScript
- JQuery
- PHP
- SQL

We'll also learn geospatial applications such as:
- Leaflet
- OpenLayers
- PostGIS
- geoJSON
- geospatial data storage
- retrieval analysis
- display

**How is programming for the web different than a single user desktop environment?**
Client-Server Architecture
- Hundreds or thousands of clients accessing one server
- Clients can be using different browsers, different operating systems, different screen sizes etc.
- Data is stored on the server and requeted by the client
- User interaction occurs on the client, data access is handled by the server, and data processing can occur on either end
- As a result you need to know how to program on the client side as well as the server side
- More importantly you need to know WHEN to handle things on the client and when to handle things on the server and how to communicate between client and server
- Servers process requests and return a result, then Clients do something with the results
- Just like a server in a restaurant
    - You (the client) tell the server what you want (Request)
    - The server delivers it to you (Result), and then you do something with it

- This requires things to happen on both ends
    - In order to process your request, the server informs the cook of your order and the cook          prepares the food from scratch and then the server delivers it to the client
    - This happens behind the scene. The details are uknown and unimportant to the client. This        is server-side processing
    - Once the food is delivered, the client has to cut the steak, put salad dressing on the            salad, and spoon it into his mouth. This is client-side processing

- The server and the cook handle multiple clients simultaneously

![image](https://user-images.githubusercontent.com/60888123/164217532-e642a55d-d42c-4969-993c-6e5a960d3601.png)

#### Components of a Web Application
Client:
- HTML, CSS, JavaScript (work together to create a website) (JavaScript runs on the browser)

Server:
- PHP, Java, ASP.NET, Ruby, Python, Node (Choose one) (Java runs on the server)
 
Databse:
- SQL (MySQL, PostgreSQL, SQLite, SQLServer, Oracle, DB2)
- No SQL (Mongo, Couch, IndexDB)

Communication:
- GET, POST, ECHO, AJAX, JSON

Libraries, API's and Frameworks
- Client - JQuery (for Javascript), Dojo (mostly for GIS), Bootstrap (lot of CSS)

Mapping Components:
- Google Maps, Leaflet, OpenLayers, ESRI Javascript API, Turf.js, PostGIS

### Client Side
In terms of the Web, client means browser
- Netscape, Chrome, Firefox, Safari, Internet Explorer, Edge, Opera, "Webkit"

All browsers understand HTML, CSS, Javascript
- Minor differences in how they are implemented and supported, especially IE

HTML = Hyper Text Markup Language
- Provides structure and content
- Original web technology

CSS = Cascading Style Sheets
- Makes things pretty
- Colors, borders, positioning etc.

JavaScript - Programming Language
- Makes things happen
- Respond to user input, calculations, animations
- NOT Java

QUIZ:
1. In web development client refers to: a browser
2. In client-server architecture, which do you have more of, clients or servers? Clients
3. Which technology is used for communicating between client and server? AJAX
4. Which technology allows you to store spatial data in a text-based format? GeoJSON
5. In client-server architecture, user input occurs on the client.

Click here for all of the powerpoint presentation: [GeospatialWeb101.pptx](https://github.com/angelevr/GIS.github.io/files/8521054/GeospatialWeb101.pptx)

