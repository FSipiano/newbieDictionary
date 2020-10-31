# newbieDictionary
**I wanted to make this Open Source (definition in the dictionary!) to enable us all to add and learn from each other!
I want YOU to contribute. Click 'fork repository' (button in the top right), make your additions in your 'own version', and then create a pull request (definition below) to put it back into this main version! I'll review it and then add it in** 😄


I have been thinking about making this for some time, but I wanted to make sure that I had enough knowledge about random tech words before I started... 

 

A code/tech dictionary! 

 

Sometimes, (well for me at least) it very much seems that this industry has overcomplicated words and phrases for things _on purpose._ 

You may be learning from someone who has been in the industry for a while, and for them, these words _just make sense_ 

But do they make sense to you, as a newbie? 

Absolutely not 

I have tried to gather a few words/phrases and definitions together here to help you out, and we can add to it as we go along!! 

There are sometimes multiple words for the same thing, again - just to be confusing. I’ve tried to include all definitions that I’ve heard, but please let me know if I’ve missed any!
                                                                             📖


#### A11y - 
A numeronym for accessibility, where the number 11 refers to the number of letters omitted. A11y refers to the accessibility of a computer system to all people, regardless of disability type or severity of impairment.

#### API - 
Stands for Application Programming Interface, which provides a comprehensive layer of communication and callbacks to the original software layer, so that it becomes easier to integrate. Example- The google maps API allows you to integrate their maps to your apps through their API.

#### ASCII - 
Stands for 'American Standard Code for Information Interchange'. It is the set of common characters use in electronic communication, based in English alphabet, numbers, punctuation symbols and non-printing control characters (like Escape, Tabulation, Backspace, End of Line, etc). This standard is the base line to newer sets of characters like UTF-8 standard, that extends ASCII including new characters like Latin or German characters by example.
                                                           
#### Boilerplate (code) - 
The standard code you need to put into your code in order for it to run. An example is frameworks. Let’s take Bootstrap as an example. To use it, you need to copy and paste in a bunch of code that you get from the official website in order for you to be able to use it. Like a template.

#### Callback function - 

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

#### CLI - 
Can also stand for Common Language Infrastructure. A tool, developed by Microsoft, to allow different languages to be understood and interpreted by different computer programs, rather than having to restructure the architecture and build behind it. 

#### Cryptography - 
The art of hiding secrets and researching for secure communications, to protect them from third parties.

#### Directory - 
Another word for folder. 
_”Navigate to the correct directory”_ = go to the right folder.  
 
#### The DOM - 
Always in capitals like that. A place in the browser to see a page’s HTML, CSS, and JavaScript all working together like a happy little family. You can type in it and add stuff. Useful when making a website and you want something to look a particular way. 

#### Destructuring - 
This means to unpack values in a data structure such as an Object or Array.  

#### Environment - 
Where you are working within your computer. For example, if you are making a webpage, your environment would be a **text editor** or **IDE** and the browser window. 

#### Framework - 
A platform for developing software applications. It has rules, instructions and some boundations which makes it different from a library. Since they are often built, tested, and optimized by several experienced software engineers and programmers, software frameworks are versatile, robust, and efficient. It is a language written to help you to write code easier. Often comes with **boilerplate** code to get you started.

#### Function -  
The block of code that you can call by name, a function is independent of an object.

#### Function & variable naming conventions - 
A naming convention is a set of rules for choosing the character sequence to be used for identifiers which denote variables, types, functions, and other entities in source code and documentation.
 - Camel Case: Writing names without spaces or punctuation, indicating the separation of words with a single capitalized letter.
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

#### **Git** - 
The name of a version control system. Involves branches and trees, pushing and pulling. All in all a great time. 

#### **GitHub** - 
The name of a hosting service for storing and interacting with git repositories. GitHub provides additional collaboration tools on top of git, such as Pull Requests, Issues/bug reports, wiki, and other features. Other popular git hosting services include BitBucket and GitLab.

#### An **IDE** - 
Stands for ‘Integrated Development Environment’. It is somewhere that you write code, and has tools to help you write, structure and test it. Build, test, connect to databases, the works! 

#### HTTP - 
HTTP or Hypertext Transfer Protocol is the set of guidelines for transferring files such as texts, videos, sounds, images, and other multimedia files through the World Wide Web. The moment a Web user opens the browser, the user is indirectly making use of HTTP. 

#### HTTPS
Stands for “Hypertext Transfer Protocol Secure” which means the webpage has a special layer of encryption added to hide your personal details and passwords. Hence, if you wish to secure your bank account details at an online shopping site, look for “https” in the URL.

#### **JSON** - 
Stands for JavaScript Object Notation. JSON is a common data format (a way data is written), originally derived from JavaScript, many programming languages now have the ability to use JSON. JSON data types include: number, string, boolean, array, object, or null. Basic JSON might look like this:  

```json
{ 
    "firstName": "Faye", 
    "lastName": "Sipiano", 
    "age": 27, 
    "eyeColor": "blue", 
}
```

#### **Kernel** - 
A piece of software running as a communicator between regular software and hardware, containing all the lower-level functions to talk to the hardware and providing an API for the software to modify the state of hardware interfaces securely. Example - The Linux Kernel

#### **Library** - 
A collection of functions which can be added to your application and the functions called as necessary, just like any other functions in the application. More precisely any object, not only functions can be stored in a library, but the vast majority of libraries only contain functions.

#### **Local/locally** - 
On your computer 
_“You can access it locally”_ 

#### **Method** -  
The block of code that you can call by name that is associated with an object (in javascript, every function treated as object,So in simple words, A method is on an object)

#### **Manipulating the DOM** - 
Just means changing something (usually JavaScript) in the DOM.

#### **Machine Learning** - 
A realm of study within the domain of artificial intelligence that aims to develop techniques in software which allow machines to learn through experience. 

#### **NaN** - 
Stands for 'Not a Number'. Is a number.

#### **Objects** - 
In code, you can create an ‘object’ that you can refer to later, for example you can create a ‘person’ with a first name and last name, an age, and an eye colour. This can then be used again if you wanted to create another ‘person’ 

``var person = {firstName:"Faye", lastName:"Sipiano", age:27, eyeColor:"blue"};`` 

#### **Open source** - 
A project or repository that anyone can request to make changes or updates to. This is a good way to learn. For example, this dictionary is Open Source.
 
#### **Pseudocode** - 
A human-readable explanation of how something should work – the way and order that it runs in. Pseudocode does not have to follow the rules of any programming language. It is a description of what the code in a program is doing so that even non-technical individuals can understand its logic. 

#### **PR** - 
Stands for 'pull request'. Means that you are requesting that the changes or edits you have made be reviewed and eventually merged (in **git**)

#### **PR** - 
Also a marketing term meaning 'Press release'. Means anything going out to be published into the wide world for others to see. You could create a PR for a PR I suppose...

#### **Repository** - 
A house for your code, stored online. Repositories are collections of source code 

#### **Refactor** - 
Means to look over and rewrite your code in a different way. Maybe you learned a better way to do it, so you rewrite it. 
_”I’m going to spend today refactoring old code because I learned so much since I first wrote it!”_ 

#### **Remote** - 
Not on your computer – stored on someone else's machine/server. Usually means you need to log in, through a portal or …... to be able to access it. 

#### **Responsive Web Design** - 
The practice of designing websites so that they adapt gracefully to different-sized devices like phones, tablets, wearable devices, etc. If you’re able to visit a website on your phone and it looks just as proportional and seamless as it does on your computer, it’s an example of responsive web design.
  
#### **Source Code** - 
Any collection of code that is displayed in a human readable format. Source code can be sent to a compiler to be translated into machine code for the CPU to utilize. 

#### **Scrum/Agile** - 
Methodical frameworks for organizing, developing, delivering and maintaining software. Scrum and Agile disciplines can be applied to a wide variety of fields but has been a popular choice in software development due to its effective approach to handling very complex tasks. 

#### **Syntactic sugar** - 
Syntax within a programming language that is designed to make things easier to read or to express.

#### **Terminal** or **CLI** - 
The place where you type commands directly to the computer. You don’t need this at the beginning, but at least you know what it is.... It looks like a small word document but is black and makes you feel like a hacker. Some people get really excited about it. CLI stands for ‘Command Line Interface’. 

#### **Transpile** - 
The process of turning code from one language into another. Examples include: TypeScript transpiled into JavaScript, CoffeeScript transpiled into JavaScript, Earl Grey being transpiled into JavaScript, JavaScript being transpiled into JavaScript. You’ll notice a trend. 

#### **Technical debt** - 
Extra development work that arises when code that is easy to implement in the short run is used instead of applying the best overall solution. If you keep implementing short term solutions, you'll soon be paying a lot of interest (Time, money) when adding new features because the codebase will be a mess.

#### **Text editor** - 
Somewhere that you can write code. Microsoft Word is a text editor. Notepad is a text editor. It is pretty much just somewhere that you can hit the keyboard and stuff appears... 
_“We need to access this remotely, do you have your login details?”_ 

#### **UI** - 
Stands for User Interface, this is used to describe what the website will generally look like - the buttons and the navigation  bar etc. UI is the _look_ of the site. Linked with **UX*

#### **UX** - 
Stands for User Experience, and is used to describe the way that a user navigates around and interacts with your site/app. UX is the _feel_ of the site. Linked with **UI**

#### **Version Control** or **Source Control** - 
A system for managing changes and edits made to a document. Popular version control systems (VCS) include Git and Subversion (SVN).

#### **Virtual Machine (VM)** - 
Software that makes it possible to use one computer operating system (like Linux) on a computer running another system (like MacOS). Examples include Virtual Box, Parallels, and VM Ware.

#### **HTTP Status Codes**

**1xx** - Informational
- **100** - Continue
- **101** - Switching Protocols
- **102** - Processing
- **103** - Early Hints

**2xx** - Success
- **200** - OK
- **201** - Created
- **202** - Accepted
- **203** - Non-Authoritative Information
- **204** - No Content
- **205** - Reset Content
- **206** - Partial Content
- **207** - Multi-Status
- **208** - Already Reported
- **226** - IM Used

**3xx** - Redirection
- **300** - Multiple Choices
- **301** - Moved Permanently
- **302** - Found
- **303** - See Other
- **304** - Not Modified
- **305** - Use Proxy
- **306** - Switch Proxy
- **307** - Temporary Redirect
- **308** - Permanent Redirect

**4xx** - Client Error
- **400** - Bad Request
- **401** - Unauthorized
- **402** - Payment Required
- **403** - Forbidden
- **404** - Not Found
- **405** - Method Not Allowed
- **406** - Not Acceptable
- **407** - Proxy Authentication Required
- **408** - Request Timeout
- **409** - Conflict
- **410** - Gone
- **411** - Length Required
- **412** - Precondition Failed
- **413** - Payload Too Large
- **414** - URI Too Long
- **415** - Unsupported Media Type
- **416** - Range Not Satisfiable
- **417** - Expectation Failed
- **418** - I'm a teapot
- **421** - Misdirected Request
- **422** - Unprocessable Entity
- **423** - Locked
- **424** - Failed Dependency
- **425** - Too Early
- **426** - Upgrade Required
- **428** - Precondition Required
- **429** - Too Many Requests
- **431** - Request Header Fields Too Large
- **451** - Unavailable For Legal Reasons

**5xx** - Server Error (Whoops, backend dev broke something!)
- **500** - Internal Server Error
- **501** - Not Implemented
- **502** - Bad Gateway
- **503** - Service Unavailable
- **504** - Gateway Timeout
- **505** - HTTP Version Not Supported
- **506** - Variant Also Negotiates
- **507** - Insufficient Storage
- **508** - Loop Detected
- **510** - Not Extended
- **511** - Network Authentication Required

A detailed explanation of each status can be found [here](https://en.wikipedia.org/wiki/List_of_HTTP_status_codes).

#### Nextjs - Next.js is a React framework built by Zeit, and according to [nextjs.org](http://nextjs.org/):

With Next.js, server rendering React applications has never been easier, no matter where your data is coming from.

Next.js also supports static exporting, but for the purposes of this post, we are focused on that “server rendering” capability mentioned above.

#### Reactjs - is an open-source, front end, JavaScript library for building user interfaces or UI components. It is maintained by Facebook and a community of individual developers and companies. React can be used as a base in the development of single-page or mobile applications.

####  Namespace (in javascript) - While we are working on web applications using JavaScript functions and files, it would become difficult to challenge code. So to help us manage this code, we have a keyword ‘Namespace’ which will create mini objects of different modules or functionalities to make code readable. JavaScript does not provide Namespace by default but this functionality can be replicated. It is a container providing scope for set of identifiers, type names, functions or variables, and methods, etc. to prevent collisions among them. It can be created with ease, so with minor tweaks, a namespace can be created.

Example: First, we need to initialize an empty Namespace: like so var <namespace> = { };

Then to access variables in the namespace, <namespace>.<identifier>

Similar to Objects in JavaScript, we initialize and access this namespace as objects.

varsampleNamespace = {

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

sampleNamespace. function_one ();

This JavaScript Namespace functionality can be replicated by creating a global object which contains all functions and variables. In modern web applications, different libraries and components are used, so we should have namespace to avoid code ambiguity.

####  Singleton Pattern - Javascript: The Singleton Pattern limits the number of instances of a particular object to just one. This single instance is called the singleton. Singletons are useful in situations where system-wide actions need to be coordinated from a single central place. An example is a database connection pool. The pool manages the creation, destruction, and lifetime of all database connections for the entire application ensuring that no connections are 'lost'.

Singletons reduce the need for global variables which is particularly important in JavaScript because it limits namespace pollution and associated risk of name collisions. The Module pattern (see our [Dofactory JS](https://www.dofactory.com/products/dofactory-js) product) is JavaScript's manifestation of the Singleton pattern.

Several other patterns, such as, Factory, Prototype, and Façade are frequently implemented as Singletons when only one instance is needed.

Sample code:

###**var Singleton = (function () {**
 
###**var instance;**

### **function createInstance() {**

### **var object = new Object("I am the instance");**

### **return object;**

### **}**

### **return {**

### **getInstance: function () {**

### **if (!instance) {**

### **instance = createInstance();**

### **}**

### **return instance;**

### **}**

### **};**

### **})();**

### **function run() {**

### **var instance1 = Singleton.getInstance();**

### **var instance2 = Singleton.getInstance();**

### **alert("Same instance? " + (instance1 === instance2));**

**}**

####  MEAN Stack - MEAN is a free and open-source JavaScript software stack for building dynamic web sites and web applications. The MEAN stack is MongoDB, Express.js, AngularJS, and Node.js.

#### MERN Stack - MERN Stack is a Javascript Stack that is used for easier and faster deployment of full-stack web applications. MERN Stack comprises of 4 technologies namely: MongoDB, Express, React and Node.js.

####  Electron - Electron is a framework for cross-platform desktop applications using Chromium and Node.js.

It’s easy to build cross-platform apps using HTML, CSS, and JavaScript. Your app will be compatible with Mac, Windows, and Linux operating systems right out of the box. 8. Source code - Source code is the list of human-readable instructions that a programmer writes—often in a word processing program—when he is developing a program. The source code is run through a compiler to turn it into machine code, also called object code, that a computer can understand and execute. Object code consists primarily of 1s and 0s, so it isn't human-readable.

#### Web-pack - web-pack is an open-source JavaScript module bundler. It is a module bundler primarily for JavaScript, but it can transform front-end assets like HTML, CSS, and images if the corresponding loaders are included. web-pack takes modules with dependencies and generates static assets representing those modules.

####  Babel: a JavaScript transpiler that converts edge JavaScript into plain old ES5 JavaScript that can run in any browser (even the old ones).
    Currently, most browsers support ES5. ES5 used to be good even though it was so painful to code in [it.Is](http://it.is/) this not reading from inside callback functions? The new version of JavaScript, ES6, also known as ES2015 makes JavaScript great again.

If you want to learn about ES6. All the good features of ES6 accompany one big problem — the majority of browsers don’t fully support them. That’s when Babel comes to its work. Babel may be a JS transpiler that converts new JS code into old ones. It is a really flexible tool in terms of transpiring. One can easily add assets such as es2015, es2016, es2017, or env; so that Babel compiles them to ES5.

#### SDK: SDK stands for software development kit or devkit for short. It’s a set of software tools and programs used by developers to create applications for specific platforms. SDK tools will include a range of things, including libraries, documentation, code samples, processes, and guides that developers can use and integrate into their own apps. SDKs are designed to be used for specific platforms or programming languages. Thus you would need an Android SDK toolkit to build an Android app, an iOS SDK to build an iOS app, a VMware SDK for integrating with the VMware platform, or a Nordic SDK for building Bluetooth or wireless products, and so on. [https://en.wikipedia.org/wiki/Software_development_kit](https://en.wikipedia.org/wiki/Software_development_kit)
 
