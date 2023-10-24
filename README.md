# assignment-2
Window
The JavaScript window object sits at the top of the JavaScript Object hierarchy and represents the browser window. The window object is supported by all browsers. All global JavaScript objects , functions, and variables automatically become members of the window object. The window is the first thing that gets loaded into the browser . This window object has the majority of the properties like length, inner Width, inner Height, name, if it has been closed, its parents, and more.

The window object represents the current browsing context . It holds things like window.location, window.history, window.screen, window.status, or the window.document . Each browser tab has its own top-level window object. Each of these windows gets its own separate global object. window.window always refers to window, but window.parent and window.top might refer to enclosing windows, giving access to other execution contexts. Moreover, the window property of a window object points to the window object itself.

So the following statements all return the same window object:

window.window
window.window.window
window.window.window.window

Document
The Document interface represents any web page loaded in the browser and serves as an entry point into the web page’s content, which is the DOM tree. When an HTML document is loaded into a web browser , it becomes a document object. It is the root node of the HTML document. The document actually gets loaded inside the window object and has properties available to it like title, URL, cookie, etc. HTML documents, served with the “text/html” content type, also implement the HTMLDocument interface, whereas XML and SVG documents implement the XMLDocument interface.

Screen
Screen is a small information object about physical screen dimensions . It can be used to display screen width, height, colorDepth, pixelDepth etc. It is not mandatory to write window prefix with screen object. It can be written without window prefix.

Properties:
screen.width
screen.height
screen.availWidth
screen.availHeight
screen.colorDepth
screen.pixelDepth

et myResume={
    "basics": {
      "name": "SRINIDHI",
      "email": "srinidhirocks12@gamil.com",
      "phone": 8056293730,
      "degree": "B.E",
      "location": {
        "address": "139/a cv raman road alwarthirunagar",
        "postalCode": 600087,
        "city": "Chennai",
        "state": "Tamilnadu",
        "country": "India"
      },
          
        }
      
      },
    ],
    "education": [
      {
        "institution": "chennai institute of technology",
        "department": "biomedical",
        "studyType": "fulltime",
        "batch start year": 2021,
        "batch end year": 2025,
        "gpa": 8.2,
      }
    ],
    "skills": [
      {
        "python,javascript",
        "level": "beginer",
        "project": [
          "automatic attendance maintaing system using python language"
        ]
      }
    ],
    "languages": [
      {
        "language": "Tamil,Enlish,hindi",
      }
    ],
    "interests": [
      {
        "film making,art,",
      }
    ]
  }
  console.log(myResume);





