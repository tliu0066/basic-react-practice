#react practice note

create react : npm create vite@latest

use “npm i” to install all package that we want

use “npm run dev”

# constructor of react

-node_modules : included all third part dependency

-public: store like images

-src: 

-index.html

-package.json

-tsconfig.json: dont need modify this file normally 

# create first component

.tsx : typescript file for react

.ts : normal typescript file

using PascalCasing casing to create function

JSX: javascript XML

remamber to Export in the end of each component to be ready to reuse in the feature

# How React working

Virtual Dom

# React eco system

React is a js Library

# listgroup component

install bootstrap for style: npm i bootstrap@xxx

copy style in bootstrap for list group

using command + d to multi chose the next same word

# fragment

select the part you want to modify → view → command pattern → wrap abbrivation → the change you want to add

# render list

in jsx using “{}” to render data

- create a list : const items = [”xxx”, ”sss”]
- in the html section use” {items.map((item)⇒(<li key={item}>{item}</li>))} “

# condition render

in html section remain to use “{}” to show the const 

# handle event

in the <> add “onclick={()⇒()}

# managing state

class name is also can use {} to assign

hook

useState(): return a array which contain two element 

ex: const arr = useState(-1)

arr[0] // variable (selectedIndex)

arr[1] // updater function

# use props translate data

typescript specific “interface”

ex: interface props:{

items: string[];

heading: string;

}

# state vs props

props is inmutable

# children

reactnode
