# Gravelometer Segment
Testing how well Segment Anything (SA) detects gravel size ranges (180 mm~22.6 mm) from 5 m to 10 m distance.

### raw images
![](https://github.com/snohatech/gravelometersegment/blob/main/raw/raw.gif)

### masked images
![](https://github.com/snohatech/gravelometersegment/blob/main/masked/mask.gif)

### 5 meters
![](https://github.com/snohatech/gravelometersegment/blob/main/segment/5m.gif | width=100)

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

### Results
180 mm gets segmented to 10 m.
128 mm fails at 9 m.
90 mm fails at 8 m. 
64 mm fails at 8 m.
45 mm fails at 7 m.
32 mm fails at 6 m.
22.6 mm fails at 6 m.

### Conclusion
Looking at gravel with Segment Anything and a conventional camera past 10 m is impractical. 
