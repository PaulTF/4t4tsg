# Moving Bubble Chart Using D3.js

https://observablehq.com/@eightants/moving-bubble-chart-using-d3-js-internship-search-data-w-per@396

View this notebook in your browser by running a web server in this folder. For
example:

~~~sh
npx http-server
~~~

Or, use the [Observable Runtime](https://github.com/observablehq/runtime) to
import this module directly into your application. To npm install:

~~~sh
npm install @observablehq/runtime@4
npm install https://api.observablehq.com/@eightants/moving-bubble-chart-using-d3-js-internship-search-data-w-per.tgz?v=3
~~~

Then, import your notebook and the runtime as:

~~~js
import {Runtime, Inspector} from "@observablehq/runtime";
import define from "@eightants/moving-bubble-chart-using-d3-js-internship-search-data-w-per";
~~~

To log the value of the cell named “foo”:

~~~js
const runtime = new Runtime();
const main = runtime.module(define);
main.value("foo").then(value => console.log(value));
~~~