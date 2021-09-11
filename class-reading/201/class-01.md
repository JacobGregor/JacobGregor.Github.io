# Class-01 Reading Notes

## **HTML Chapter 1 - "Structure"**

### **Key Concepts:**
Author, pg. 21
> "HTML uses elements to describe the structure of pages"


## Topic: **Element Tags**

-> Tags are used as containers to house the content of our document. anything text within the following <p> </p> for example would be displayed as a paragraph in our web dociument.

-> WIthin an element tag we can also use **attributes**. These provide additional information about our element and the contents within. 
  Ex. Author, pg. 25
> <p lang="en-us"> this paragraph is in english </p> 
-> here the attribute is the "lang=en-us" which is specifying a language for the content of the <p>. 
  
### **Chapter Summary**
-> Key take aways are Tags (Elements) and their structure. <p> </p> tags come in pairs with an opening & cloding tag. 
  
 
## **HTML Chapter 8 - "Extra Markup"**
  
### **Key Concepts**
  
Tags/Elements covered:
 - Comment Tag: !-- --> *Note: you will need < start tag in order for it to register as a comment tag, but i want it to be visible.. ha.
 - Block Eleements: alaways starts on a new line in the browser. 
 - Inline ELements: continue on the same line as their neighboring elements. 
 - div: Groups elements in one block-level box. div should be used to group sections of your web page. Think of div as a container whithin which to house other elements that make up the sections of your webpage. div are manipulated in CSS to adjust their attributes as they relate to the webpage.
 - span: span is best described as the inline version of a div. We can use span to manipulate specific content within elements.
 - Escape Characters: These are the code references for how we use reserved characters. Reference pg 193-194 for a list of escape code references. 
  
Class vs. ID Attributes
-> HTML elements can carry an ID & Class attribute. This allows for specific ID's or classes to be called in CSS to manipulate a specific element by ID or elements by a designated class. **ID is used for specific single element designations while class allows for several elements top be identified and manipulated.**
  
### **Chapter Summary**
  - div & span tags and how we use them within our structure to create containers either in-block or inline. (pg. 187-188)
  - iframe tags allow you to cut windows into your webpage. Think google map squares cut into websites to show a snapshot location. 
  - meta allow you to supply information about the website used behind the scenes to dictate characteristics for your website. 
  - Escape character reference codes (pg. 193-194)
  
## **HTML Chapter 17 - "HTML5 Layout"**

### **Key Concepts**

HTML5 Elements:

- Headers & Footers: Exactly as the name suggests, elements that create a main header (top of webpage) and a footer (bottom of webpage)
- Navigation: the nav element is where we can house our href links. Think of a website with a nav bar that can dfirect you to "about-us", "careers", "profile" with a link that redirects tot he specified location. 
- Article: Acts as a container within a webpage for stand alone content. Articles can be nested within other articles. **(pg. 435)**
- Aside: Aside can be used in conjunction with an article element or live globally outside the article element. When the aside element is used within article the content should be related to that of the article. when it is used outside the article element it acts as a container relative to the entire webpage. **(pg. 436)** 
- Sections: section elements group related content into sections.. Think of a webpage like the new york times. The. ain webpage has multiple headline articles broken into sections on the page. each section contains the article header followed by a snippet of the beggining of the article and finally accompanied by a graphic. So within this section we are able to have article elements, nav elements, headers, ect.. *Note: Section should not be sued as a wrapper for the HTML document, still use a Div to wrap your webpage. **(pg. 437)**
- DIV: Dont forget the trusty div elements! when in doubt wrap that SH*T in a div. *Note: while learning how to use these elements, we should be able to replace div mostly but its still commonly used. 
- **Page 445 - 446 provide an example HTML structure using all of these new elements.**
  
### **Chapter Summary**
- Revisit the new elements covered in this section. we will use them to replace the DIV element in future Hw assignments im sure of it.. 
- Using these elements instead of the standard div is just cleaner and clearer code as opposed to a bunch of divs. 
  
## **HTML Chapter 18 - "Process & Design"**

### **Key Concepts**
Keep these in mind when designing your website:
- Whos is the target audience for your website?
  - Individuals vs. companies?
- Why is this audience visiting your website? 
  - Goals & Motivations: Another way to conceptualize this is the "WHY".
- What are you trying to acheive from visitors to your site? 
  - This is a bit ambiguous as visits can vary greatly, the concept here is to begin to understand the key reasons visits are occuring and the outcomes.
- What information are we missing/need to present to visitors?
  - From here we need to take what we learned from visitors and reasons for visits and make sure we are presenting the apporpriate information to our visitors.
- How often are we getting recurring visits?
  - Is our site generating repeated visits? are we generating unique visits? Here we can begin to understanmd how often we need to rotate information on our site.
- **Site Maps**: We can take all of this information and begin to build our site maps. Similar to a brainstorming or a blueprint. We organize our sight with high level concepts of what information we will need and where. This is the 10k view of our website, just the overarching subjects we will be including.
- **Wireframes**: Sketch of our website. We use wireframes to make sure all of the information we need to include on our website has a rough idea of spacing and location. We build this out to give us a visual reopresentation of our site map prior to building any code. 
- **Visual Hierarchy**: Size, Color, Style and Images. The point of visual hierarchy is to create visual contrast and attract the visitor to points of interest on your site you wish ti attract them to. 

### **Chapter Summary**
1. Understand your target audience
2. Plan out the core information needed on your site (Site Map)
3. build a blueprint of your website to make sure all of the relevant information has a place that flows (Wireframe)
4. Use the concepts of Visual Hierarchy & Groupiong to differentiate key information and attract visitors to popints of interest. 

## **JS Chapter 1 - "The ABC of Programming"**

### **Key Concepts 1/a (Writing a script)**
- **Script**: (Author pg. 14) 
> "A script is a series of instructions that a computer can follow to achieve a goal".
- 3 steps to script writing: Define, Design and Code. 
  - in order to write a script you must uderstand 2 key concepts. Vocabulary & Syntax. How do computers understand and how do they then take your content and follow those instructions. 
 
 ### **Key concepts 1/b (How do computers communicate)**
- **Objects**: Like we place an object tag on physical things in our physical world we do the same with objects in the programming world. Think a Keyboard or a mouse, these are both objects. if they were in our code we could also tag these as objects for the code to hold in memory.
  - **properties**: we can apply properties on our objects, like defining characteristics on real-world objects. These come in the form of names and values.
- **Events**: Events are exactly how they sound, they are interactions with an object. They may change the properties of an object or trigger an event a function has been listening for and waiting to happen.
- **Methods**: Methods are how we change the value of properties assigned to objects. Ex. This may increase or decrease a specified value assigned to an object at a given time. 
- Example of this process: Event (Book room) -> Interact with object (Hotel) -> Method called (makebooking()) -> Adjust object (Hotel) bookings property to reflect a new booking. 

### **Key Concepts 1/c (How to write a script for webpage)**
- How to use Objects & Methods: See final tick from 1/b for a simple action of calling a method. Essentiall we use an abject to call a method() with given parameters (....). 
- This section breaks down how to create a .js file, how to write an example method w/ if{} else{} and then how to embed the script into an HTML document. 

### **Chapter Summary**
- We learned how to write a script and hopw to embed a script into our HTML code.
- We learned abbout Objects, Events and Methods and how these 3 exist with eachother. 
- We saw examples of how to call a method() and how to embed our .js script into an HTML file. 

  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
