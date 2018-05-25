# clean-node-console

## How to use

#### add to your project

```
yarn add clean-node-console
```

```
npm i clean-node-console
```

```
const clean = require('clean-node-console')
```

#### usage example

```
const express = require('express')
const router = express.Router()
const clean = require('clean-node-console')

let num = 0

router.get('/test', (req, res) => {
    clean()
    console.log('request No. ', ++num)
    res.json({
        msg: 0
    })
})
```
#### preview
![image text](https://github.com/Voyager-One/clean-node-console/blob/master/preview/2018-05-25%2014_57_50.gif)
