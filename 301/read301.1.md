
# ***Component***

  ![Component](https://www.dmcinfo.com/Portals/0/Blog%20Pictures/React%20Components.png)

A **Component** is part of code (block) that can be replaceable, portable, and reusable. or we can say a component is a software object(code), intended to interact with other components, we can call a component at some place and change or add something in this part of code only.  [from](https://www.tutorialspoint.com/software_architecture_design/component_based_architecture.htm)

* Views of a Component :
    * object-oriented view
    * conventional view
    * process-related view


## **Charactistics of a Component :**
   * ***Independent*** => designed to have minimal dependencies.
   * ***Reusability*** => usually designed to be reused in different applications. 
   * ***Replaceable*** => Components may be freely substituted with other similar components.
   * ***Extensible*** => can be extended from existing components.
   * ***Encapsulated*** => allow the caller to use its functionality, and do not expose details of the internal processes or any internal variables or state.
   * ***Not context specific*** => designed to operate in different environments.

   ![Component](https://miro.medium.com/max/700/0*5vEroMcVEXF1ghUi.jpg)

## **Advantages of using component based architecture:**
   * Ease of deployment
   * Reduced cost
   * Ease of development 
   * Reusable 
   * Modification of technical complexity
   * Reliability 
   * System maintenance and evolution
   * Independent 


![react](https://thumbs.gfycat.com/BestMeagerHoki-size_restricted.gif)

# ***Props***
 * The components need to communicate between each other (send data) and the way to pass data between components is by using **props**.
 * " **“Props”** is a special keyword in React, which stands for **properties** and is being used for **passing data from one component to another.**"
 * Props is read only.
 * uni-directional flow. (**one way** from parent to child).
## " How to use Props in react " [from](https://itnext.io/what-is-props-and-how-to-use-it-in-react-da307f500da0)
  1. Firstly, define an attribute and its value(data).
  2. Then pass it to child component(s) by using Props.
  3. Finally, render the Props Data.

   * example : 
     1. `<a href="www.google.com">Click here to visit Google</a>;`
     2. `<ChildComponent someAttribute={value} anotherAttribute={value}/>`


