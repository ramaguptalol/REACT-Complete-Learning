## in package.json, 

there's dependencies, and scripts, versions

	there's react and react-dom dependencies which successfully runs our react code

![][image1]

whenever a page loads,

index.js is first loaded

index.css is nothing, just provides class, id for 	index.js

JSX is Javascript XML

app.js or app.jsx is for app component where all the codes will be sent for rendering. (for showing)

![][image2]

![][image3]

# COMPONENT CREATION in Item.jsx

go and create components folder  
add Item.jsx and Item.css

## to import/ add any file
`
import './Item.css';
`
## Function Creation

after creating function, we also need to put export below it
``` javascript
function SomeThing(){  
  return(  
 <div>  
 <p>Hello Buddy</p>  
 </div>  
  );  
}

export default Something;
```

Note: \<p className\="okaa"\>hey\</p\> when writing class for adding css, we have to write here className

# COMPONENT USING in App.jsx

## FOR IMPORTING component

okay, so to import a component

import Item from './components/Item.jsx';

## CALLING THE component

go in App.jsx and insert\<\>\</\> with its name
``` js
return(  
  <div>  
<Item>\</Item>  
	……………..  
	……………..  
	……………..  
  </div>  
);
```
# How to reuse Component???

Passing Props
