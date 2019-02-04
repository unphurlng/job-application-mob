### index.html

* header
* link to apply

***
### apply.html

* header
* link to index.html
* form container
  * application form
  * submit

NEED:
* name
* value
* key

***

<mark style="background:lightsalmon">Step 1</mark>

index.html  
* link css
* title
* header
* main
  *  h1
  *  link to application page

<mark style="background:lightsalmon">Step 2</mark>

apply.html  
* link css
* title
* header
* main
  * h1
  * link to home

<mark style="background:lightsalmon">Step 3</mark>

* build out form
* need section / div / label / input
  * section - name:
  * section - contact details (in fieldset)
  * section - identity checkboxes
  * section - dropdown
  * section - radio buttons

<mark style="background:lightsalmon">Step 4</mark>
* create variable to grab form node
* create object for form
* addEventListener to variable created above for submit [do event in paren so that you can event.preventDefault]

<mark style="background:lightsalmon">Step 5</mark>  

* access whatever was submitted - get name element [document.getElementById] - goes up at top in globals
* within addEventListener new variable

globals
applicationFormNode  
nameInputNode  
phoneNumberNode  
emailInputNode  
humanNode
beastNode
extraplanarNode




```
applicationFormNode.addEventListener('submit', function(event) {
    event.preventDefault();
    const formSubmission = {
        name;
        phoneNumber;
        email;
    }
});
```
