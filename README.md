# INTERACTIVE MAP OF NIGERIA
INIGMap in an Interactive map of nigeria

## Features:
- can add pin to locate a capital
- hover
- clickable
- outline
- dynamic title, description for states
- url links 
- html tags for states description on hover

## DOCUMENTATION

### HOW TO USE
Initialize the necessary files:
```
<link rel="stylesheet" type="text/css" href="custom.min.css">

<script type="text/javascript" src="jquery.js"></script>
<script type="text/javascript" src="nigeria-min.js"></script>
```
#### Call the Interactive Map function after the page has loaded

- Simple initialization
```
NiMap('containerId');
```

- Advance initialization
```
NiMap(
'containerId',  
{
 config:[
      {
        state:1,
        hover: "ABIA",
        url: "#",
        target: "same_window",
        upColor: "#FFFFF3",
        overColor: "#ECFFB3",
        downColor: "#cae9af", 
      }
 ],
 pins_config:[
      {
        state:1,
        shape: "square",
        hover: "<b><u>Abia</u></b><br>Write any text and load images<br><img src='assets/example.png'>",
        x: 300, 
        y: 308,
        size: 18,
        outline: "#000080",
        upColor: "#1a1aff",
        overColor: "#66d9ff",
        url: "#",
        target: "new_window",
      }
 ],
});
```

> state in config is the number of the state on the map, all state has number. state is required to use a config.
> the pins_config add extra layer on a state. However state is the only required value on any config

### States number
- >  1.Abia
- >  2.Adamawa
- >  3.Akwa Ibom
- >  4.Anambra
- >  5.Bauchi
- >  6.Bayelsa
- >  7.Benue
- >  8.Borno
- >  9.River
- >  10.Delta
- >  11.Ebonyi
- >  12.Edo
- >  13.Ekiti
- >  14.Enugu
- >  15.Gombe
- >  16.Imo
- >  17.Jigawa
- >  18.Kaduna
- >  19.Kano
- >  20.Katsina
- >  21.Kebbi
- >  22.Kogi
- >  23.Kwara
- >  24.Lagos
- >  25.Nasarawa
- >  26.Niger
- >  27.Ogun
- >  28.Ondo
- >  29.Osun
- >  30.Oyo
- >  31.Plateau
- >  32.Rivers
- >  33.Sokoto
- >  34.Taraba
- >  35.Yobe
- >  36.Zamfara
- >  37.Abuja


 <a href='https://saidabdul80.github.io/INIGMap/demo.html'>.github.io demo</a>

