# Section 4

## Lecture 29

<table> is an html table
	<tr> for each row
		<td> for each element in the table

<thead> and <tbody> are optional tags to segment the table into a header and body. Otherwise the rows will all appear as body rows


> <table border="1">
> <thead>
> 	<tr>
> 		<th>Name</th>
> 		<th>Age</th>
> 		<th>LastRow</th>
> 	</tr>
> </thead>
> <tbody>
> 	<tr>
> 		<td>Red</td>
> 		<td>Orange</td>
> 		<td>Blue</td>
> 	</tr>
> 	<tr>
> 		<td>Red</td>
> 		<td>Orange</td>
> 		<td>Blue</td>
> 	</tr>
> </tbody>
> </table>


## Lecture 32 - Intro to forms

<form>
action="/formsubmitapi.py" attribute. the URL to send form data to
Method="post" type of http request
</form>

GET - retrieve
POST - send data to add or host

<input>
type="text"/"date"/"color"/"file"/"checkbox" - attribute that determines what type of input

See MDN docs for all types and attributes
https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input

-------------

34

Form tags
A form tag is a tag that contains inputs (they are packaged together)

Forms have
- Action - Where the form sends data to
- Method - What HTTP method (get/post)

<form> is a block-level element

If not action= is specified, it will send the request to the same page you are on.

name= attribute adds the form response to the query-string (terrible idea for secure data)


---------

35 - Labels


Labels add captions to individual elements in your form if there is text within the tag. These are used for accessibility and other things.


for= specifies which form element a label is bound to
id= id of the element the label is bound to

id is used by the HTML DOM and style sheets

-----

36 - validations


Validate 'required' form values in HTML (typically not done in HTML)

required - a *boolean attribute* that can be added to the element, specifying that it is required. Request will not be sent until the required field is filled out


type= Checks that the form is filled out in the correct format. E.g. type="email"

------


37 - Dropdowns and radio buttons


radio button - mutually exclusive and required choice
checkbox - multiple or no choices

type="radio"

Use the name attribute on the elements to associate multiple radio buttons

><form>
>    <label for="dogs">Dogs:</label>
>    <input name="petChoice" id="dogs" type="radio">
>
>    <label for="cats">Cats:</label>
>    <input name="petChoice" id="cats" type="radio">
>
>     <button>Go!</button>
></form>


<button> is a special tag that will submit the form when pressed



value= is the value that will appear in the query-string
The name= attribute is the key value in the key-value query-string pair

Dropdown
>    <select name="color">
>        <option>Red</option>
>        <option>Orange</option>
>        <option>Yellow</option>
>        <option>Green</option>
>        <option>Black</option>
>    </select>


Override the value portion of the query=string using value= in dropdown


>    <p>What's your current mood?</p>
>    <select name="color">
>        <option value="sad">:(</option>
>        <option value="crying">:}</option>
>        <option value="happy">:)</option>
>        <option value="frown">:\</option>
>    </select>


<textarea> can be used for larger text inputs

>    <textarea name="paragraph" rows="10" columns="50"></textarea>



-----


38 quiz

email, user, pass are required
try to force password between 5 and 10 characters
Dropdown for birthday (dont' need all days or years)




