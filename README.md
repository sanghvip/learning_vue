# learning_vue

[Tutorial](https://youtu.be/FXpIoQ_rT_c?si=Y8qFbGvN6lVOg0g6)
Vue setup
1. learned about adding vue to your application using the script tag
2. Availabilty of the Vue variable in the <script> to initialize and create the vue app
3. ability to pass data to the app using the options and data variable

Vue directive
1. v-model: to link a html directive with a variable
2. v- prefix helps to differentiate the vue components
3. v-show,v-if: similar directives and they both take some boolean argument
4. other examples would be v-else-if, v-els etc.
5. v-cloak: Used to hide un-compiled template until it is ready.

Vue events and methods
1. v-on is the event handler v-on:click will handle the click event
2. v-on:click will take a JS value assignment or a function call as well
3. @(shorthand) replaces v-on
4. listen for keyboard event using @keyup. Listen for enter key press using @keyup.enter
5. event modifier listens for specific event. For a keyup event is @keyup.enter

Vue components
1.  app.component will be used to create a vue component which takes 2 parameter, name and options object
2. the options object can contain template key to specify the template
3. data key to specify the data
4. passing data to child component using v-bind:var_name
5. Child component can accept props from parent by specifying props key in the components options object
6. for the parent component to recognize any child component, we need a component key and value of lists containing the child component name
7. since v-bind is a very common directive, we can use :<propname> instead of v-bind
8. To pass a value to child we create a prop key in the child component and specify the lable. For passing from child to parent, we have something called modelValue and computed key with its own get and set method.
9. props are immutable in the child

Vue template loop
1. v-for is a for in loop which can be used to iterate over an array
2. key attribute should be specified on the element which will be repeated


Vue lifecycle hooks
[Flowchart](https://vuejs.org/assets/lifecycle.16e4c08e.png)

lifecycle hooks helpful for following usecases
1. check if user is authorized
2. api calls
3. creating or removing events
4. getting or cleaning up data

[CheatSheet](https://www.vuemastery.com/pdf/Vue-Essentials-Cheat-Sheet.pdf)
