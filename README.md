# Java-4.26-Task2
implement a packaging helper tool for your company to estimate how many boxes can be put into a container
The boxes are instances of classes which form a
class hierarchy. This hierarchy can be described as follows:
• Each Box has a width, height and depth.
• Each Box has a method getVolume to query the volume of the box.
• The Box class counts the boxes already instantiated in an attribute count and has a method getCount
to query this value. getCount can be used without an instance of Box.
• There is no possibility to make an instance of Box.
• Your company only uses two predefined basic box sizes:
– A BigBox has width 10, height 5 and depth 5.
– A SmallBox has width 3, height 2 and depth 1.
• Both BigBox and SmallBox are a Box.
• The SmallBox has a method addExtention(int addHeight), which increases its height by
addHeight. There can only be one extension at a time. As your company has only small box extensions
with an additional height of 1 and 2, only these values are accepted to increase height. For all other values,
the method does nothing.
• The SmallBox has a method removeExtention(), which removes the current height extension
of the box.
All size data of a Box is stored as variables of type int. For all other variables, use appropriate data types.
With this information, you have to implement the classes using best object oriented programming practices.
