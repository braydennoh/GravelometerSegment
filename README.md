# Gravelometer Segment
Testing how well Segment Anything (SA) detects gravel size ranges (180 mm~22.6 mm) from 5 m to 10 m distance.

### raw images
![](https://github.com/snohatech/gravelometersegment/blob/main/raw/raw.gif)

### masked images
![](https://github.com/snohatech/gravelometersegment/blob/main/masked/mask.gif)

### 5 meters
![](https://github.com/snohatech/gravelometersegment/blob/main/segment/5m.gif)

### 6 meters
![](https://github.com/snohatech/gravelometersegment/blob/main/segment/6m.gif)

### 7 meters
![](https://github.com/snohatech/gravelometersegment/blob/main/segment/7m.gif)

### 8 meters
![](https://github.com/snohatech/gravelometersegment/blob/main/segment/8m.gif)

### 9 meters
![](https://github.com/snohatech/gravelometersegment/blob/main/segment/9m.gif)

### 10 meters
![](https://github.com/snohatech/gravelometersegment/blob/main/segment/10m.gif)

### Segment Anything accuracy plot
SA becomes less accurate with smaller area. This also means that even if the segmentation isn't correct, SA will still provide a number for accuracy. However, based on my eyes, if the segmentation isn't correct, I gave a 0. 

![](https://github.com/snohatech/gravelometersegment/blob/main/data/accuracyfull.png)

![](https://github.com/snohatech/gravelometersegment/blob/main/data/accuracy.png)
