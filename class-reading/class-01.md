# Class-01 Reading Notes

## **Chapter 1 - "Structure"**

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
  
 
## **Chapter 8 - "Extra Markup"**
  
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
  
## **Chapter 17 - "HTML5 Layout"**

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
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
