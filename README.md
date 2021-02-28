# newbieDictionary
**I have made this Open Source (definition in the dictionary!) to enable us all to add and learn from each other!
I want YOU to contribute. Click 'fork repository' (button in the top right), make your additions in your 'own version', and then create a pull request (definition below) to put it back into this main version! I'll review it and then add it in.** 😄

**If you'd like a word to be defined, just write it in the alphabetical place and write it like this:**

************
### Word -
Definition
************
**You can then come back later and see if anyone has defined it!! I'll check often for these and promote them on Twitter so we can get great answers!!**




I have been thinking about making this for some time, but I wanted to make sure that I had enough knowledge about random tech words before I started...



A code/tech dictionary!



Sometimes, (well for me at least) it very much seems that this industry has overcomplicated words and phrases for things _on purpose._

You may be learning from someone who has been in the industry for a while, and for them, these words _just make sense_

But do they make sense to you, as a newbie?

### Absolutely not

I have tried to gather a few words/phrases and definitions together here to help you out, and we can add to it as we go along!!

There are sometimes multiple words for the same thing, again - just to be confusing.





                                                      📖



### A11y -
A numeronym for accessibility, where the number 11 refers to the number of letters omitted. A11y refers to the accessibility of a computer system to all people, regardless of disability type or severity of impairment.

### AJAX -
AJAX is not a programming language.
AJAX just uses a combination of:
 - A browser built-in XMLHttpRequest object (to request data from a web server)
 - JavaScript and HTML DOM (to display or use the data)

### API -
Stands for Application Programming Interface, which provides a comprehensive layer of communication and callbacks to the original software layer, so that it becomes easier to integrate. Example- The google maps API allows you to integrate their maps to your apps through their API. An API is a contract between you and the software that you want to use, telling you what you can and can't do with it. It's a bridge allowing you to use the software and integrate it with your code.

### Arrays -
Arrays are containers that hold variables, they're used to group together similar variables. You can think of an array like a book shelf where books are kept next to each other in a row. Similarly arrays are stored in memory as a continuous block.

### ASCII -
Stands for 'American Standard Code for Information Interchange'. It is the set of common characters use in electronic communication, based in English alphabet, numbers, punctuation symbols and non-printing control characters (like Escape, Tabulation, Backspace, End of Line, etc). This standard is the base line to newer sets of characters like UTF-8 standard, that extends ASCII including new characters like Latin or German characters by example.

### Authentication -
Authentication is the process of recognizing a user's identity. In authentication, the user or computer has to prove its identity to the server or client. Authentication by a server entails the use of a username and password. It is the process of validating the identity of a registered user before allowing access to the protected resource.

### Authorization -
Authorization is the process of determining a user's access levels, or permissions, to various systems or features once **authenticated**. For example, a user may be authorized for read-only access or administrator access.

### Babel -
A JavaScript transpiler that converts edge JavaScript into plain old ES5 JavaScript that can run in any browser (even the old ones).
    Currently, most browsers support ES5. ES5 used to be good even though it was so painful to code in [it.Is](http://it.is/) this not reading from inside callback functions? The new version of JavaScript, ES6, also known as ES2015 makes JavaScript great again.

If you want to learn about ES6. All the good features of ES6 accompany one big problem — the majority of browsers don’t fully support them. That’s when Babel comes to its work. Babel may be a JS transpiler that converts new JS code into old ones. It is a really flexible tool in terms of transpiring. One can easily add assets such as es2015, es2016, es2017, or env; so that Babel compiles them to ES5.

### Bcrypt -
The bcrypt hashing function allows us to build a password security platform that scales with computation power and always hashes every password with a salt. The process of generating salt is done using genSalt() and then the passwords that need to be hashed are hashed with this salt and bcrypt-ed password is ready.
This works on the bluefish encryption algorithm.

### Boilerplate (code) -
The standard code you need to put into your code in order for it to run. An example is frameworks. Let’s take Bootstrap as an example. To use it, you need to copy and paste in a bunch of code that you get from the official website in order for you to be able to use it. Like a template.

### Bug -
A bug is a general term used to describe any unexpected problem with hardware or software. Its different from an error. Error is a message shown to let user know that something went wrong while bug is a problem in the code that caused the error.


### Cache - 
A cache (pronounced as *cash*) is a temporary memory or storage area, for example, in browser or cloud.

### Caching - 
Caching is the process of storing temporary data into a cache. For example, when we make a request to an API for the first time, we store the response's data into the browser's cache so that when we need the same data again then we don't need to make a request to the API, we can just get it from the cache. This helps in reducing network calls and make our apps faster.


### Callback function -


A function (Plug-in) passed as an argument to another function or method (Worker). The function Worker call the function Plug-in within its context with the corresponding data, e.i.:

```javascript

// Notify functions are our Plug-ins

function notifyByAlert(msg) {
  alert(msg)
}

function notifyByConsole(msg) {
  console.log(msg)
}

function notifyBySweetAlert(msg) {
  Swal.fire({
    icon: 'info',
    title: msg
  })
}

// This function is our Worker
function greetings(name, callback)  {
  let message = `Hello ${name}`
  callback(message)
}

// Here we'll inject our Plug-in functions, in other words, a callback

greetings('Test #1', notifyByAlert)
greetings('Test #2', notifyByConsole)
greetings('Test #3', notifyBySweetAlert) // this one require sweet alert 2 lib


```

### CLI -

See [Terminal or Cli](#terminal-or-cli--)

Can also stand for Common Language Infrastructure. A tool, developed by Microsoft, to allow different languages to be understood and interpreted by different computer programs, rather than having to restructure the architecture and build behind it.

### Compiler -
A compiler is a program that translates computer programs written using letters, numbers, and characters into a machine language program that can be read and executed by a computer. For example gcc compiler is used to compile a C program.

### Cryptography -
The art of hiding secrets and researching for secure communications, to protect them from third parties.

### Destructuring -
This means to unpack values in a data structure such as an Object or Array.

### Directory -
Another word for folder.
_”Navigate to the correct directory”_ = go to the right folder.

### DOM -
Stands for Document Object Model. Always in capitals like that. A place in the browser to see a page’s HTML, CSS, and JavaScript all working together like a happy little family. You can type in it and add stuff. Useful when making a website and you want something to look a particular way.
See [Manipulating the DOM](#manipulating-the-dom--)

### Double -
A double is a double-precision, 64-bit floating-point data type. It accommodates 15 to 16 digits, with a range of approximately 5.0 × 10−345 to 1.7 × 10308.
- Double precision value
- Stores up to 15 significant digits
- Double is costlier, occupies more space and is more effective when more precision is required. For example, currency conversion, financial reports and transactions, scientific calculations etc…

### Electron -
Electron is a framework for cross-platform desktop applications using Chromium and Node.js.

It’s easy to build cross-platform apps using HTML, CSS, and JavaScript. Your app will be compatible with Mac, Windows, and Linux operating systems right out of the box. 8. Source code - Source code is the list of human-readable instructions that a programmer writes—often in a word processing program—when he is developing a program. The source code is run through a compiler to turn it into machine code, also called object code, that a computer can understand and execute. Object code consists primarily of 1s and 0s, so it isn't human-readable.

### Environment -
Where you are working within your computer. For example, if you are making a webpage, your environment would be a **text editor** or **IDE** and the browser window.

### Firebase -
A platform developed by Google to build mobile and web applications. It provides services like Authentication, Realtime Database, Cloud Firestore , Cloud Storage, Cloud Functions,web  hosting, ML Kit etc.

-You’re gonna save a ton of time and money using Firebase products rather than trying to build them yourself.

### Float -
 A float is short for floating-point number. It's a common way for computers to store decimal numbers or fractions
 ```c
 float b = 0.0;
 ```

### Framework -
A platform for developing software applications. It has rules, instructions and some boundations which makes it different from a library. Since they are often built, tested, and optimized by several experienced software engineers and programmers, software frameworks are versatile, robust, and efficient. It is a language written to help you to write code easier. Often comes with **boilerplate** code to get you started.

### Function -
The block of code that you can call by name, a function is independent of an object.

### Function & variable naming conventions -
A naming convention is a set of rules for choosing the character sequence to be used for identifiers which denote variables, types, functions, and other entities in source code and documentation.
 - camelCase: Writing names without spaces or punctuation, indicating the separation of words with a single capitalized letter.
    Example:
     - helloWorld
     - newbieDictionary
 - Pascal Case: Making the first letter of each word capitalized. Often used when writing code to name functions, classes, and other objects.
    Example:
     - Car
     - LinkedList
 - kabab-case: Putting a hyphen between words in order to improve readability while allowing them to be used as variables in code.
    Example:
     - hello-world
     - active-multiplier
 - snake_case: Putting an underscore between words to improve readability, and for languages where a hyphen would be interpreted as a subtract operation
    Example:
     - hello_world
     - python_rocks
 - SCREAMING_SNAKE_CASE: snake_case but louder (all caps), often used to easily distinguish macros and constants from variables
    Example:
     - HELLO_WORLD
     - HOST_NAME

### Git -
The name of a version control system. Involves branches and trees, pushing and pulling. All in all a great time.

### GitHub -
The name of a hosting service for storing and interacting with git repositories. GitHub provides additional collaboration tools on top of git, such as Pull Requests, Issues/bug reports, wiki, and other features. Other popular git hosting services include BitBucket and GitLab.

### IDE -
Stands for ‘Integrated Development Environment’. It is somewhere that you write code, and has tools to help you write, structure and test it. Build, test, connect to databases, the works!

### Headless CMS -
A Headless CMS is a back-end **Content Management System** where the content (data) is stored in a repository or a bucket which can be delivered to the presentation layer (for examples: web page, mobile app) with the help of an API. It is different from a traditional CMS as it is independent of the presentation layer and the same content can be reused across different platforms and devices.

The presentation layer of a website is the “head” of a CMS, we are separating the head from the body (back-end layer of the CMS), that's why the name **"*Headless*" CMS**.

### HTTP -
HTTP or Hypertext Transfer Protocol is the set of guidelines for transferring files such as texts, videos, sounds, images, and other multimedia files through the World Wide Web. The moment a Web user opens the browser, the user is indirectly making use of HTTP.

### HTTP Status Codes
HTTP Status codes are part of the response data returned by an HTTP request, which signals to the client about the result in a way that is easy for code to understand. Common status codes include:

- **200** - OK. This is the status response for a successful request. When you visit a webpage, and the webpage loads fine, this is the response.
- **400** - Bad Request. Often returned when the request's data is bad and cannot be handled by the server.
- **403** - Forbidden. Usually returned if the request does not have authorization to access the resource (missing login details for example)
- **404** - Not Found. Returned when a requested resource does not exist
- **500** - Internal Server Error. Used when there is an server internal error (i.e. a bug)

A full list and detailed explanation of each status can be found [here](https://en.wikipedia.org/wiki/List_of_HTTP_status_codes).

### HTTPS
Stands for “Hypertext Transfer Protocol Secure” which means the webpage has a special layer of encryption added to hide your personal details and passwords. Hence, if you wish to secure your bank account details at an online shopping site, look for “https” in the URL.

### Integer -
An integer (pronounced IN-tuh-jer) is basically a data type in programming language and also an integer is a whole number (not a fractional number) that can be positive, negative, or zero.

### JSON -
Stands for JavaScript Object Notation. JSON is a common data format (a way data is written), originally derived from JavaScript, many programming languages now have the ability to use JSON. JSON data types include: number, string, boolean, array, object, or null. Basic JSON might look like this:

```json
{
    "firstName": "Faye",
    "lastName": "Sipiano",
    "age": 27,
    "eyeColor": "blue",
}
```

### Kernel -
A piece of software running as a communicator between regular software and hardware, containing all the lower-level functions to talk to the hardware and providing an API for the software to modify the state of hardware interfaces securely. Example - The Linux Kernel

### Key-Value Pairs

Key-value pairs let us give labels (or keys) to pieces of information (or values). We can use the labels to retrieve that information later on. They are also called attribute-value pairs. The key is like an index, but can be a more sensible way to name a piece of information than by its position. We can add key-value pairs to data structures like objects (e.g. in JavaScript), or dictionaries (in Python). Pair a key with its value by using a colon between them. Separate each complete pair with a comma when entering them. E.g. `{keyA: valueA, keyB: valueB, keyC: valueC}` contains three key-value pairs.

### Library -
A collection of functions which can be added to your application and the functions called as necessary, just like any other functions in the application. More precisely any object, not only functions can be stored in a library, but the vast majority of libraries only contain functions.

### Local/locally -
On your computer
_“You can access it locally”_

For the opposite of Local, see [Remote](#remote--)

### Manipulating the DOM -
Just means changing something (usually JavaScript) in the DOM.

### Machine Learning -
A realm of study within the domain of artificial intelligence that aims to develop techniques in software which allow machines to learn through experience.

### Method -
The block of code that you can call by name that is associated with an object (in javascript, every function treated as object,So in simple words, A method is on an object)

### MEAN Stack -
MEAN is a free and open-source JavaScript software stack for building dynamic web sites and web applications. The MEAN stack is MongoDB, Express.js, AngularJS, and Node.js.

### MERN Stack -
MERN Stack is a Javascript Stack that is used for easier and faster deployment of full-stack web applications. MERN Stack comprises of 4 technologies namely: MongoDB, Express, React and Node.js.

### MEVN Stack -
MEVN stack is the open-source JavaScript software stack that has emerged as a new and evolving way to build powerful and dynamic web applications. This stack consists of MongoDB for NoSQL Database, Express.js for building the server, VueJS for front-end and Node.js as the JavaScript runtime environment.

###  Namespace (in javascript) -
While we are working on web applications using JavaScript functions and files, it would become difficult to challenge code. So to help us manage this code, we have a keyword ‘Namespace’ which will create mini objects of different modules or functionalities to make code readable. JavaScript does not provide Namespace by default but this functionality can be replicated. It is a container providing scope for set of identifiers, type names, functions or variables, and methods, etc. to prevent collisions among them. It can be created with ease, so with minor tweaks, a namespace can be created.

Example: First, we need to initialize an empty Namespace: like var <namespace> = { };

Then to access variables in the namespace, <namespace>.<identifier>

Similar to Objects in JavaScript, we initialize and access this namespace as objects.

```js
var sampleNamespace = {
  function_one: function()
  {
    // body of code
  },
  function_two: function()
  {
    // body of code
  }
};

...

sampleNamespace.function_one ();
```

This JavaScript Namespace functionality can be replicated by creating a global object which contains all functions and variables. In modern web applications, different libraries and components are used, so we should have namespace to avoid code ambiguity.

### NaN -
Stands for 'Not a Number'. In JavaScript `typeof NaN` is `Number`.

### Nextjs -
Next.js is a React framework built by Zeit, and according to [nextjs.org](http://nextjs.org/):

With Next.js, server rendering React applications has never been easier, no matter where your data is coming from.

Next.js also supports static exporting, but for the purposes of this post, we are focused on that “server rendering” capability mentioned above.

Also see [React](#reactjs--)

### Objects -
In code, you can create an ‘object’ that you can refer to later, for example you can create a ‘person’ with a first name and last name, an age, and an eye colour. This can then be used again if you wanted to create another ‘person’

``var person = {firstName:"Faye", lastName:"Sipiano", age:27, eyeColor:"blue"};``

### Open API -
The OpenAPI Specification, public discoverable API, originally known as the Swagger Specification, is a specification for machine-readable interface files for describing, producing, consuming, and visualizing RESTful web services.

### Open source -
A project or repository that anyone can request to make changes or updates to. This is a good way to learn. For example, this dictionary is Open Source.

### Pseudocode -
A human-readable explanation of how something should work – the way and order that it runs in. Pseudocode does not have to follow the rules of any programming language. It is a description of what the code in a program is doing so that even non-technical individuals can understand its logic.

### PR -
Stands for 'pull request'. Means that you are requesting that the changes or edits you have made be reviewed and eventually merged (in **git**)
Also known as MR for 'merge request'

### PR -
Also a marketing term meaning 'Press release'. Means anything going out to be published into the wide world for others to see. You could create a PR for a PR I suppose...

### PWA -
PWA stands for Progressive Web App. It is basically a website that gives the look and feel of a native app.That means it is an incredible mix of the best of both, the web and native applications.

Features- 1) No need to download and install. 2) One canadd it to home screen. 3) Offlice functionality using service worker's. 4)Quick loading.
Drawbacks- 1) No indoor geolocation -it cannot access Bluetooth. 2) No consumer data access like contact and socil profiles. 3)High battery usage.

### Recursion -
Some algorithms can be reduced to a simple function that acts on the value returned by another run of itself, when a function calls itself as part of such an algorithm, this is known as recursion. Common recursive algorithms include list traversal, or tree searches, or mathematical sequence generation.

Recursive algorithms must have an end condition so that it doesn't recurse infinitely. However, care must be taken when using recursion, as a practical limitation of recursion is high **stack memory** usage, which can lead to a problem known as **stack overflow** (which the popular programming question & answer website is named after)

Alse see [Recursion](#recursion--)

### Reactjs -
An open-source, front end, JavaScript library for building user interfaces or UI components. It is maintained by Facebook and a community of individual developers and companies. React can be used as a base in the development of single-page or mobile applications.

### Refactor -
Means to look over and rewrite your code in a different way. Maybe you learned a better way to do it, so you rewrite it.
_”I’m going to spend today refactoring old code because I learned so much since I first wrote it!”_

### Regex -
Short for regular expression, a regex is a string of text that allows you to create patterns that help match, locate, and manage text. Its a sequence of characters that define a search pattern which come very handy in many cases like form validation, searching stuff, etc

### Remote -
Not on your computer – stored on someone else's machine/server. Usually means you need to log in, through a portal or …... to be able to access it.

For the opposite of Remote, see [Local](#locallocally--)

### Repository -
A house for your code, stored online. Repositories are collections of source code

### Responsive Web Design -
The practice of designing websites so that they adapt gracefully to different-sized devices like phones, tablets, wearable devices, etc. If you’re able to visit a website on your phone and it looks just as proportional and seamless as it does on your computer, it’s an example of responsive web design.

### ReST (Representational State Transfer) -
A uniform interface which allows for a standard way to transfer and manipulate resources. Communication occurs through methods, like GET a resource, POST a new one, or DELETE a resource. This allows for software to share and manipulate data over a network connection through a standard interface. Browsers generally use the GET and POST methods to serve websites, but many others exist for different use cases.

### Runtime -
Runtime is the time period during which a program is running on a computer. If an operation occurs at ‘runtime’, it occurred when a program is running or the moment at which the program begins to run. Also known as execution time.

### Salt -
A [salt](https://heynode.com/blog/2020-04/salt-and-hash-passwords-bcrypt) is a random string. By hashing a plain text password plus a salt, the hash algorithm’s output is no longer predictable. The same password will no longer yield the same hash. The salt gets automatically included with the hash, so you do not need to store it in a database.

### Scrum/Agile -
Methodical frameworks for organizing, developing, delivering and maintaining software. Scrum and Agile disciplines can be applied to a wide variety of fields but has been a popular choice in software development due to its effective approach to handling very complex tasks.

### SDK -
SDK stands for software development kit or devkit for short. It’s a set of software tools and programs used by developers to create applications for specific platforms. SDK tools will include a range of things, including libraries, documentation, code samples, processes, and guides that developers can use and integrate into their own apps. SDKs are designed to be used for specific platforms or programming languages. Thus you would need an Android SDK toolkit to build an Android app, an iOS SDK to build an iOS app, a VMware SDK for integrating with the VMware platform, or a Nordic SDK for building Bluetooth or wireless products, and so on. [https://en.wikipedia.org/wiki/Software_development_kit](https://en.wikipedia.org/wiki/Software_development_kit)

### Server-Side Rendering -
To load up a client-side or universal app to HTML on the server. Either using Rehydration or Prerendering the app as static HTML on the server. Teams often factor in the impact of SEO when choosing a strategy for the web. To use SSR or Not. SSR delivers a "complete looking" exprience for crawlers and can interpret code with ease.

### Service Worker -
A service worker is a type of [web worker](https://developer.mozilla.org/en-US/docs/Web/API/Web_Workers_API). It's essentially a JavaScript file that runs separately from the main browser thread, intercepting network requests, caching or retrieving resources from the cache, and delivering push messages.
- Because workers run separately from the main thread, service workers are independent of the application they are associated with. This has several consequences:
- Because the service worker is not blocking (it's designed to be fully asynchronous) synchronous XHR and localStorage cannot be used in a service worker.
The service worker can receive push messages from a server when the app is not active. This lets your app show push notifications to the user, even when it is not open in the browser.

### Singleton Pattern -
The Singleton Pattern limits the number of instances of a particular object to just one. This single instance is called the singleton. Singletons are useful in situations where system-wide actions need to be coordinated from a single central place. An example is a database connection pool. The pool manages the creation, destruction, and lifetime of all database connections for the entire application ensuring that no connections are 'lost'.

Singletons reduce the need for global variables which is particularly important in JavaScript because it limits namespace pollution and associated risk of name collisions. The Module pattern (see our [Dofactory JS](https://www.dofactory.com/products/dofactory-js) product) is JavaScript's manifestation of the Singleton pattern.

Several other patterns, such as, Factory, Prototype, and Façade are frequently implemented as Singletons when only one instance is needed.

Sample code (Javascript)
```js
var Singleton = (function () {
  var instance;

  function createInstance() {
    var object = new Object("I am the instance");
    return object;
  }

  return {
    getInstance: function () {
      if (!instance) {
        instance = createInstance();
      }
      return instance;
    }
  };
})();

function run() {
  var instance1 = Singleton.getInstance();
  var instance2 = Singleton.getInstance();
  alert("Same instance? " + (instance1 === instance2));
}
```

### Source Code -
Any collection of code that is displayed in a human readable format. Source code can be sent to a compiler to be translated into machine code for the CPU to utilize.

### SPA -
Stands for Single Page Application. A web app that loads with a single browser load. While the app can contain multiple "pages", these are either already pre-loaded, and displayed using Javascript; or content is fetched dynamically using an API without loading a new page (a loading icon may be displayed, or the content fetched in the background while the user scrolls)

### String -
A string is a data type used in programming, such as an integer and floating point unit, but is used to represent text rather than numbers. It is comprised of a set of characters that can also contain spaces and numbers. For example, the word "hamburger" and the phrase "I ate 3 hamburgers" are both strings. Even "12345" could be considered a string, if specified correctly. Typically, programmers must enclose strings in quotation marks for the data to be recognized as a string and not a number or variable name.

### Syntactic sugar -
Syntax within a programming language that is designed to make things easier to read or to express.

### Technical debt -
Extra development work that arises when code that is easy to implement in the short run is used instead of applying the best overall solution. If you keep implementing short term solutions, you'll soon be paying a lot of interest (Time, money) when adding new features because the codebase will be a mess.

### **Terminal** or **CLI** -
The place where you type commands directly to the computer. You don’t need this at the beginning, but at least you know what it is.... It looks like a small word document but is black and makes you feel like a hacker. Some people get really excited about it. CLI stands for ‘Command Line Interface’.

For another definition of CLI, see [CLI](#cli--)
### Text editor -
Somewhere that you can write code. Microsoft Word is a text editor. Notepad is a text editor. It is pretty much just somewhere that you can hit the keyboard and stuff appears...
_“We need to access this remotely, do you have your login details?”_

### Transpile -
The process of turning code from one language into another. Examples include: TypeScript transpiled into JavaScript, CoffeeScript transpiled into JavaScript, Earl Grey being transpiled into JavaScript, JavaScript being transpiled into JavaScript. You’ll notice a trend.

### TTFB -
Time to first byte (TTFB) is a measurement used as an indication of the responsiveness of a web server. How fast do you see the page? It measures the duration from the user or client making an HTTP request to the first byte of the page being received by the client's browser. Google Chrome Lighthouse reports can describe TTFB.

### UI -
Stands for User Interface, this is used to describe what the website will generally look like - the buttons and the navigation  bar etc. UI is the _look_ of the site. Linked with UX*

### UX -
Stands for User Experience, and is used to describe the way that a user navigates around and interacts with your site/app. UX is the _feel_ of the site. Linked with **UI**

### **Version Control** or **Source Control** -
A system for managing changes and edits made to a document. Popular version control systems (VCS) include Git and Subversion (SVN).

### Virtual Machine (VM) -
Software that makes it possible to use one computer operating system (like Linux) on a computer running another system (like MacOS). Examples include Virtual Box, Parallels, and VM Ware.

### Web-pack -
web-pack is an open-source JavaScript module bundler. It is a module bundler primarily for JavaScript, but it can transform front-end assets like HTML, CSS, and images if the corresponding loaders are included. web-pack takes modules with dependencies and generates static assets representing those modules.
