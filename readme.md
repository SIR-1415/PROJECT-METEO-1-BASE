# Project METEO 1 #
This document introduces 

## Goals ##
1. design a very basic *HTML* form
2. process data form with a *php* script
3. consume a API service from *php*
4. parse *XML* and/or *JSON* with *php*
5. use php to dynamically generate *HTML* content

## Languages ##
+ HTML
+ PHP
+ JSON
+ XML
+ CSS

### Step 0 ###

+ Go to https://developer.worldweatheronline.com/ and register for a new acount.
+ Get a Free API key.
+ Explore the API. Syudy both the *JSON* and *XML* formats.

### Step 1 ###

FILE : *getmeteo.html*
> This file should have a HTML form with an input text and a submit and reset button. The form should use *GET* as method to send data to the server. The input text form field should be named *location*. By now you should configure *dump.php* as the *action* to process the script.

FILE : *dump.php*
> This file should write a *dump* of the values that are received as form fiels via the *GET* and *POST* methods in PHP.

TEST :
> Test the *dump.php* either with URL encoded data either with the *getmeteo.html*.

### Step 2 ###
STUDY : *file_get_contents()* and *cURL*
> notice that: *file_get_contents()* is a handy function to make *GET* requests and grab the response in a string.
> notice that: cURL is much more powerful library able to communicate with servers under different types of internet protocols.
STUDY : *SimpleXML* php API
> how to instantiate an object.
> how to search / navigate

STUDY : *json_encode* and *json_decode()* functions.



### Step 3 ###






