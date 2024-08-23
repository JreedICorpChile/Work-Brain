
<h1>Hello</h1>
- The Text above was created with `<h1>` tags. 

- These tags are header tags and can range from 1 to 6

- With 1 being the most important and 6 being the least important elements

---

<p> <mark style="background: #D2B3FFA6;">paragraph</mark> </p>

- Once again above is the `<p>` tag, the paragraph tag

- This tag can be used to display content in the body of the document

- You can turn any text into a link, such as the text inside of a `p` element.


---

<mark style="background: #CACFD9A6;">comment</mark>

the <!-- CONTENT HERE --> is used as a comment in the HTML document language


---

<mark style="background: #F038FF;">main</mark>

- We also have the `<main>` tag which is newer to HTML5 and is used to specify a unique group of content on the page


---

<mark style="background: #3772FF;">image</mark>

- The `<img>` tag is a non closing tag known as a **'Void Element'** , it can be used to link to an image

- All `img` elements should have an `alt` attribute. The `alt` attribute's text is used for screen readers to improve accessibility and is displayed if the image fails to load.

- 

---

<mark style="background: #FB8B24;">HTML attributes</mark>

-  special words used inside the opening tag of an element to control the element's behavior. The `src` attribute in an `img` element specifies the image's URL


---

<mark style="background: #C2E812;">anchor</mark>

- You can link to another page with the anchor (`a`) element.

- A link's text must be placed between the opening and closing tags of an anchor (`a`) element.

- You can turn any text into a link, such as the text inside of a `p` element.

- To open links in a new tab, you can use the `target` attribute on the anchor (`a`) element.

- Other types of content can also be turned into a link by wrapping it in anchor tags.
---

<mark style="background: #FB3640;">section</mark>

- The `section` element is used to define sections in a document, such as chapters, headers, footers, or any other sections of the document. It is a semantic element that helps with SEO and accessibility.

---

<mark style="background: #EA2B1F;">unordered lists</mark>

- Can be created with the `<ul>` html element. 

- To list different elements in the unordered list use `<li></li>` for each item in the list


---

<mark style="background: #43BCCD;">figure</mark>

- The `figure` element represents self-contained content and will allow you to associate an image with a caption.

---

<mark style="background: #26F0F1;">form</mark>

- The `form` element is used to get information from a user like their name, email, and other details.

- The `action` attribute indicates where form data should be sent.

- Forms commonly use checkboxes for questions that may have more than one answer. The `input` element with a `type` attribute set to `checkbox` creates a checkbox.

---

<mark style="background: #FDE12D;">input</mark>

- The `input` element allows you several ways to collect data from a web form. Like `img` elements, `input` elements are a void element and do not need closing tags.

- There are many kinds of inputs you can create using the `type` attribute. You can easily create a password field, reset button, or a control to let users select a file from their computer.

- In order for a form's data to be accessed by the location specified in the `action` attribute, you must give the text field a `name` attribute and assign it a value to represent the data being submitted.

- To prevent a user from submitting your form when required information is missing, you need to add the `required` attribute to an `input` element. There's no need to set a value to the `required` attribute. Instead, just add the word `required` to the `input` element, making sure there is space between it and other attributes.

---

<mark style="background: #40F99B;">button</mark>

- The `button` element is used to create a clickable button.

- The default behavior of clicking a form button without any attributes submits the form to the location specified in the form's `action` attribute.

- `input` and `button` elements are inline elements, which don't appear on new lines.

- Add the `type` attribute with the value `submit` to the `button` to make it clear that it is a submit button.

---

<mark style="background: #DDD92A;">label</mark>

- `label` elements are used to help associate the text for an `input` element with the `input` element itself (especially for assistive technologies like screen readers).


---

<mark style="background: #2365a5;">id</mark>

The `id` attribute is used to identify specific HTML elements. Each `id` attribute's value must be unique from all other `id` values for the entire page.

Here is an example of an `input` element with an `id` attribute:

Example

```html
<input id="email">
```


---

<mark style="background: #26F0F1;">name</mark>

To make it so selecting one radio button automatically deselects the other, both buttons must have a `name` attribute with the same value.

Here is an example of two radio buttons with the same `name` attribute:

Example Code

```html
<input type="radio" name="meal"> Breakfast
<input type="radio" name="meal"> Lunch
```


---

<mark style="background: #DDD92A;">fieldset</mark> 

The `fieldset` element is used to group related inputs and labels together in a web form. `fieldset` elements are block-level elements, meaning that they appear on a new line.


---

<mark style="background: #2365a5;">legend</mark>

The `legend` element acts as a caption for the content in the `fieldset` element. It gives users context about what they should enter into that part of the form.


---

<mark style="background: #43BCCD;">for</mark> 

There's another way to associate an `input` element's text with the element itself. You can nest the text within a `label` element and add a `for` attribute with the same value as the `input` element's `id` attribute.

Given an `input` element as below:

Example Code

```html
<input id="breakfast" type="radio" name="meal" value="breakfast">
```

An example of a `label` element that is associated to this `input` element is:

Example Code

```html
<label for="breakfast">Breakfast</label>
```


---

Reset

Navigated to Step 56