# Form Control

#edit

This is how you include form controls in your web page if you decide to use them for capturing information for your visitors.

The `<input>` element is used to create different form controls. The value of the `type` attribute determines what kind of input it will create.

Each form control requires a `name` attribute and the value identifies the form control and is sent along with the information they enter to the server. This is because when users enter information into a form, the server needs to know which form control each piece of data was entered into.

You can include `max-length` attribute to limit the number of characters a user may enter into the text field and the value is the number of characters they may enter.

## text input

When the `type` attribute has a value of text, it creates a single line text input then you can include the `max-length` attribute to limit the number of characters a user may input inside the text field.

```html
<form action="https://www.example.org/login.php" method="post">
	<p>Username:
		<input type="text" name="username" size="15" maxlength="30"/>
	</p>
</form>
```

## password input

When the `type` attribute has a value of `“password”`, it creates a text box that acts just like a single-line text input, except the characters are blocked out. The opening `<input>` tag can also carry `size` and `maxlength` attributes.

```html
<form action="https://www.example.org/login.php" method="post">
	<p>Username:
		<input type="text" name="username" size="15" maxlength="30"/>
	</p>
	<p>Password:
		<input type="password" name="password" size="15" maxlength="30"/>
	</p>
</form>
```

## text area

The `<textarea>` element is used to create a multi-line text input and it has an opening tag and a closing tag.

```html
<form action="https://www.example.org/comments.php" method="post">
	<p>What do you thing of this country</p>
	<textarea name="comments" cols="20" rows="4">Enter Your Comment</textarea>
</form>
```

> [!tip] Use CSS to control the width and height of `<textarea>`.

**OLD CODE**:
- The `cols` attribute indicates how wide the text area should be (measured in number of characters).
- The `row` attribute indicates how many rows the text area should take up vertically.

## radio button

When the `type` attribute’s value is `radio`, it creates a radio button and radio buttons allow users to click just one of a number of options. 

- The value of the `name` attribute should be the same for all the radio buttons.
- The `value` attribute indicates the value that is sent to the server for the option.
- The `check` attribute cab be used to indicate which value should be selected when the page loads and its value is `checked`. Only one radio button in a group should use this attribute.

```html
<form action="https://www.example.org/profile.php" method="post">
	<p>Please select your favourite genre:
		<br>
		<input type="radio" name="genre" value="rock" checked>Rock
		<input type="radio" name="genre" value="pop" checked>Pop
		<input type="radio" name="genre" value="jazz" checked>Jazz
	</p>
</form>
```

## checkbox

When the `type` attribute’s value is `"checkbox"`, it creates a checkbox. Checkboxes allows users to select (and unselect) one or more options.

```html
```