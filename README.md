SSD.js
=========

> Sudan Special Day's 

A simple jQuery Ribbon library , it will Display a ribbon in  a [left | right] corner of your web site.
The ribbon will display in a specific Day , with a specific Message.

## day's and message's
01/01 == "عيد استقلال مجيد"
First day of Ramadan until the last day == "رمضان كريم "  
First day of aid al Fetr until the 4th Day == "عيد سعيد"
First day of aid al audheya until the 4th Day == "عيد مبارك"
First Day of Hijri year =="عام هجري سعيد "

> TO triggering the hijri date I'm using Al adhan REST UP api


Check out this [demo page](http://shakir-abdo.github.io/SSD/ "Demo")

## Installation

Dependency: [jQuery](http://jquery.com).

Download ssd.min.js:
- from [Github](http://shakir-abdo.github.io/SSD/)

Usage
-----

To make a normal ribbon without events  , use `ssd(text, options)`. Examples :

    ssd('BETA 2');
    ssd('New version', {color: 'red', position: 'left'}); // please use a `hex` color value to make a nice gradient in ribbon , other wise it will return a normal color without gradient.

To displays he ribbon in Event's days , simply use `events` option .
> the event's list:
- `ramadan` for Ramadan. 
- `aidF` for aid al fetr. 
- `aidA` for aid al audheya. 
- `indepen` for Sudan Independence Day. 
- `hijriE` for hijri new year.

### NOTE!!
you must include the ssd.css file in your web page to styling your ribbon
`<link rel="stylesheet" href="ssd.css" type="text/css" />`

By **Shakir Abdo**
