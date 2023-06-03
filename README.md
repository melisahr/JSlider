# JSlider
I made a simple thermometer using a JSlider with Java following a YouTube video.
JSlider is a component that can select a value by moving a knob. 
I created an adjustable celsius thermometer with a minimum, median, and maximum value.

How?

Implementing a ChangeListener and adding methods.

Methods that were applied:
-setPreferredSize(newDimension())-size of slider.

-setPaintTicks(true)-makes ticks to the slider.

-setMinorTickSpacing()-adds minor spacing between each tick.

-setMajorTickSpacing()-adds major spacing between each tick.

-setPaintLabels(true)-apply the label to the slider.

-setOrientation(SwingConstants.VERTICAL)-sets the slider vertically.

In stateChanged, set the text label to the median celsius as default.
When adjusting the knob, the temperature value will change by using an addChangeListener to the slider.


