# sdp
An android SDK that provides a new size unit - sdp (scalable dp). This size unit scales with the screen size. It can help Android developers with supporting multiple screens.

[Here](https://github.com/intuit/sdp/blob/master/src/main/res/layout/sdp_example.xml) is a single layout built using sdp:

![sdp example](https://github.com/intuit/sdp/blob/master/sdp_example.png)

And [here](https://github.com/intuit/sdp/blob/master/src/main/res/layout/dp_example.xml) is the same layout built using dp:

![dp example](https://github.com/intuit/sdp/blob/master/dp_example.png)

You can see that sdp scales with the screen size and the dp stays with the same size on all screen sizes.

# Getting Started

To add sdp to your project:

1. Using Android Studio and Gradle: 

  add compile project(':sdp') to your build.gradle dependencies block.
  
  for example:
  
  ```
  dependencies {
    compile project(':sdp')
  }
  ```
  
2. Using Eclipse ADT:

  add sdp as a library to your project.

See the [sdp_example.xml](https://github.com/intuit/sdp/blob/master/src/main/res/layout/sdp_example.xml) to see how to use to the sdp size unit.
