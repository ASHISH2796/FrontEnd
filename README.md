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
