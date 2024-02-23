# tea-oss-number-generator

Run:

```
npm i tea-oss-number-generator

```

Create a generate file

```

touch generate.js

```

```
const TeaOssNumberGenerator = require('oss-number-generator');
console.log(TeaOssNumberGenerator(5, 10));

```


You can change the number range that you want to generate in the generate.js file

it is between 5-10 by default

Generate: 

```

node ./generate.js

```
