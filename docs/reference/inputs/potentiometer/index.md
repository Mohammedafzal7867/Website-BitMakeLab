### Potentiometer
A potentiometer provides an analogue input, which means that it can provide a range of input values, not just 0 and 1 like a digital input like a button.

Use it to control things you want to vary over a range of values, such as the speed of a motor, the intensity of a light and much more!

![Potentiometer](potentiometer.jpg)

#### Wiring
Use a GVS cable to connect the sensor.  This has 3 wires, blue, red and black:

![GVS cable](../../assets/gvs-cable.jpg){ width=400 }

Wire up as follows, using the Edge Connector or Motor Controller board:

|Potentiometer   | Microbit             |
| :-------------- | :------------------  |
|3-pin connector  | P0 3-pin connector   |

![Wiring](wiring.png){ width=600 }

You don't have to use pin P0.  You can use any <a href="assets/pins-short.png" target="_blank">analogue pin</a>.  Just remember to adjust your code accordingly.

#### Coding

Enter this code in **forever**:

![Code](code-serial-out.png)

The Serial blocks can be found in Advanced.

Download the code to the microbit.

To see the data, click on Show data Device:

![Show Data](show-data.png)

You should see some numbers and a graph. These show the position of the potentiometer knob.  Rotate the knob and watch the values change:

![Data](data.png)

You can use these values to control other things.  For example, in the code below, we can use this to control the bar graph function of the Microbit:

![Bar graph](code-bar-graph.png)

In the above code, the **map** block takes the potentiometer value, which is in the range 0 to 1023, and uses it to plot a bar chart on the LED display:

![Bar graph](potentiometer.gif)

<br/>
