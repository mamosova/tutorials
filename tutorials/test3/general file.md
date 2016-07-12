---
title: general file
description: example
tags: [tutorial:product/sapHana, tutorial:product/hana_studio]
qrcode: true
---

```markup
    <?xml version="1.0" encoding="UTF-8"?>
    <web-app xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns="http://java.sun.com/xml/ns/javaee" xsi:schemaLocation="http://java.sun.com/xml/ns/javaee http://java.sun.com/xml/ns/javaee/web-app_2_5.xsd" id="WebApp_ID" version="2.5">
    <display-name>cloud-weatherapp</display-name>
    <welcome-file-list>
    <welcome-file>index.html</welcome-file>
    </welcome-file-list>
    <servlet>
    <display-name>HelloWorldServlet</display-name>
    <servlet-name>HelloWorldServlet</servlet-name>
    <servlet-class>
        com.sap.hana.cloud.samples.weatherapp.web.HelloWorldServlet
    </servlet-class>
    </servlet>
    <servlet-mapping>
    <servlet-name>HelloWorldServlet</servlet-name>
    <url-pattern>/hello</url-pattern>
    </servlet-mapping>
    <login-config>
    <auth-method>FORM</auth-method>
    </login-config>
    <security-constraint>
    <web-resource-collection>
        <web-resource-name>Protected Area</web-resource-name>
        <url-pattern>/*</url-pattern>
    </web-resource-collection>
    <auth-constraint>
        <!-- Role Everyone will not be assignable -->
        <role-name>Everyone</role-name>
    </auth-constraint>
    <?xml version="1.0" encoding="UTF-8"?>
    <web-app xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns="http://java.sun.com/xml/ns/javaee" xsi:schemaLocation="http://java.sun.com/xml/ns/javaee http://java.sun.com/xml/ns/javaee/web-app_2_5.xsd" id="WebApp_ID" version="2.5">
    <display-name>cloud-weatherapp</display-name>
    <welcome-file-list>
    <welcome-file>index.html</welcome-file>
    </welcome-file-list>
    <servlet>
    <display-name>HelloWorldServlet</display-name>
    <servlet-name>HelloWorldServlet</servlet-name>
    <servlet-class>
        com.sap.hana.cloud.samples.weatherapp.web.HelloWorldServlet
    </servlet-class>
    </servlet>
    <servlet-mapping>
    <servlet-name>HelloWorldServlet</servlet-name>
    <url-pattern>/hello</url-pattern>
    </servlet-mapping>
    <login-config>
    <auth-method>FORM</auth-method>
    </login-config>
    <security-constraint>
    <web-resource-collection>
        <web-resource-name>Protected Area</web-resource-name>
        <url-pattern>/*</url-pattern>
    </web-resource-collection>
    <auth-constraint>
        <!-- Role Everyone will not be assignable -->
        <role-name>Everyone</role-name>
    </auth-constraint>
    <?xml version="1.0" encoding="UTF-8"?>
    <web-app xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns="http://java.sun.com/xml/ns/javaee" xsi:schemaLocation="http://java.sun.com/xml/ns/javaee http://java.sun.com/xml/ns/javaee/web-app_2_5.xsd" id="WebApp_ID" version="2.5">
    <display-name>cloud-weatherapp</display-name>
    <welcome-file-list>
    <welcome-file>index.html</welcome-file>
    </welcome-file-list>
    <servlet>
    <display-name>HelloWorldServlet</display-name>
    <servlet-name>HelloWorldServlet</servlet-name>
    <servlet-class>
        com.sap.hana.cloud.samples.weatherapp.web.HelloWorldServlet
    </servlet-class>
    </servlet>
    <servlet-mapping>
    <servlet-name>HelloWorldServlet</servlet-name>
    <url-pattern>/hello</url-pattern>
    </servlet-mapping>
    <login-config>
    <auth-method>FORM</auth-method>
    </login-config>
    <security-constraint>
    <web-resource-collection>
        <web-resource-name>Protected Area</web-resource-name>
        <url-pattern>/*</url-pattern>
    </web-resource-collection>
    <auth-constraint>
        <!-- Role Everyone will not be assignable -->
        <role-name>Everyone</role-name>
    </auth-constraint>
    <?xml version="1.0" encoding="UTF-8"?>
    <web-app xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns="http://java.sun.com/xml/ns/javaee" xsi:schemaLocation="http://java.sun.com/xml/ns/javaee http://java.sun.com/xml/ns/javaee/web-app_2_5.xsd" id="WebApp_ID" version="2.5">
    <display-name>cloud-weatherapp</display-name>
    <welcome-file-list>
    <welcome-file>index.html</welcome-file>
    </welcome-file-list>
    <servlet>
    <display-name>HelloWorldServlet</display-name>
    <servlet-name>HelloWorldServlet</servlet-name>
    <servlet-class>
        com.sap.hana.cloud.samples.weatherapp.web.HelloWorldServlet
    </servlet-class>
    </servlet>
    <servlet-mapping>
    <servlet-name>HelloWorldServlet</servlet-name>
    <url-pattern>/hello</url-pattern>
    </servlet-mapping>
    <login-config>
    <auth-method>FORM</auth-method>
    </login-config>
    <security-constraint>
    <web-resource-collection>
        <web-resource-name>Protected Area</web-resource-name>
        <url-pattern>/*</url-pattern>
    </web-resource-collection>
    <auth-constraint>
        <!-- Role Everyone will not be assignable -->
        <role-name>Everyone</role-name>
    </auth-constraint>
```

You can use:

***Text*** (including bold, italic, etc)

  **Example:** 
It's very easy to make some words **bold** and other words *italic* and ***bold italic*** with Markdown.

You can use ~~strikethrough~~ font

***Headers***

  **Example:** 
## This is an h2 header 
### This is an h3 header
###### This is an h6 header

***Lists***

  **Example:** 
  
Sometimes you want numbered lists:

1. One
2. Two 
3. Three

Sometimes you want bullet points:

* Start a line with a star
* Profit!

You can create nested lists: 

* item1
    * one_one
    * two

***Blockquotes***

  **Example:** 
In the words of Abraham Lincoln:
> Pardon my French

***Links***

  **Example:** 
[Primer] [id]:
[id]: http://tut.by

<http://tut.by>

<address@example.com>

***There are three different types of messages: Note, Caution and Warning.***

>### Warning
>Hello
>>### Warning
>>>### Warning
>>>>### Warning
>>>>This is a Warning. 

&nbsp;

>### Caution
>Hola
>>### Caution
>>This is a Caution. 

&nbsp;

>### Note

>This is a note. 

&nbsp;

***Images*** (all images are stored on GitHub, URLs are rewritten to absolute)

Format: 
&nbsp;
![Funny-Baby-11.jpg](Funny-Baby-11.jpg)

  **Example:** 
![Image](http://i.dailymail.co.uk/i/pix/2016/03/22/13/32738A6E00000578-3504412-image-a-6_1458654517341.jpg)
![Example](https://static.pexels.com/photos/69372/pexels-photo-69372-large.jpeg)


![Example](http://91ef69bade70f992a001-b6054e05bb416c4c4b6f3b0ef3e0f71d.r93.cf3.rackcdn.com/g-for-giraffe-10050248.jpg)


***Code blocks:***

```markup
 quit;
 !@#$%^&*&*(*(()_++|"}?><>??*&^%#!~~~~@33123-090=|"]?>{}|\\
  require 'redcarpet'
  markdown = Redcarpet.new("Hello World!")
  puts markdown.to_html
  exit;
```

```js
 quit;
 !@#$%^&*&*(*(()_++|"}?><>??*&^%#!~~~~@33123-090=|"]?>{}|\\
  require 'redcarpet'
  markdown = Redcarpet.new("Hello World!")
  puts markdown.to_html
  exit;
```

  **Example:** 
```javascript
quit;
function fancyAlert(arg) { function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) { 
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
function fancyAlert(arg) {
  if(arg) {
  20 line
  quit;
function fancyAlert(arg) { function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) { 
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
function fancyAlert(arg) {
  if(arg) {
  40 line
  quit;
function fancyAlert(arg) { function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) { 
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
function fancyAlert(arg) {
  if(arg) {
  60 line
  quit;
function fancyAlert(arg) { function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) { 
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
function fancyAlert(arg) {
  if(arg) {
  60 line
  quit;
function fancyAlert(arg) { function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) { 
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
function fancyAlert(arg) {
  if(arg) {
  80 line
  quit;
function fancyAlert(arg) { function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) { 
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
function fancyAlert(arg) {
  if(arg) {
  100 line
  quit;
function fancyAlert(arg) { function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) { 
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
function fancyAlert(arg) {
  if(arg) {
  120 line
  quit;
function fancyAlert(arg) { function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) { 
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
function fancyAlert(arg) {
  if(arg) {
  140 line
  quit;
function fancyAlert(arg) { function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) { 
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
function fancyAlert(arg) {
  if(arg) {
  160 line
  quit;
function fancyAlert(arg) { function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) { 
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
function fancyAlert(arg) {
  if(arg) {
  160 line
  quit;
function fancyAlert(arg) { function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) { 
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
function fancyAlert(arg) {
  if(arg) {
  180 line
  quit;
function fancyAlert(arg) { function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) { 
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
function fancyAlert(arg) {
  if(arg) {199
```
***Task Lists*** (Please note, this requires empty line before task list):

  **Example:** 
  
- [x] @mentions, #refs, [links](), **formatting**, and ~~tags~~ supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

***Tables:***

  **Example:** 

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column


and

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |
