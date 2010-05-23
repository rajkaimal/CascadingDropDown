
CascadingDropDown : a jQuery plugin, version: 0.2 (2010-05-21)
@requires jQuery v1.4 or later

CascadingDropDown is a jQuery plugin that can be attached to a select list to get automatic population. 
Each time the source element changes value, an ajax request is made to retrieve a list of values for 
the select list. The respose from the ajax request should be in json with the following format

   [{
       "Text": "John",
       "Value": "10326"
   },
   {
       "Text": "Jane",
       "Value": "10801"
   }] 


Licensed under the MIT:
http://www.opensource.org/licenses/mit-license.php

Raj Kaimal http://weblogs.asp.net/rajbk/

v 0.2 Added support for custom postData using functions
