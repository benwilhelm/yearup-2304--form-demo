# Form Demo

This is demo code that loosely follows MDN's ["Your First Form" tutorial](https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form)

`index.html` contains the demo form, which has been put into a complete HTML document (ie, `html`, `head`, and `body` elements), and wrapped in a couple of bootstrap classes to make it look a little prettier.

## Form Inputs

MDN has [great documentation](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input) on the various kinds of form inputs and the attributes that are relevant to each. I highly recommend spending some time with this.

## Bootstrap Forms 

Bootstrap provides a number of classes to make forms look nice. Notably, if you give your input elements the class `form-control`, and wrap the label/input pairs in a div with class `form-group`, you end up with the beginnings of a pretty decent-looking form

**Example:**

```html
  <div class="form-group">
    <label for="name">Name:</label>
    <input class="form-control" type="text" id="name" name="user_name" />
  </div>
```


### Documentation 

More Extensive documentation on using Bootstrap to style your forms can be found here:

[Bootstrap Form Component Documentation](https://getbootstrap.com/docs/4.3/components/forms/)