# Creating an awesome Signup form using React

1. Cloning the create-react-app-barebones project
2. Creating a 'components' folder
3. Creating a 'components/EmailInput' folder
4. Creating our first stateless component (EmailInput)
    1. Importing React
    2. Export default function
    3. Returning JSX from our component
    4. Adding our <input> tag to the JSX
    5. HTML entity properties and Component properties
        1. type
        2.  value
        3.  placeholder
        4.  onChange
    6. Importing and using PropType validations
    7. Strings and Funcs and isRequired PropTypes
5. Creating our first stateful component (SignupForm)
    1. The esNext class and extends keywords
    2. Our component constructor and super
    3. Creating our state object
    4. Importing and using our EmailInput component
    5. Managed component values
    6. Component event handlers
    7. Binding class instance function context (this)
    8. Changing component state via event handles
6. Importing and using component assets
    1. Creating component css files
    2. Unique classNames (__component-name)
    3. Implementing some basic styles
    4. Importing the CSS file
    5. Adding the className property to EmailInput
7. Creating a stateless PasswordInput component
    1. Creating the component folder 'components/PasswordInput'
    2. Creating the component file 'components/PasswordInput/index.js'
    3. Copying the code from the EmailComponent and renaming
    4. Copying the styles.css file from EmailComponent and renaming
8. Importing and using our PasswordInput in SignupForm
    1. Adding our password state to the constructor
    2. Adding a change handler for password
    3. Adding our PasswordInput component to the render function
9. Generalizing common code from EmailInput and PasswordInput
    1. A single handleChange event handler instead of two
    2. Immutable change state and the spread operator
    3. Creating a generic Input component to wrap common functionality
