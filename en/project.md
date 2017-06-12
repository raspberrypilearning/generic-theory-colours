--- step ---
---
title: Representing colours with numbers
---
The colour of an object depends on the light that is reflected off it or the light that it emits. The various colours of light can be seen in the diagram below. You might recognise this as the colours of the rainbow.

![spectrum](https://upload.wikimedia.org/wikipedia/commons/thumb/d/d9/Linear_visible_spectrum.svg/1024px-Linear_visible_spectrum.svg.png)

Humans see colour because of the cells in their eyes. These cells are called *cones*. We have three types of cones - red, blue and green. So all the colours that we see are therefore just mixtures of the colours red, blue and green.

Computers store everything as 1s and 0s. These 1s and 0s are often organised into sets of 8, called a **byte**

*[bytes]: A set of 8 bits - 10011001

A single byte can represent any number from 0 up to 255.

As humans can only see combinations of the colours red, green and blue, when we want to represent colours in computer programs, the amount of each of the three colours is usually stored as a single byte and therefore a number between 0 and 255.

Here's a table showing some colour values

| Red | Green | Blue | Colour    |
|-----|-------|------|-----------|
| 255 |     0 |    0 | Red       |
|   0 |   255 |    0 | Green     |
|   0 |     0 |  255 | Blue      |
| 255 |   255 |    0 | Yellow    |
| 255 |    10 |  180 | Hot Pink  |
| 210 |   105 |   30 | Chocolate |
--- /step ---
