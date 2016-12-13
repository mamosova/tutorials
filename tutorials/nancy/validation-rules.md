---
title: Add a map display to your app
description: Add a map to your app and geolocate a street address
tags: [  tutorial>beginner, topic>sapui5, products>sap-hana-cloud-platform, products>sap-web-ide ]
---

## Prerequisites  
 - [Add an XML fragment for a tab in your app](http://www.sap.com/developer/tutorials/teched-2016-6.html)


## Next Steps
 - [Translate your app into multiple languages](http://www.sap.com/developer/tutorials/teched-2016-8.html)


## Details
### You will learn  
You will add a map display to one of the tabs in your app and geolocate an address associated with the item selected in the master (or list) view.


### Time to Complete
**15-20 Min**.

---
[ACCORDION-BEGIN [Step 1: ](Read about Google Static Maps API)]

<!-- [VALIDATE_1]-->



The Static Maps API returns an image that you can display in a HTML image tag.   

[DONE]
[ACCORDION-END]

[ACCORDION-BEGIN [Step 2: ](Create a Destination for the API)]
In order to use the Google Maps API, you need to create a new destination in HCP for your application.

Log into [SAP HANA Cloud Platform](https://account.hanatrial.ondemand.com) by opening the following URL in a new tab: https://account.hanatrial.ondemand.com


Enter the following field values.

|Field Name     | Value                                  |
|---------------|----------------------------------------|
|Name           | `GoogleMaps`                           |
|Type           | `HTTP`                                 |
|Description    | `Google Maps API`                      |
|URL            | `https://maps.googleapis.com/maps/api` |
|Proxy Type     | `Internet`                             |
|Authentication | `NoAuthentication`                     |

Leave the **Use default JDK truststore** checked

And add the following **Additional Properties** below by clicking on the **New Property** button once for each property.

|Field Name      | Value  |
|----------------|--------|
|`WebIDEEnabled` | `true` |
|`WebIDESystem`  | `API`  |

Click on **Save**.

After the destination is saved, you can click the **Check Connection** button to test that Google Maps end-point is reachable.

[DONE]
[ACCORDION-END]

[ACCORDION-BEGIN [Step 3: ](Update the neo-app.json)]

First let's _re-open_ the **SAP Web IDE**.

From your [SAP HANA Cloud Platform cockpit](https://account.hanatrial.ondemand.com/cockpit), in the left-hand navigation bar, select **Services** and then click on the **SAP Web IDE** tile.

In the **SAP Web IDE** overview page, click **Open SAP Web IDE**.

Copy the following code and paste it after the last route. **Save** your changes.

```
,
{
  "path": "/GoogleMaps",
  "target": {
    "type": "destination",
    "name": "GoogleMaps",
    "entryPath": "/"
  },
  "description": "Google Maps API"
}
```
> note, this is my test



[DONE]
[ACCORDION-END]

## Next Steps
 - [Translate your app into multiple languages](http://www.sap.com/developer/tutorials/teched-2016-8.html)
