# Mermaid

## Flow Chart Left to Right

**Sample Code**
````
``` mermaid
flowchart LR
    A-- Hlo -->B
    A-->C
    B-->D
    C-->D
    D-->E 
```
````

**Output**

![](mermaid1.png)

## Flow Chart Top to Bottom

**Sample Code**

````
```mermaid
---
title: Flowchart
---
flowchart TD
    Christmas -- Get money -->B(Go shopping)
    B --> C{Let me think}
    C -- One --> D[Laptop] 
    C -- Two -->E[iPhone]
    C -- Three --> F[Car]
    style Christmas fill:red,stroke:white
    style B fill:green,stroke:white
    style C fill:green,stroke:white
```
````

**Output**

![](mermaid2.png)

## Pie Chart

**Sample Code**

````
``` mermaid
pie 
    title Pie Chart
    "Words" : 7
    "Voice Tone" : 38
    "Body Language" : 55
%%{init: { 'themeVariables': { 'pie1': 'red', 'pie2': 'yellow', 'pie3': 'blue'}}}%%   
```
````

**Output**

![](mermaid3.png)

## Mindmap

**Sample Code**

````
``` mermaid
mindmap
        A
            B
                C
            D
            E
                X
                Y
```
````

**Output**

![](mermaid4.png)

## Mindmap

**Sample Code**

````
``` mermaid
mindmap
  root((mindmap))
    Origins
      Long history
      Popularisation
        British popular psychology author Tony Buzan
    Research
      On effectiveness<br/>and features
      On Automatic creation
        Uses
            Creative techniques
            Strategic planning
            Argument mapping
    Tools
      Pen and paper
      Mermaid
```
````

**Output**

![](mermaid5.png)

## Timeline

**Sample Code**

````
```mermaid
timeline
    title History of Social Media Platform
    2002 : LinkedIn
    12 feb 2004 : Facebook
         : Google
    2005 : Youtube
    2006 : Twitter
```
````

**Output**

![](mermaid6.png)

## XY Chart 

**Sample Code**

````
```mermaid
xychart-beta
    title "Revenue Chart"
    x-axis [January,February,March,April]
    y-axis "Revenue" 4000 --> 10000
    bar [5000, 6000, 7500, 10000]
    line [5000, 6000, 7500, 10000]
```
````

**Output**

![](mermaid7.png)

**Note: The given syntax is for Github only. In live editor, don't use ```` ```mermaid ``` ````. Just type the code directly.**

