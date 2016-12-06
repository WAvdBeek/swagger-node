[![Build Status](https://travis-ci.org/swagger-api/swagger-node.svg?branch=master)](https://travis-ci.org/swagger-api/swagger-node) 

The `swagger` module provides tools for designing and building Swagger-compliant APIs entirely in Node.js. It integrates with popular Node.js servers, including Express, Hapi, Restify, and Sails, as well as any Connect-based middleware. With `swagger`, you can specify, build, and test your API from the very beginning, on your laptop. It allows you to change and iterate your design without rewriting the logic of your implementation.

![alt text](./docs/images/overview2.png)


Remember, one great thing about this approach is that all of the Swagger validation logic is handled for you, and all of the routing logic is managed through the Swagger configuration. You don't have to code (or recode!) any of that stuff yourself.

# Your swagger API in five steps

## 1. Install the swagger module (wb-swagger)

Install using npm. For complete instructions, see the [install](./docs/install.md) page.

```bash
npm i -g git+https://github.com/WAvdBeek/wb-swagger-node.git
```

## 2. usage

Use the [CLI](./docs/cli.md) to create and manage projects. Learn more on the [quick start](./docs/quick-start.md) page.
all functions of swagger are still there.
see: https://github.com/swagger-api/swagger-node

only difference is that the swagger command is now replaced by wb-swagger:

```bash
$ wb-swagger validate <swagger file name>
```


# <a name="about"></a>About this project

forked version, with changes to support anyOf oneOf constructs in swagger payload definitions.

This initiative grew out of Apigee-127, an API design-first development framework using Swagger.
Apigee donated the code to create the swagger-node project in 2015.

 >Copyright 2016 Apigee Corporation

 >Licensed under the Apache License, Version 2.0 (the "License");
 you may not use this file except in compliance with the License.
 You may obtain a copy of the License at

 >http://www.apache.org/licenses/LICENSE-2.0

 >Unless required by applicable law or agreed to in writing, software
 distributed under the License is distributed on an "AS IS" BASIS,
 WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 See the License for the specific language governing permissions and
 limitations under the License.

---
<img src="http://swagger.io/wp-content/uploads/2016/02/logo.jpg"/>
