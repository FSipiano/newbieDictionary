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

See [Terminal or Cli](#terminal-or-cli--)

Can also stand for Common Language Infrastructure. A tool, developed by Microsoft, to allow different languages to be understood and interpreted by different computer programs, rather than having to restructure the architecture and build behind it. 

#### Cryptography - 
The art of hiding secrets and researching for secure communications, to protect them from third parties.

#### Directory - 
Another word for folder. 
_”Navigate to the correct directory”_ = go to the right folder.  
 
#### The DOM - 
Stands for Document Object Model. Always in capitals like that. A place in the browser to see a page’s HTML, CSS, and JavaScript all working together like a happy little family. You can type in it and add stuff. Useful when making a website and you want something to look a particular way. 

See [Manipulating the DOM](#manipulating-the-dom--)

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
 - snake_case: Putting an underscore between words to improve readability, and for languages where a hyphen would be interpreted as a subtract operation
    Example:
     - hello_world
     - python_rocks
 - SCREAMING_SNAKE_CASE: snake_case but louder (all caps), often used to easily distinguish macros and constants from variables
    Example:
     - HELLO_WORLD
     - HOST_NAME

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

For the opposite of Local, see [Remote](#remote-)

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

For the opposite of Remote, see [Local](#locallocally-)

#### **Responsive Web Design** - 
The practice of designing websites so that they adapt gracefully to different-sized devices like phones, tablets, wearable devices, etc. If you’re able to visit a website on your phone and it looks just as proportional and seamless as it does on your computer, it’s an example of responsive web design.
  
#### **Source Code** - 
Any collection of code that is displayed in a human readable format. Source code can be sent to a compiler to be translated into machine code for the CPU to utilize. 

#### **SPA** - 
Stands for Single Page Application. A web app that loads with a single browser load. While the app can contain multiple "pages", these are either already pre-loaded, and displayed using Javascript; or content is fetched dynamically using an API without loading a new page (a loading icon may be displayed, or the content fetched in the background while the user scrolls)

#### **Scrum/Agile** - 
Methodical frameworks for organizing, developing, delivering and maintaining software. Scrum and Agile disciplines can be applied to a wide variety of fields but has been a popular choice in software development due to its effective approach to handling very complex tasks. 

#### **Syntactic sugar** - 
Syntax within a programming language that is designed to make things easier to read or to express.

#### **Terminal** or **CLI** - 
The place where you type commands directly to the computer. You don’t need this at the beginning, but at least you know what it is.... It looks like a small word document but is black and makes you feel like a hacker. Some people get really excited about it. CLI stands for ‘Command Line Interface’. 

For another definition of CLI, see [CLI](#cli-)

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
