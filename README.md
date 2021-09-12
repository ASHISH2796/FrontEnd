# FrontEnd
UI designing
Selectors
 Element selecors html tag eg : p, a,div etc tag
  eg : <p>paragraph</p>
    p {
    color :red //Any css prop can
    }
  
 Class selector :  [class = "className" ]
   eg : <p class ="className">paragraph</p>
    .className {
    color :red //Any css prop can
    }
    
 ID selector :  [ID = "idName" ]
   eg : <p id ="className">paragraph</p>
    #idName {
    color :red //Any css prop can
    }  
    
 Specificity : https://www.w3schools.com/css/css_specificity.asp   
  If there are two or more conflicting CSS rules that point to the same element, the browser follows some rules to determine which one is most specific and therefore wins out.
  high to low specificity 
  inline css > id selectors > class selectors > element selector
  
  high specificity mean more dominant or high weight or priority
  
 Psudeo selector
 After some operation
 
 eg : selector:pseudo-class {
  property: value;
}
 eg : hover
  h2:hover {
  color : red
  }
  on hover on h2 element colo will change 2 red.
  
  first/ last child
  eg : li:first-child / :last-child /nth-child(n) / :only-child {
      //any css prop
    }
where n can be any +ive no.
eg : #id:link {//css}
     #id:visited {//css} 
     
  
  
  Attribute Selector
  img[src="value"] {
  //css property
  }
  
  
  
  Coloring & Formatting
   Opacity
   Gradient
   
 Type of Unit
 Absolute(cm,mm,inc with out any ref around then) and relative (depend on something or screen size or parent element size)
 relative 
   > pixel -px , pt,pc
   > percentage -%
   > em : eg 1.5em  then 1.5 time bigger or size - Specify a certain no of time bigger than size of current font
   > view port - vw - view width or vh view height
 
 Text manipulation
 - text-decoration:
 - text-transform
 - text-align : center/left/right/justify

Font manipulation
- font-size
- font-weight
- font-style
- font-family :  font type to be used eh font-family:'Georgia',serif; -> it mean font will Georgia if any issue with georgia then use serif

------------------ Layout ----------------
for each element we have a box or model 
in each model we have content,padding,Border,margin respectively.

Padding : space between content and border , it basicaly provide extra room/space around content use for internal space
border : divider between padding and margin : eg border: 1px solid
margin : space between border and all other content , use for external space

Float  & Display type
 Block type tag : it has own block space and if added will move other tag or block space nearby
 inline element : will keep it intact eg : span type
 
 float : value  : will move every thing nearby based on value
Display: none : tag will be remove from ui
