## Creating Wordpress with 
- In an empty folder, open it in VSCode
- `npm init -y`

- Now install the official Wordpress package
`npm install @wordpress/scripts`
Be patient with this installation, it has a lot of packages - it will take some time even on fast internet.

- Once it is done, create a folder `src`  , by default ;- the Wordpress knows to look in this folder for a file named `index.js` .
- In the `index.js` ,  we can write React import code e.g. 
  > import React from 'react'

fun fact,
> No need to run - `npm install react` as Wordpress loads React on its side. 
> This package is smart enough to treat React as an external, meaning:- It will look in the Browser's global scope for React.

The `index.js` file can look like

>import React from 'react'
>import ReactDOM from 'react-dom'
