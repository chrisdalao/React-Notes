#Steps to building React To Do Application - Full CRUD

#some things to keep note of 
- Always use:
 ```js 
 [import React form  'react']; 
 ``` 
at the top of your class components in order to use react

-Always export your components useing:
```js
    [
        export default ComponentName;
    ]
```

- parent class component will be inheriting from React.Component.

#the App class component
- syntax inside component will be:
```js
[
    constructor(){
        super();
        this.state={
            data: [data: "data"]
        },
        data: ""
    }
];
```

-this.state will be holding the state the application will be using

#step 1: render html - (READ)
- use this syntax to render html 
```js
[
    render(){
        return(
            ">>>>>>HTML here<<<<<<"
            <Component bananaName={this.state.nameInThisDotState}/>
            <Component bananaName={this.state.nameInThisDotState}/>
        )
    }
];
```

- write out your components in order to render them 
- pass down the data you need to your component
- give that data a name first and use that as a reference in the component itself.

#step 2: format passing down props and html in JSX
-syntax will be:
```js
[
    const Component = props = {
        ">>>>>>HTML here<<<<<<"
        use props.bananaName.data to get acess to the props being passed down from the parent component.
    }
]
```

#repeat the second step
- every time you use a class Component - you should use step 2 to pass down the props ;