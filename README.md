# d3seq
Simple DNA Sequence + Annotation display widget using javascript / D3

__Usage__

1. create container element:
  ```<div id='containerElementID'></div>```

2. initialize sequence display in javascript block:
  ```
seqdisplay.init('containerElementID');
seqdisplay.load(sequence, features);
```

Where ``sequence`` is a string with a DNA sequence (single-letter code).

Features should look like this:
```
[
 { 'name': "name",
   'color': "#FFFFFF",
   'start': 1,
   'end': 100,
   'strand' : 1,
   'type' : "CDS" },
]
```
