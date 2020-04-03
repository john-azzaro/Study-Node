# Node Study

<br>
<br>
<br>
<br>


# What is node

<dl>
<dd>

## Node is a runtime environment for JavaScript on a machine.
Node.js is a server-side enviroment for executing JavaScript that allows us to write JavaScript that runs on the server. It is an open source (MIT license) and cross-platform (PC, MAC, or Linux) runtime enviroment for server-side and networking applications (i.e. executing JavaScript OUTSIDE of a browser).

## Node uses the V8 JavaScript engine in chrome.
Node includes the v8 JavaScript engine plus additional modules that give us extra capabilites that are not inside browsers. V8 is a "just-in-time compiler" written in C++ that takes the JavaScript you write in your web apps and turns it into machine-level instructions. It engine translates JavaScript into instructions that the computer can execute. On top of the V8 engine sit a collection of "modules". These modules include things like file-system, networking, etc. Other modules are built by the commmunity and distributed via NPM.
     
## Node is NOT...
Node is NOT a programming langauge. Node is NOT to be compared to other frameworks like ASP.NET. Node is NOT a framework (its a runtime enviroment for executing JavaScript code). Node is NOT for CPU-intensive applications (since node applications are single threaded).

</dd>
</dl>

<br>
<br>
<br>
<br>

# Why would you use Node.js?

<dl>
<dd>

## Node is used to solve different problems than in a browser.
Node.js is mainly used to create web servers. However, Node can be used to create different types of applications like web applications, chat applications and REST API servers.  

## Node allow us to work with the back-end.
Computers execute machine code instructions, but machine code is difficult for humans to work with. Thus, we use Node to abstract away from machine code to make it easier for people to use. Since web and mobile apps are only the surface, they need a way to talk to some service that sit on the server (or cloud) to store data, send emails, etc.

## Using node has benefits.   
Node is easy to start, good for prototyping and agile development, good for building fast and highly scalable services. Node is lightweight and you can write your front-end and back-end in the same langauge. Additionaly, it is ideal for building highly scalable, data-intensive, and real time back end services that power client applications.


## Applications for Node are written in JavaScript. 
A great reason to use node is that with node application we use JavaScript. Because Node uses JavaScript, your source code will be cleaner and more consistent codebase for both front and back end (i.e. same naming conventions, same tools, etc). Since browsers use JavaScript for components, components are typically written in JavaScript. Since JavaScript is a dynamic language (i.e. the meaning is determined by value, not when it is declared), it is LOOSELY typed rather than strongly typed.

## With node, front and back-ends are in the same language.   
Having the front-end and the back-end written in the same langauge (i.e. JavaScript) is good for a few reasons. There are no syntactical difference when you use one language like JavaScript. Being able to share code betwen the front end and the back end. For example: Shared libraries (like Underscore, etc.) used for both front and back ends so that if you are using user authentication on front and back end, you want to use the same library to authorize the user. For example: Using an algorithm or function that you could use on the front and back end. For example: Using a data model, like the definition of your user which can have many properties. If the back end language is not the same as the front end, you will also have a lot fo maintenance overhead.

## Node is used by many large companies.
Node is used by many large companies like paypal, NetFlix, Uber, etc. Example of paypal who rebuilt one of thier Java and Spring based application with node resulted in an application that was twice as fast with fewer people, 33% fewer lines of code, 40% fewer files, and most importantly doubles the number of requests per seconds with 35% faster average repsonse time. Node has a large ecosystem of open-source libraries so you dont have to build your own building-block from scratch. JavaScript works very well with JSON which is ideal for web apps both on the front and back ends.

</dd>
</dl>

<br>
<br>
<br>
<br>

# Is Node Asynchronous or Synchronous?

<dl>
<dd>

## Node is asynchronous.
Node has an Asynchronous, "non-blocking" architecture that uses a single thread to service multiple requests. A Synchronous "blocking" architecture must service each request before moving on to the next one making it inefficient compared to asynchronous arhcitecture. For example, imagine a restaurant with multiple tables, a waiter, and a kitchen. An Asynchronous restaurant has a waiter (thread) that could service multiple tables (responses) while the orders are given to the kitchen (server). When those orders are done, the finished order in the "event queue" is brough to the requesting table.  

</dd>
</dl>

<br>
<br>
<br>
<br>

# What is NPM?

<dl>
<dd>

## NPM manages dependencies.
NPM (Node Package Manager) is used for managing dependencies and other meta information. NOM can be used to initialize a project, list what packages are needed in order to function, write short scripts that allows developers to work with the project, etc.

</dd>
</dl>

<br>
<br>
<br>
<br>

# What are CLI tools?

<dl>
<dd>

## CLI tools are prewritten scripts.
CLI tools (Command Line Interface tools) are prewritten scripts that can be run to perform various tasks. For example, the ```create=react-app``` commmand that creates a React application, is a Node script that generates all the files into a new file for you.

</dd>
</dl>

<br>
<br>
<br>
<br>

# What are local dependencies?

<dl>
<dd>

## Local dependencies are for local projects.
For example, when you install a local dependency, it will be installed ONLY on the respective project and not on the whole machine. Local dependencies are preferred to global installs becuse there might be different version numbers we want to use for particualr projects. Additionally, local dependencies are listed in your package.json file so they are explicit. Also, global dependencies might create system conflicts with other tools.

</dd>
</dl>

<br>
<br>
<br>
<br>

# What is NPX?

<dl>
<dd>

## NPX is used for one-time commands.
For the times you only need run a CLI tool once or every once and a while where you do NOT need to have it as a dependency, NPX will let you run whatever follows as a one  time command without a global install. For example, when you use ```npx create-react-app```, you only need to run this once to create the scaffold of your React application. Since it is a a one-off command, you run it and the command gets cleaned up once its finished.


</dd>
</dl>

<br>
<br>
<br>
<br>