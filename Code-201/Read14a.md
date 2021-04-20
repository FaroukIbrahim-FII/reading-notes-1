# Read: 14a - CSS Transforms, Transitions, and Animations


#### The transform property comes in two different settings, two-dimensional and three-dimensional. Each of these come with their own individual properties and values.

#### transform property includes multiple vendor prefixes to gain the best support across all browsers.

```CSS
  -webkit-transform: scale(1.5);
     -moz-transform: scale(1.5);
       -o-transform: scale(1.5);
          transform: scale(1.5);
```

#### Transformed, a two-dimensional plane or a three-dimensional plane. Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes. Three-dimensional transforms work on both the x and y axes, as well as the z axis. 

### 2D :
* rotate value : provides the ability to rotate an element from 0 to 360 degrees. Ex : `transform: rotate( numOfDeg deg);`.
* scale value : within the transform property allows you to change the appeared size of an element. The default scale value is 1. Ex : `transform: scale( Num );`. It is possible to scale only the height or width of an element using the scaleX and scaleY values. Ex : `transform: scaleX( Num );` + `transform: scaleY( Num );`or `transform: scale( X , Y );`.
* translate value :  pushing and pulling an element in different directions without interrupting the normal flow of the document. Ex : `transform: translateX( Num );` + `transform: translateY( Num );` OR `transform: translate(X, Y);`.
* skew : is used to distort elements on the horizontal axis, vertical axis, or both. Ex : `transform: skewX(Num deg);` + `transform: skewY(Num deg);` OR `transform: skew( X deg, Y deg);`.
#### Combining Transforms - Ex : `transform: rotate( Num deg) scale( Num );`.
 
### 3D :
* Perspective : In order for three-dimensional transforms to work the elements need a perspective from which to transform. The perspective for each element can be thought of as a vanishing point. while the length value will set the depth of the perspective. Ex : `transform: perspective(Num px)`.
* Origin : As with setting a transform-origin you can also set a perspective-origin. Ex : `perspective-origin: Num px Num px;`.
#### 3D Rotate : With three-dimensional transforms we can rotate an element around any axes. To do so, we use three new transform values, including rotateX, rotateY, and rotateZ. Add : `transform: rotateZ(Num deg);` + `transform: scaleZ(Num);` + `transform: translateZ(Num px);`.
* transform-style : To allow nested elements to transform in their own three-dimensional plane use the transform-style property with the preserve-3d value. Ex : `transform-style: preserve-3d;`.
* backface-visibility : set the backface-visibility property to hidden, and you will hide the element whenever it is facing away from the screen. Ex : `backface-visibility: hidden;`.

### Transitions & Animations :
* Transitional Property : The transition-property property determines exactly what properties will be altered in conjunction with the other transitional properties. Ex : `transition-property: background, border-radius , etc;`.
* Transition Duration :The duration in which a transition takes place is set using the transition-duration property. Ex : `transition-duration: Num s OR Num ms;`.
* Transition Timing : The transition-timing-function property is used to set the speed in which a transition will move. Ex : `transition-timing-function: linear / ease-in / etc;`.
* Transition Delay : set a delay with the transition-delay property. Ex : `transition-delay: Num s OR Num ms;`.
* Shorthand Transitions : To set numerous transitions at once. Ex : `transition: background .2s linear, border-radius 1s ease-in 1s;`.
* Animations Keyframes : To set multiple points at which an element should undergo a transition. Ex :
```CSS
@keyframes nameOFAnimation {
  0% {
  
  }
  50% {

  }
  100% {

  }
}
```
* Animation Name : The animation-name declaration is applied to the element in which the animation is to be applied to. Ex : `animation-name: nameOFAnimation;`.
* Animation Duration : animations need a duration declared using the animation-duration property. Ex : `animation-duration: Num s OR Num ms;`.
* timing function and delay can be declared using the animation-timing-function and animation-delay properties respectively. Ex `animation-timing-function: ease-in-out/etc;` And `animation-delay: Num s OR Num ms;`.
* Animation Iteration : animations run their cycle once from beginning to end and then stop. To have an animation repeat itself numerous times. Ex : `animation-iteration-count: infinite/ Num ;`.
* Animation Direction :  declare the direction an animation completes.  animation-direction property include normal, reverse, alternate, and alternate-reverse. Ex : `animation-direction: alternate;`.
* Animation Play State : animation to be played or paused using the running and paused keyword values respectively. Ex : `animation-play-state: paused;`.
* Animation Fill Mode : how an element should be styled either before, after, or before and after an animation is run. accepts four keyword values, including none, forwards, backwards, and both. : Ex `animation-fill-mode: forwards;`.
* Shorthand Animations - Ex : `animation: slide 2s ease-in-out .5s infinite alternate;`.

[ Back To README !]( https://yousefabujalboush.github.io/reading-notes/ )