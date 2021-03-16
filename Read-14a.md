# CSS Transforms, Transitions, and Animations

## Transforms
##### The transform property comes in two different settings, two-dimensional and three-dimensional. Each of these come with their own individual properties and values.

### Transform Syntax
##### The actual syntax for the transform property is quite simple, including the transform property followed by the value. The value specifies the transform type followed by a specific amount inside parentheses.
![image](https://user-images.githubusercontent.com/79092103/111366262-f39ae680-869b-11eb-957c-c9aaf2737cb7.png)

### 2D Transforms
##### Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes.

#### - 2D Rotate
![image](https://user-images.githubusercontent.com/79092103/111366425-247b1b80-869c-11eb-9fa4-cf86d3aba151.png)

#### - 2D Scale
![image](https://user-images.githubusercontent.com/79092103/111366585-5a200480-869c-11eb-8085-a14e7eb773fc.png)

![image](https://user-images.githubusercontent.com/79092103/111366635-6d32d480-869c-11eb-85af-060d850339ea.png)

#### - 2D Translate
##### The translate value works a bit like that of relative positioning, pushing and pulling an element in different directions without interrupting the normal flow of the document. Using the translateX value will change the position of an element on the horizontal axis while using the translateY value will change the position of an element on the vertical axis.
![image](https://user-images.githubusercontent.com/79092103/111366738-905d8400-869c-11eb-83d3-1eb43be42c67.png)

#### - 2D Skew
##### The last transform value in the group, skew, is used to distort elements on the horizontal axis, vertical axis, or both. The syntax is very similar to that of the scale and translate values. Using the skewX value distorts an element on the horizontal axis while the skewY value distorts an element on the vertical axis. To distort an element on both axes the skew value is used, declaring the x axis value first, followed by a comma, and then the y axis value.%p
![image](https://user-images.githubusercontent.com/79092103/111366817-b125d980-869c-11eb-97e3-da524517bc06.png)

###### - note that you can find more of syntax for 2d and 3d transform by [transform website](https://learn.shayhowe.com/advanced-html-css/css-transforms/)

### Transitions
##### for a transition to take place, an element must have a change in state, and different styles must be identified for each state. The easiest way for determining styles for different states is by using the :hover, :focus, :active, and :target pseudo-classes.

#### There are four transition related properties in total
- transition-property
- transition-duration
- transition-timing-function
- transition-delay

### Animations
#### Animations within CSS3 allow the appearance and behavior of an element to be altered in multiple keyframes. Transitions provide a change from one state to another, while animations can set multiple points of transition upon different keyframes.

#### Animations Keyframes

![image](https://user-images.githubusercontent.com/79092103/111367908-e848ba80-869d-11eb-9af3-0f6fa2a6e876.png)

##### The animation above is named slide, stated directly after the opening @keyframes rule. The different keyframe breakpoints are set using percentages, starting at 0% and working to 100% with an intermediate breakpoint at 50%. The keywords from and to could be used in place of 0% and 100% if wished. Additional breakpoints, besides 50%, may also be stated. The element properties to be animated are listed inside each of the breakpoints, left and top in the example above.

##### It is important to note, as with transitions only individual properties may be animated. Consider how you might move an element from top to bottom for example. Trying to animate from top: 0; to bottom: 0; will not work, because animations can only apply a transition within a single property, not from one property to another. In this case, the element will need to be animated from top: 0; to top: 100%;.

###### - note: as so you will find the Transitions & Animations [syntax](https://learn.shayhowe.com/advanced-html-css/transitions-animations/)
