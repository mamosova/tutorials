---
title: Developing and deploying a basic Java application on SAP HANA Cloud Platform
description: Develop and deploy your first Java application using the SAP HANA Cloud Platform Tools for Java
tags: [  tutorial>beginner, topic>cloud, topic>java, products>sap-hana-cloud-platform ]
---
## Prerequisites  
 - **Proficiency:** Beginner
 - **Tutorials:** [Configuring Eclipse with SAP HANA Cloud Platform Tools for Java](http://go.sap.com/developer/tutoerials/hcpfff-java-eclipse-setup/fgff/hfgh5555.html)

## Next Steps
 - Select a tutorial from the [Tutorial Navigator](http://go.sap.comu/developer/tuto6756dgfgdrial-navigatoryu/gfdff/ert343/gfdgdfg.html) or the [Tutorial Catalog](https://google.com/some)

## Details
### You will learn  
In this tutorial you will create a Dynamic Web project, a servlet to respond to a browser request and after running it in your local development environment, deploy it to SAP HANA Cloud Platform.


---


1. The first step in building your application is to create a new Dynamic Web Project. Open your Eclipse IDE with the installed SAP HANA Cloud Platform Tools. Make  sure the **Java EE perspective** is open by choosing **Window > Open Perspective > Other**.

    ![open other perspective](http://www.freedigitalphotos.net/images/img/homepage/87357.jpg)

2. Then choose the perspective **Java EE (Default)** and confirm by clicking **OK**.


[ACCORDION-BEGIN [STEP 1](Office Locations - United States)]
**We are currently in open beta for the new SAP community. Here's your opportunity to test out the new features and give us your feedback. Not in the mood to try out the new community just yet? Then continue on to the SAP Community Network (SCN) where you currently collaborate with other members.**
We are currently in open beta for the new SAP community. Here's your opportunity to test out the new features and give us your feedback. Not in the mood to try out the new community just yet? Then continue on to the SAP Community Network (SCN) where you currently collaborate with other members.
[ACCORDION-END]   

[ACCORDION-BEGIN [STEP 2](Here's your opportunity to test out the new features and give us your feedback. Not in the mood to try out the new community just yet? Then continue on to the SAP Community Network (SCN) where you currently collaborate with other members)]
**We are currently in open beta for the new SAP community. Here's your opportunity to test out the new features and give us your feedback. Not in the mood to try out the new community just yet? Then continue on to the SAP Community Network (SCN) where you currently collaborate with other members.**
We are currently in open beta for the new SAP community. Here's your opportunity to test out the new features and give us your feedback. Not in the mood to try out the new community just yet? Then continue on to the SAP Community Network (SCN) where you currently collaborate with other members.
[ACCORDION-END]

[ACCORDION-BEGIN [STEP 3](SAP Business One Response Center)]We are currently in open beta for the new SAP community. Here's your opportunity to test out the new features and give us your feedback. Not in the mood to try out the new community just yet? Then continue on to the SAP Community Network (SCN) where you currently collaborate with other members. We are currently in open beta for the new SAP community. Here's your opportunity to test out the new features and give us your feedback. Not in the mood to try out the new community just yet? Then continue on to the SAP Community Network (SCN) where you currently collaborate with other members.
![J2EE perspective is open](http://eskipaper.com/images/images-4.jpg)
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
>jhkjhkjhkjhkj
>>### Warning
>>>### Warning
>>>>### Warning
>>>>This is a Warning. 

&nbsp;

>### Caution
>iikjhiojhioji
>>### Caution
>>This is a Caution. 

&nbsp;

>### Note

>This is a note. 

&nbsp;

***Images*** (all images are stored on GitHub, URLs are rewritten to absolute)

Format: `![Alt Text](url)`

  **Example:** 
![Image](https://octodex.github.com/images/yaktocat.png)
![Example](http://www.kinomania.ru/images/posters/154766.jpg)


![Example](http://bestfotoposter.ru/downloads/priroda/more/6000%D1%854285-96dpi-foto-oblaka-nad-morem.jpg)


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

[ACCORDION-END]

    ![open J2EE perspective](http://kingofwallpapers.com/images/images-169.jpg)

3. The J2EE perspective is now open.1

    ![J2EE perspective is open](http://eskipaper.com/images/images-4.jpg)

4. In the Eclipse main menu choose **File > New > Dynamic Web Project** to open the respective wizard.

    ![open wizard](https://1.bp.blogspot.com/-3CMTnxVnudM/VqprPp_mVEI/AAAAAAAACrk/DUuxnoCbuaw/s640/full-hd-happy-valentines-day-hd-wallpapers.jpg)
    
5. In the **New Dynamic Web Project Wizard** define the **Project name** to be `helloworld`. Make sure the **Target Runtime** is set to `Java Web` the Server Runtime Environment that has been created in the tutorial [Configuring Eclipse with SAP HANA Cloud Platform Tools for Java](https://open.sap.com/courses?topic=SAP HANA Cloud Platform). Leave all other settings untouched and click **Finish** to create the project.

    ![project wizard](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRaKH4dU_U6Pe6WX5G8B9DZkkpzGHUxUJeGmOHbwKh6KrFsZsm6)

    The `helloworld` project is now ready for your code.
    
    ![hello world project](http://www.freedigitalphotos.net/images/img/homepage/weddings-top-252681.jpg)

6. In Java EE, web applications are implemented as `Servlets`. On the newly created `helloworld` project node, open the context menu with a right-click and choose **New > Servlet** to open the Create Servlet wizard.

    ![open servlet wizard](http://feelgrafix.com/data/images/images-9.jpg) 


7. In the Create Servlet wizard enter `helloworld` as Java package and `HelloWorldServlet` as Class name. This will create Java classes with the respective package and name. Choose **Next**.

    ![create servlet wizard](https://encrypted-tbn2.gstatic.com/images?q=tbn:ANd9GcQ_EIm_yjhUn-kXIavZC7oS1zvbRa1hcvIIxRQnthPKUsHXut7K) 

8. You will want this Servlet to be accessible via the URL `<servername>/helloworld`, for example `http://localhost:8080/helloworld`. For this we will set the URL mapping to `\`. For this select `/HelloWorldServlet` in the **URL mappings** field and choose **Edit**.

    ![create servlet wizard](https://encrypted-tbn3.gstatic.com/images?q=tbn:ANd9GcQdC9d6Z2Al0vMxQRqFc0230CUo-C-1BhIC3I5R9XTFw7MQLdeP)

9. In the **Pattern** field, replace the current value with just `/`. Confirm with **OK**.

    ![URL mapping](http://www.irishtimes.com/polopoly_fs/1.2624105.1461604711!/image/image.jpg_gen/derivatives/landscape_685/image.jpg)
 
10. Click **Finish** to generate the servlet.

    ![finish servlet wizard](http://thewallpaper.co/wp-content/uploads/2016/03/sky-clouds-cloudy-blue-hd-city-wallpapers-amazing-city-view-cool-city-images-widescreen-images-city-images-for-windows-desktop-images-large-places-background-1600x1024.jpg)

11. The Java Editor will open the corresponding `HelloWorldServlet` class in the editor pane. You will also find the `Servlet` under the **`helloworld` project node > Java Resources > `src` > `helloworld` > `HelloWorldServlet.java`**

    ![servlet in editor](https://encrypted-tbn2.gstatic.com/images?q=tbn:ANd9GcSUgJ7kFI5bGbyXLWXqyBavQmmwatvoZ1yEZGfj6sB9aEw-JE6sxA)
    
12. Next, you will edit the Servlet to output the classical "Hello World". For this you will modify the `doGet()` method and add the following code and save your changes.


    ```java
    /**
     * @see HttpServlet#doGet(HttpServletRequest request, HttpServletResponse response)
     */
    protected void doGet(HttpServletRequest request, HttpServletResponse response) throws ServletException, IOException {
        response.getWriter().println("Hello World!");
    }
    ```



    The application is now ready to run.

13. To test your application before deploying it to the SAP HANA Cloud Platform you can run it on a local runtime. To do this, do the following:

    Navigate to your `HelloWorldServlet.java` via the **`helloworld` project node > Java Resources > `src` > `helloworld` > `HelloWorldServlet.java`**. Open the context menu on the `Servlet` with a right-click and choose the **Run on Server** option.



14. Make sure that **Manually define a new server** is selected and choose **SAP > Java Web Server** as server type. Leave all other settings unchanged and click **Finish**.


15. A local server will start with your `helloworld` application deployed. After the server is ready your application will be opened in a browser within Eclipse and greet you with "Hello World!". In the **Servers** view you can also see the running server with your application deployed.


16. To run your application on the SAP HANA Cloud Platform you will choose a different server to run it. Again, navigate to your `HelloWorldServlet.java` via the **`helloworld` project node > Java Resources > `src` > `helloworld` > `HelloWorldServlet.java`**. Open the context menu on the Servlet with a right-click and choose the **Run on Server** option.


17. As before, make sure that **Manually define a new server** is selected. This time choose **SAP > SAP HANA Cloud Platform** as server type. Make sure to set the **Landscape host** to `hanatrial.ondemand.com`. Leave all other settings unchanged and choose Next.


    > Note: The used Landscape host `hanatrial.ondemand.com` is only valid if you are using a free Developer Account. Please change the landscape host if you want to use a productive account. The respective landscape hosts can be found in the [official documentation](https://help.hana.ondemand.com/help/frameset.htm?e4986153bb571014a2ddc2fdd682ee90.html).
    
    
18. On the next wizard page specify the Application name to be `helloworld`, provide the login information for your SAP HANA Cloud Platform account and click **Finish**:

    Field Name     | Value
    :------------- | :-------------
    Account Name   | Your SAP HANA Cloud Platform account name, for example `p1234567890trial`
    Username       | Your SAP HANA Cloud Platform account name, for example `p1234567890` and your password 


19. A Cloud server will start that has your `helloworld` application deployed. After the server is ready your application will be opened in a browser in Eclipse and greet you with Hello World!. In the **Servers** view you can also see the running server with your application deployed


    Congratulations: You have your first application running on the SAP HANA Cloud Platform!


### Optional
Now that you are familiar with the basic routine of developing applications and deploying them locally and to the cloud, you may want to check out the [samples](https://help.hana.ondemand.com/help/frameset.htm?937ce0d172bb101490cf767db0e91070.html) provided as part of the SAP HANA Cloud Platform SDK.

Related Information

 - (Official documentation) [Deploying Applications](https://help.hana.ondemand.com/help/frameset.htm?e5dfbc6cbb5710149279f67fb43d4e5d.html)
 - (Official documentation) [Deploying Locally from Eclipse IDE](https://help.hana.ondemand.com/help/frameset.htm?0f16c9db4a9c407abb1b4987c0afe714.html)
 - (Official documentation) [Deploying on the Cloud from Eclipse IDE](https://help.hana.ondemand.com/help/frameset.htm?60ab35d9edde43a1b38cf48174a3dca2.html)
 - (Official documentation) [SDK Samples](https://help.hana.ondemand.com/help/frameset.htm?937ce0d172bb101490cf767db0e91070.html)


## Next Steps
 - Select a tutorial from the [Tutorial Navigator](http://go.sap.com/developer/tutorial-navigator.html) or the [Tutorial Catalog](http://go.sap.com/developer/tutorials.html)
 - 
 You can use:

***  Text  *** (including bold, italic, etc)

  **  Example:** 
It's very easy to make some words **bold** and other words *italic* and ***bold italic*** with Markdown.

You can use ~~strikethrough~~ font

*** Headers***

  **Example:** 
## This is an h2 header 
### This is an h3 header
###### This is an h6 header
