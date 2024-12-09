# Forms

Forms allow users to perform other functions online like registering as a new member on a website, shopping online, signing to newsletters or mailing list.

## Form Controls

There are several types of form controls that you can use to collect information form visitors to your site.

![[form control.svg]]

To differentiate between various pieces of inputted data, information is sent from the browser to the server using *name/value* pairs.

## Form Structure

Form control live inside a `<form>` element and this element should always carry the `action` and `method` attribute, also usually have `id` attribute. 

- The `action` attribute must always be included in the opening `<form>` tag and its value is the URL for the page on the server that will receive the information in the form when it is submitted.

Forms can be sent using:

1. `get`: with this method, the values from the form are added to the end of the URL specified in the `action` attribute. The `get` method is ideal for:

	- short forms (such as search boxes)
	- when you are just retrieving data from the web server.

3. `post`: with this method, the values are sent in what are known as HTTPS headers. This method in ideal for:

	- allows users to upload a file
	- is very long
	- contains sensitive data (such as passwords)
	- adds information to, or deletes information from a database.

>[!info] If the methos attribute is not used, the form data will be sent using the get method.

The syntax:

```html
<form action="https://www.example.com/subscribe.php" method="get">
	<p>This is where the form controls will appear</p>
</form>
```

---

- [[form-control]]

[[html]]
[[attributes]]
[[block and inline]]
