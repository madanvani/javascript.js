first day of class:=
# javascript.js
in this your are using javascript
1.JavaScript is used to create interactive websites.it is mainly used for:
 A. client-side validation.
 B. Dynamic drop-down menu.
 C. Display date and time.
 D. Displaying popup windows and dialog boxes.

Second Day of class:==
2. JavaScript code is used in 3 ways they are:=
   A. Head tag:=  in this we are giving code in between Head tag and Head close tag 
      <script type="text/javascript">document.write("madan")</script>
   B. Body tag:=   in this we are giving code in between Body tag starting
      <script type="text/javascript">document.write("madan")</script>
   C. External file:=  in this we are taking externalfile.js in script in Head tag as
      <script type="text/javascript" src="documentfile.js"></script>
      in documentfile.js we are giving document.write("hai hello world")
      note:=1. instead of documentfile.js we can anyother name before .js
            2.  ❤️ document.write is used for showing content in html display as javascript
 
Third day of class:==
 3. Three ways/methods to add content of javascript in Html 
   A.Document.file
   B.Alert (alert box)
   C.InnerHTML  (Formvalidation)
   
    A.Document.write ("Testing Purpose")
    
    B.Alert ("Alert Box") := (it is replaced in document.write as alert("hai hello world") or             window.alert("hai world")
      in this you can see a popup window above the page by displaying what we are add in that               content 
      
    C.InnerHTML:= in this we are writing                                                                      <script  type="text/javascript">document.getElementBYId("demo").innerHTML="hai                    hello world";></script>
            for this we have to write <h1 id="demo"></h1>  above the script  


Fourth day of class:==
 4. Functions in javascript
     in <script>
     function hello(){
    documnet.write("hai madan");
              or
    alert("hello world");
              or
    document.getElementByID("demo").innerHTML="hai world"
    </script>
    if user want to exclude the javascript then you call it as where ever we want as 
    <button onclick="hello()" >clickhere</button>
    <input type="button" value="Clickhere" onclick="hello()" /> it is for calling the hello           world by clicking on clickhere  in button
    
Fifth day of class:=
 5. In functons we have 2 more proprties.
      Perameters:= in this we are learning about parameters
       we are calling multiplication by using functions
        function multiply(number){
          alert("number*number*number");
           }
        <input type="button" value="clickhere" onclick="multipy(2)" /> 
        
        in this we are calling return instead of  onclick 
         
         for thius we are writing 2scripts as 
         1.<scripts> 
           function multiply(number){
           return number*number*number
           }
            </scripts>
         2. <script>
             document.write(multiply(4));
             </script>
             to get output as 64
             Note:= before return we can write any content  but after return intitated if we wr                write anything we dont get answer from the browser because it dont take iut as c                 content
            

Sixth day of class:=
 6. Variables:==(var)
   They are two types:-
    1. Local Variables.
    2. Global Variables.
    
    1.Local Variables:=
       <script>
        function add(){
         var x=20;
         documnet.write("we are adding variables"+x);
         }
         add();
       </script>
       in the above script where add(); is called below the </script> for getting output is c          called as  Local variables.
       
       
     2.Global Variables:=
