# npm-bug
Demonstrates npm install problem/bug

# steps to reproduce

* `npm install`
* `npm list --depth 0`
* observe how the necessary **lodash** for **redux** is missing

# tried configurations

* `node 6.0.0` with `npm 3.8.9`
