# Class01

## Why This Matters

It is obvious React is best used from the approach of addressing a site on a components basis for adding, changing, or removing items from the DOM.

## What is a “component”?

A component is a modular, portable, replaceable, and reusable set of well-defined functionality that encapsulates its implementation and exporting it as a higher-level interface. A component is a software object, intended to interact with other components, encapsulating certain functionality or a set of functionalities. It has an obviously defined interface and conforms to a recommended behavior common to all components within an architecture. A software component can be defined as a unit of composition with a contractually specified interface and explicit context dependencies only. That is, a software component can be deployed independently and is subject to composition by third parties.

## What are the characteristics of a component?

**Reusability** − Components are usually designed to be reused in different situations in different applications. However, some components may be designed for a specific task.

**Replaceable** − Components may be freely substituted with other similar components.

**Not context specific** − Components are designed to operate in different environments and contexts.

**Extensible** − A component can be extended from existing components to provide new behavior.

**Encapsulated** − A A component depicts the interfaces, which allow the caller to use its functionality, and do not expose details of the internal processes or any internal variables or state.

**Independent** − Components are designed to have minimal dependencies on other components.

## What are the advantages of using component-based architecture?

**Ease of deployment** − As new compatible versions become available, it is easier to replace existing versions with no impact on the other components or the system as a whole.

**Reduced cost** − The use of third-party components allows you to spread the cost of development and maintenance.

**Ease of development** − Components implement well-known interfaces to provide defined functionality, allowing development without impacting other parts of the system.

**Reusable** − The use of reusable components means that they can be used to spread the development and maintenance cost across several applications or systems.

**Modification of technical complexity** − A component modifies the complexity through the use of a component container and its services.

**Reliability** − The overall system reliability increases since the reliability of each individual component enhances the reliability of the whole system via reuse.

**System maintenance and evolution** − Easy to change and update the implementation without affecting the rest of the system.

**Independent** − Independency and flexible connectivity of components. Independent development of components by different group in parallel. Productivity for the software development and future software development.

## What is “props” short for?

In React, the term props stands for properties, which refers to the properties of an object.

## How are props used in React?

React props are a singular aspect of React used to help simplify the passing of data from one component to another. However, it is not the act of giving props to one of your friends, that is very different. Instead, it's how an application shares data across different parts of a piece of software. React props can be thought of as rain falling on layers of soil, typically the flow is down, not up. Because of this, the element that uses the props value is generally the child of the component that contains it. In React props are used primarily to display data that does not change, to render data that needs regular updating you’ll need state.
![Example of using props](code-301/class1pic.jpg)

## What is the flow of props?

React props flow is down, not up.

## Things I want to know more about

I've watched enough videos but I need to get my hands "dirty" with some react code. Think I am in a deep hole now with not having a strong understanding of JS and getting exposed to React so quickly. I am just glad that there is only a week break between 201 & 301.

## Sources To Cite

- [Component-Based Architecture](https://www.tutorialspoint.com/software_architecture_design/component_based_architecture.htm)

- [What is “Props” and how to use it in React?](https://itnext.io/what-is-props-and-how-to-use-it-in-react-da307f500da0)

- [Tutorial: Intro to React](https://reactjs.org/tutorial/tutorial.html)

- [Hello World](https://reactjs.org/docs/hello-world.html)

- [Introducing JSX](https://reactjs.org/docs/introducing-jsx.html)

- [Rendering Elements](https://reactjs.org/docs/rendering-elements.html)

- [Components and Props](https://reactjs.org/docs/components-and-props.html)

- [Introduction to React Props & How to Use It in Your Code](https://blog.hubspot.com/website/react-props)
