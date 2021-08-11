# Local Storage


Cookies:
Cookies on web applications can be used for persistent local storage of small amounts of data. However, they have 3 dealbreaking downsides:

1. Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the ame data over and over.

2. cookies are included with every HTTP request, thereby sending data unencyprted over the internet.

3. cookies are limited to abut 4KB of data. This is enough to slow down your application, but not enought to be useul.

## History of local storage
Userdata allows web pages to store up to 64 KB of data perdomain in a hierarchical XML-based structure. 

## HTML5 Storage
(DOM Storage)
HTML5 storage is a way for web pages to store key.value pair locally, within the client web browser. Like cookies, this data persists even after you navigate away from the website, close your browser tab, exit your browser, or whatever else you do to exit the page.

This data is never transmitted to the remote web server. 


## Using HTML5 storage 
HTML5 storage is based on name key/value pairs. you store data based on a name key, then you can retireve that data with the same key. **The named key is a string.** (usernames and passwords for example).

The data can be any type supported by JS, including strings, booleans, integers, of floats. However, the data is actually stored as a string.

If you are storing or retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() to coerce your retireved data into the expected JS datatype.
