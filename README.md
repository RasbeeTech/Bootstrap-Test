# Bootstrap-Test

## Purpose
Create a Bootstrap 4 reference while practicing web-design.

# Bootstrap 4.3.1
## Getting Started  
Include the following code to take advantage of Bootstrap CSS/JS  
```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
    <meta charset="utf-8">
    <!-- meta viewport tag enables touch zooming and proper rendering on mobile devices-->
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <title>Bootstrap Test</title>
    <!-- Bootstrap CSS file -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css">
    <!-- Icons and font styling CSS file -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
    </head>
    <body>
    <h1>Bootstrap Test</h1>
    <div class="container-fluid"> <!-- Acts as the wrapper for the page content-->
    </div>
    <-- Place JS at end for perforomance -->
    <script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js"></script>
    </body>
    </html>
```  

## Table  
1. [Grid-System](#Grid-System)  
2. [Fixed-Layout](#Fixed-Layout)  
3. [Fluid-Layout](#Fluid-Layoutl)  
4. [Responsive-Layout](#Responsive-Layout)  
5. [Typography](#Typography)  
6. [Tables](#Tables)  
7. [Lists](#Lists)  
8. [Forms](#Forms)  
9. [Buttons](#Buttons)  
10. [Images](#Images)  
11. [Cards](#Cards)  
12. [Icons](#Icons)  
13. [Navbars](#Navbars)  
14. [Pagination](#Pagination)  
15. [Badges](#Badges)  
16. [Progress-Bars](#Progress-Bars)  
17. [Spinners](#Spinners)  
18. [Jumbotron](#Jumbotron)  
19. [Helper-Classes](#Helper-Classes)  
20. [Modals](#Modals)  
21. [Dropdowns](#Dropdowns)  
22. [Alerts](#Alerts)  
23. [Accordian](#Accordian)  
24. [Carousal](#Carousal)  

## Content
1. ## Grid-System

The latest Bootstrap 4 version introduces the new mobile-first flexbox grid system that appropriately scales up to 12 columns as the device or viewport size increases.
![alt text](https://github.com/RasbeeTech/Bootstrap-Test/blob/main/images/grid-system-sizing-table.png)  

2. ## Fixed-Layout
With Bootstrap 4 you can still create web page layouts based on fixed number of pixels, however the container width vary depending on the viewport width and the layout is responsive too.
<details>
<summary>View code</summary>

```html
<body>
    <h1>Bootstrap Test</h1>
    <div class="container"> <!-- Acts as the wrapper for the page content-->
    
    </div>
</body>
```

</details>

3. ## Fluid-Layout
<details>
<summary>View code</summary>

```html
<body>
<h1>Bootstrap Test</h1>
<div class="container-fluid"> <!-- Acts as the wrapper for the page content-->

</div>
</body>
```

</details>

4. ## Responsive-Layout
<details>
<summary>View code</summary>

```html
<head>
<!-- meta viewport tag enables touch zooming and proper rendering on mobile devices-->
<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
</head>
```

</details>

5. ## Typography
    ![alt text](https://github.com/RasbeeTech/Bootstrap-Test/blob/main/images/html%20prints/typography.jpg)  
<details>
<summary>View code</summary>
    
```html
<h1>Typography</h1>
<div class="container"> <!-- Acts as the wrapper for the page content-->
    <!--  The small tag-->
    <h2> Fancy display heading
        <small class="text-muted">With faded secondary text</small>
    </h2>

    <!-- Display classes: larger font size but lighter font-weight -->
    <h1 class="display-1">Display Heading 1</h1>
    <h1 class="display-2">Display Heading 2</h1>
    <h1 class="display-3">Display Heading 3</h1>
    <h1 class="display-4">Display Heading 4</h1>

    <!-- Paragraphs -->
    <!-- default font-size: 1rem/16px, line-height: 1.5/20px, line-end: 10px -->
    <p>This is how a normal paragraph looks like in Bootstrap.</p>
    <p class="lead">This is how a paragraph stands out in Bootstrap.</p>

    <!-- Text Alignment -->
    <p class="text-left">Left aligned text.</p>
    <p class="text-center">Center aligned text.</p>
    <p class="text-right">Right aligned text.</p>
    <p class="text-justify">Justified text.</p>

    <!-- Viewport alignment -->
    <p class="text-sm-left">Text aligned to left on small or wider viewports.</p>
    <p class="text-md-left">Text aligned to left on medium or wider viewports.</p>
    <p class="text-lg-left">Text aligned to left on large or wider viewports.</p>
    <p class="text-xl-left">Text aligned to left on extra-large or wider viewports.</p>

    <!-- Text formatting -->
    <p><b>This is bold text</b></p>
    <p><code>This is computer code</code></p>
    <p><em>This is emphasized text</em></p>
    <p><i>This is italic text</i></p>
    <p><mark>This is highlighted text</mark></p>
    <p><small>This is small text</small></p>
    <p><strong>This is strongly emphasized text</strong></p>
    <p>This is <sub>subscript</sub> and <sup>superscript</sup></p>
    <p><ins>This text is inserted to the document</ins></p>
    <p><del>This text is deleted from the document</del></p>

    <!-- Text transformation -->
    <p class="text-lowercase">The quick brown fox jumps over the lazy dog.</p>
    <p class="text-uppercase">The quick brown fox jumps over the lazy dog.</p>
    <p class="text-capitalize">The quick brown fox jumps over the lazy dog.</p>

    <!-- Text coloring -->
    <p class="text-primary">Primary: Please read the instructions carefully before proceeding.</p>
    <p class="text-secondary">Secondary: This is featured has been removed from the latest version.</p>
    <p class="text-success">Success: Your message has been sent successfully.</p>
    <p class="text-info">Info: You must agree with the terms and conditions to complete the sign up process.</p>
    <p class="text-warning">Warning: There was a problem with your network connection.</p>
    <p class="text-danger">Danger: An error has been occurred while submitting your data.</p>
    <p class="text-muted">Muted: This paragraph of text is grayed out.</p>

    <!-- Block quotes -->
    <blockquote class="blockquote">
        <p class="mb-0">The world is a dangerous place to live; not because of the people who are evil, but because of the people who don't do anything about it.</p>
        <footer class="blockquote-footer">by <cite>Albert Einstein</cite></footer>
    </blockquote>

</div>
```
    
</details>

6. ## Tables
    ![alt text](https://github.com/RasbeeTech/Bootstrap-Test/blob/main/images/html%20prints/tables.jpg)  
<details>
<summary>View code</summary>
    
```html
<h1>Tables</h1>
<!-- table-responsive class enables horizontal scrolling on smaller devices-->
<div class="table-responsive{-sm|-md|-lg|-xl}"> <!-- Acts as the wrapper for the page content-->
    <!-- use table classes to change styling:
    .table-dark: inverted or dark table colors,
    .table-striped: alternating zebra stripes,
    .table-bordered: adds border to table,
    .table-borderless: removes all borders,
    .table-hover: highlights row when hovered over,
    .table-sm: cuts table padding in half
    -->
    <table class="table table-striped table-bordered table-sm">
        <!-- use table head classes to style:
        .thead-light: light colored table heads,
        .thead-dark: dark colored table heads,
        -->
        <thead class="thead-dark">
            <tr>
            <th>Row</th>
            <th>First Name</th>
            <th>Last Name</th>
            <th>Email</th>
            </tr>
        </thead>
        <tbody>
            <!-- use table body classes to style:
            .table-primary: blue color,
            .table-secondary: grey color,
            .table-success: green color,
            .table-info: teal color,
            .table-warning: yellow color,
            .table-danger: red color,
            .table-active: light grey color,
            .table-light: light color,
            .table-dark: dark color
            -->
            <tr class="table-primary">
                <td>1</td>
                <td>Clark</td>
                <td>Kent</td>
                <td>clarkkent@mail.com</td>
            </tr>
            <tr class="table-warning">
                <td>2</td>
                <td>John</td>
                <td>Carter</td>
                <td>johncarter@mail.com</td>
            </tr>
            <tr class="table-danger">
                <td>3</td>
                <td>Peter</td>
                <td>Parker</td>
                <td>peterparker@mail.com</td>
            </tr>
        </tbody>
    </table>

</div>
```
    
</details>

7. ## Lists
    ![alt text](https://github.com/RasbeeTech/Bootstrap-Test/blob/main/images/html%20prints/lists.jpg)  
<details>
<summary>View code</summary>
    
```html
<h1>Lists</h1>
<div class="container-fluid"> <!-- Acts as the wrapper for the page content-->
    <!-- ul classes for styling:
    .list-unstyled: immediate children have listing style removed,
    -->
    <ul class="list-inline">
        <li>Home</li>
        <li>Products
            <ul>
                <li>Gadgets</li>
                <li>Accessories</li>
            </ul>
        </li>
        <li>About Us</li>
        <li>Contact</li>
    </ul>
    <!-- horizontal list example -->
    <!-- list styling:
    .list-inline: horizontal list (must add .list-inline-item to all <li> items)
    -->
    <ul class="list-inline">
        <li class="list-inline-item">Home</li>
        <li class="list-inline-item">Products</li>
        <li class="list-inline-item">About Us</li>
        <li class="list-inline-item">Contact</li>
    </ul>
    <!-- horizontal definition lists -->
    <dl class="row">
        <dt class="col-sm-3">User Agent</dt>
        <dd class="col-sm-9">An HTML user agent is any device that interprets HTML documents.</dd>
        <dt class="col-sm-3 text-truncate">Client-side Scripting</dt>
        <dd class="col-sm-9">Client-side scripting generally refers to the category of computer programs on the web that are executed by the user's web browser.</dd>
        <dt class="col-sm-3">Document Tree</dt>
        <dd class="col-sm-9">The tree of elements encoded in the source document.</dd>
    </dl>
    <!-- List Groups -->
    <!-- <ul> has .list-group class and all contained <li> use .list-group-item class-->
    <ul class="list-group">
        <li class="list-group-item">Pictures</li>
        <li class="list-group-item">Documents</li>
        <li class="list-group-item">Music</li>
        <li class="list-group-item">Videos</li>
    </ul>
    <!-- hyper linking list items with styling -->
    <!-- icon and badge styling requires: font-awesome.min.css -->
    <div class="list-group">
        <a href="#" class="list-group-item list-group-item-action active">
            <i class="fa fa-home"></i> Home
        </a>
        <a href="#" class="list-group-item list-group-item-action">
            <i class="fa fa-camera"></i> Pictures <span class="badge badge-pill badge-primary pull-right">145</span>
        </a>
        <a href="#" class="list-group-item list-group-item-action">
            <i class="fa fa-music"></i> Music <span class="badge badge-pill badge-primary pull-right">50</span>
        </a>
        <a href="#" class="list-group-item list-group-item-action">
            <i class="fa fa-film"></i> Videos <span class="badge badge-pill badge-primary pull-right">8</span>
        </a>
    </div>

</div>
```
    
</details>

8. ## Forms
    ![alt text](https://github.com/RasbeeTech/Bootstrap-Test/blob/main/images/html%20prints/forms.jpg)  
<details>
<summary>View code</summary>
    
```html
<h1>Forms</h1>
<div class="container-fluid"> <!-- Acts as the wrapper for the page content-->
    <!--  form controls default: left aligned-->
    <!-- <input>, <textarea>, and <select> require the class .form-control for general styling-->
    <form>
        <div class="form-group">
            <label for="inputEmail">Email</label>
            <input type="email" class="form-control" id="inputEmail" placeholder="Email">
        </div>
        <div class="form-group">
            <label for="inputPassword">Password</label>
            <input type="password" class="form-control" id="inputPassword" placeholder="Password">
        </div>
        <div class="form-group">
            <label class="form-check-label"><input type="checkbox"> Remember me</label>
        </div>
        <button type="submit" class="btn btn-primary">Sign in</button>
    </form>
    <hr>
    <!-- horizontal form layout example -->
    <form>
        <div class="form-group row">
            <label for="inputEmail" class="col-sm-2 col-form-label">Email</label>
            <div class="col-sm-10">
                <input type="email" class="form-control" id="inputEmail" placeholder="Email">
            </div>
        </div>
        <div class="form-group row">
            <label for="inputPassword" class="col-sm-2 col-form-label">Password</label>
            <div class="col-sm-10">
                <input type="password" class="form-control" id="inputPassword" placeholder="Password">
            </div>
        </div>
        <div class="form-group row">
            <div class="col-sm-10 offset-sm-2">
                <label class="form-check-label"><input type="checkbox"> Remember me</label>
            </div>
        </div>
        <div class="form-group row">
            <div class="col-sm-10 offset-sm-2">
                <button type="submit" class="btn btn-primary">Sign in</button>
            </div>
        </div>
    </form>
    <hr>
    <!-- inline form layout -->
    <form class="form-inline">
        <div class="form-group mr-2">
            <label class="sr-only" for="inputEmail">Email</label>
            <input type="email" class="form-control" id="inputEmail" placeholder="Email">
        </div>
        <div class="form-group mr-2">
            <label class="sr-only" for="inputPassword">Password</label>
            <input type="password" class="form-control" id="inputPassword" placeholder="Password">
        </div>
        <div class="form-group mr-2">
            <label><input type="checkbox" class="mr-1"> Remember me</label>
        </div>
        <button type="submit" class="btn btn-primary">Sign in</button>
    </form>
    <hr>
    <!-- static form layout -->
    <form>
        <div class="form-group row">
            <label for="inputEmail" class="col-sm-2 col-form-label">Email</label>
            <div class="col-sm-10">
                <input type="text" readonly class="form-control-plaintext" id="inputEmail" value="peterparker@example.com">
            </div>
        </div>
        <div class="form-group row">
            <label for="inputPassword" class="col-sm-2 col-form-label">Password</label>
            <div class="col-sm-10">
                <input type="password" class="form-control" id="inputPassword" placeholder="Password">
            </div>
        </div>
        <div class="form-group row">
            <div class="col-sm-10 offset-sm-2">
                <div class="checkbox">
                    <label><input type="checkbox"> Remember me</label>
                </div>
            </div>
        </div>
        <div class="form-group row">
            <div class="col-sm-10 offset-sm-2">
                <button type="submit" class="btn btn-primary">Sign in</button>
            </div>
        </div>
    </form>
    <hr>
    <!-- Vertically stacked checkboxes -->
    <!-- .d-block class for vertically aligning -->
    <div class="form-group">
        <label class="d-block">
            <input type="checkbox" class="mr-1" name="sports"> Cricket
        </label>
        <label class="d-block">
            <input type="checkbox" class="mr-1" name="sports"> Football
        </label>
        <label class="d-block">
            <input type="checkbox" class="mr-1" name="sports"> Tennis
        </label>
    </div>
    <!-- Vertically stacked radios -->
    <div class="form-group">
        <label class="d-block">
            <input type="radio" class="mr-1" name="gender"> Male
        </label>
        <label class="d-block">
            <input type="radio" class="mr-1" name="gender"> Female
        </label>
    </div>
    <hr>
    <!-- Inline checkboxes -->
    <div class="form-group">
        <label class="mr-3">
            <input type="checkbox" class="mr-1" name="sports"> Cricket
        </label>
        <label class="mr-3">
            <input type="checkbox" class="mr-1" name="sports"> Football
        </label>
        <label class="mr-3">
            <input type="checkbox" class="mr-1" name="sports"> Tennis
        </label>
    </div>
    <!-- Inline radios -->
    <div class="form-group">
        <label class="mr-3">
            <input type="radio" class="mr-1" name="gender"> Male
        </label>
        <label class="mr-3">
            <input type="radio" class="mr-1" name="gender"> Female
        </label>
    </div>
    <!-- disable form controls -->
    <!-- add 'Disabled' to attribute -->
    <!-- add 'readonly' attribute -->
    <input type="text" class="form-control mb-2" placeholder="Disabled input" disabled>
    <textarea class="form-control mb-2" placeholder="Disabled textarea" disabled></textarea>
    <select id="disabledSelect" class="form-control" disabled>
        <option>Disabled select</option>
    </select>
    <hr>
    <!-- column sizing -->
    <div class="form-row">
        <div class="form-group col-sm-6">
            <label for="inputCity">City</label>
            <input type="text" class="form-control" id="inputCity">
        </div>
        <div class="form-group col-sm-4">
            <label for="inputState">State</label>
            <select id="inputState" class="form-control">
                <option>Select</option>
            </select>
        </div>
        <div class="form-group col-sm-2">
            <label for="inputZip">Zip</label>
            <input type="text" class="form-control" id="inputZip">
        </div>
    </div>
    <!-- height sizing -->
    <form>
        <div class="form-group row">
            <label class="col-sm-2 col-form-label col-form-label-lg">Email</label>
            <div class="col-sm-10">
                <input type="email" class="form-control form-control-lg" placeholder="Large input">
            </div>
        </div>
        <div class="form-group row">
            <label class="col-sm-2 col-form-label">Email</label>
            <div class="col-sm-10">
                <input type="email" class="form-control" placeholder="Default input">
            </div>
        </div>
        <div class="form-group row">
            <label class="col-sm-2 col-form-label">Email</label>
            <div class="col-sm-10">
                <input type="email" class="form-control form-control-sm" placeholder="Small input">
            </div>
        </div>
        <hr>
        <div class="form-group row">
            <label class="col-sm-2 col-form-label col-form-label-lg">State</label>
            <div class="col-sm-10">
                <select class="form-control form-control-lg">
                    <option>Large select</option>
                </select>
            </div>
        </div>
        <div class="form-group row">
            <label class="col-sm-2 col-form-label">State</label>
            <div class="col-sm-10">
                <select class="form-control">
                    <option>Default select</option>
                </select>
            </div>
        </div>
        <div class="form-group row">
            <label class="col-sm-2 col-form-label col-form-label-sm">State</label>
            <div class="col-sm-10">
                <select class="form-control form-control-sm">
                    <option>Small select</option>
                </select>
            </div>
        </div>
    </form>
    <hr>
    <!-- help text around form controls -->
    <div class="form-group">
        <label>Password</label>
        <input type="password" class="form-control">
        <!-- help text can be put in-line with just <small> tag -->
        <small class="form-text text-muted">
            Your password must be 8-20 characters long, contain letters, numbers and special characters, but must not contain spaces.
        </small>
    </div>
    <hr>
    <!-- form validation -->
    <!-- applied with CSS :invalid and :valid pseudo-classes -->
    <form class="needs-validation" novalidate>
        <div class="form-group">
            <label for="inputEmail">Email</label>
            <input type="email" class="form-control" id="inputEmail" placeholder="Email" required>
            <div class="invalid-feedback">Please enter a valid email address.</div>
        </div>
        <div class="form-group">
            <label for="inputPassword">Password</label>
            <input type="password" class="form-control" id="inputPassword" placeholder="Password" required>
            <div class="invalid-feedback">Please enter your password to continue.</div>
        </div>
        <div class="form-group">
            <label class="form-check-label"><input type="checkbox"> Remember me</label>
        </div>
        <button type="submit" class="btn btn-primary">Sign in</button>
    </form>
    <!-- javascript code to test validation above ^ -->
    <script>
        // Self-executing function
        (function() {
            'use strict';
            window.addEventListener('load', function() {
                // Fetch all the forms we want to apply custom Bootstrap validation styles to
                var forms = document.getElementsByClassName('needs-validation');
                // Loop over them and prevent submission
                var validation = Array.prototype.filter.call(forms, function(form) {
                    form.addEventListener('submit', function(event) {
                        if (form.checkValidity() === false) {
                            event.preventDefault();
                            event.stopPropagation();
                        }
                        form.classList.add('was-validated');
                    }, false);
                });
            }, false);
        })();
    </script>
    <hr>
    <!-- full form example -->
    <!-- supports all html5 input types including:  datetime, number, email, url, search, range, color, and url-->
    <form>
    <div class="form-group row">
        <label class="col-sm-3 col-form-label" for="firstName">First Name:</label>
        <div class="col-sm-9">
            <input type="text" class="form-control" id="firstName" placeholder="First Name" required>
        </div>
    </div>
    <div class="form-group row">
        <label class="col-sm-3 col-form-label" for="lastName">Last Name:</label>
        <div class="col-sm-9">
            <input type="text" class="form-control" id="lastName" placeholder="Last Name" required>
        </div>
    </div>
    <div class="form-group row">
        <label class="col-sm-3 col-form-label" for="inputEmail">Email Address:</label>
        <div class="col-sm-9">
            <input type="email" class="form-control" id="inputEmail" placeholder="Email Address" required>
        </div>
    </div>
    <div class="form-group row">
        <label class="col-sm-3 col-form-label" for="phoneNumber">Mobile Number:</label>
        <div class="col-sm-9">
            <input type="number" class="form-control" id="phoneNumber" placeholder="Phone Number" required>
        </div>
    </div>
    <div class="form-group row">
        <label class="col-sm-3 col-form-label">Date of Birth:</label>
        <div class="col-sm-3">
            <select class="custom-select">
                <option>Date</option>
            </select>
        </div>
        <div class="col-sm-3">
            <select class="custom-select">
                <option>Month</option>
            </select>
        </div>
        <div class="col-sm-3">
            <select class="custom-select">
                <option>Year</option>
            </select>
        </div>
    </div>
    <div class="form-group row">
        <label class="col-sm-3 col-form-label" for="postalAddress">Postal Address:</label>
        <div class="col-sm-9">
            <textarea rows="3" class="form-control" id="postalAddress" placeholder="Postal Address" required></textarea>
        </div>
    </div>
    <div class="form-group row">
        <label class="col-sm-3 col-form-label" for="ZipCode">Zip Code:</label>
        <div class="col-sm-9">
            <input type="text" class="form-control" id="ZipCode" placeholder="Zip Code" required>
        </div>
    </div>
    <div class="form-group row">
        <label class="col-sm-3 col-form-label">Gender:</label>
        <div class="col-sm-9 mt-2">
            <label class="mb-0 mr-3">
                <input type="radio" class="mr-1" name="gender"> Male
            </label>
            <label class="mb-0 mr-3">
                <input type="radio" class="mr-1" name="gender"> Female
            </label>
        </div>
    </div>
    <div class="form-group row">
        <div class="col-sm-9 offset-sm-3">
            <label class="checkbox-inline">
                <input type="checkbox" class="mr-1" value="agree"> I agree to the <a href="#">Terms and Conditions</a>.
            </label>
        </div>
    </div>
    <div class="form-group row">
        <div class="col-sm-9 offset-sm-3">
            <input type="submit" class="btn btn-primary" value="Submit">
            <input type="reset" class="btn btn-secondary" value="Reset">
        </div>
    </div>
    </form>
</div>
```
    
</details>

9. ## Buttons
    ![alt text](https://github.com/RasbeeTech/Bootstrap-Test/blob/main/images/html%20prints/buttons.jpg)  
<details>
<summary>View code</summary>
    
```html
<h1>Buttons</h1>
<div class="container-fluid"> <!-- Acts as the wrapper for the page content-->
  <!-- button classes -->
  <button type="button" class="btn btn-primary">Primary</button>
  <button type="button" class="btn btn-secondary">Secondary</button>
  <button type="button" class="btn btn-success">Success</button>
  <button type="button" class="btn btn-danger">Danger</button>
  <button type="button" class="btn btn-warning">Warning</button>
  <button type="button" class="btn btn-info">Info</button>
  <button type="button" class="btn btn-dark">Dark</button>
  <button type="button" class="btn btn-light">Light</button>
  <button type="button" class="btn btn-link">Link</button>
  <hr>
  <!-- button outlining -->
  <button type="button" class="btn btn-outline-primary">Primary</button>
  <button type="button" class="btn btn-outline-secondary">Secondary</button>
  <button type="button" class="btn btn-outline-success">Success</button>
  <button type="button" class="btn btn-outline-danger">Danger</button>
  <button type="button" class="btn btn-outline-warning">Warning</button>
  <button type="button" class="btn btn-outline-info">Info</button>
  <button type="button" class="btn btn-outline-dark">Dark</button>
  <button type="button" class="btn btn-outline-light">Light</button>
  <hr>
  <!-- button sizing -->
  <button type="button" class="btn btn-primary btn-lg">Large</button>
  <button type="button" class="btn btn-primary">Default</button>
  <button type="button" class="btn btn-primary btn-sm">Small</button>
  <hr>
  <!-- block buttons cover full width: use to .btn-block class-->
  <button type="button" class="btn btn-primary btn-lg btn-block">Block level button</button>
  <button type="button" class="btn btn-secondary btn-lg btn-block">Block level button</button>
  <hr>
  <!-- disabled buttons -->
  <button type="button" class="btn btn-primary btn-lg" disabled>Primary button</button>
  <button type="button" class="btn btn-secondary btn-lg" disabled>Button</button>
  <hr>
  <!-- spinner buttons -->
  <button type="button" class="btn btn-primary" disabled>
      <span class="spinner-border spinner-border-sm"></span>
  </button>
  <button type="button" class="btn btn-primary" disabled>
      <span class="spinner-border spinner-border-sm"></span> Loading...
  </button>
  <button type="button" class="btn btn-primary" disabled>
      <span class="spinner-grow spinner-grow-sm"></span> Loading...
  </button>
  <hr>
  <h2>Button Groups</h2>
  <!-- Button Groups -->
  <div class="btn-group">
      <button type="button" class="btn btn-primary">Home</button>
      <button type="button" class="btn btn-primary">About</button>
      <button type="button" class="btn btn-primary">Services</button>
  </div>
  <hr>
  <!-- Button toolbar -->
  <div class="btn-group mr-2">
      <button type="button" class="btn btn-primary">
          <i class="fa fa-font"></i>
      </button>
      <button type="button" class="btn btn-primary">
          <i class="fa fa-bold"></i>
      </button>
      <button type="button" class="btn btn-primary">
          <i class="fa fa-italic"></i>
      </button>
  </div>
  <div class="btn-group mr-2">
      <button type="button" class="btn btn-primary">
          <i class="fa fa-align-left"></i>
      </button>
      <button type="button" class="btn btn-primary">
          <i class="fa fa-align-center"></i>
      </button>
      <button type="button" class="btn btn-primary">
          <i class="fa fa-align-right"></i>
      </button>
      <button type="button" class="btn btn-primary">
          <i class="fa fa-align-justify"></i>
      </button>
  </div>
  <div class="btn-group">
      <button type="button" class="btn btn-primary">
          <i class="fa fa-undo"></i>
      </button>
  </div>
  <hr>
  <!-- Button group sizing -->
  <div class="btn-group mb-2 btn-group-lg">
      <button type="button" class="btn btn-primary">Home</button>
      <button type="button" class="btn btn-primary">About</button>
      <button type="button" class="btn btn-primary">Services</button>
  </div>
  <br>
  <div class="btn-group mb-2">
      <button type="button" class="btn btn-primary">Home</button>
      <button type="button" class="btn btn-primary">About</button>
      <button type="button" class="btn btn-primary">Services</button>
  </div>
  <br>
  <div class="btn-group btn-group-sm">
      <button type="button" class="btn btn-primary">Home</button>
      <button type="button" class="btn btn-primary">About</button>
      <button type="button" class="btn btn-primary">Services</button>
  </div>
  <hr>
  <!-- nesting button groups -->
  <div class="btn-group">
      <a href="#" class="btn btn-primary">Home</a>
      <a href="#" class="btn btn-primary">About</a>
      <div class="btn-group">
          <a href="#" class="btn btn-primary dropdown-toggle" data-toggle="dropdown">Services</a>
          <div class="dropdown-menu">
              <a class="dropdown-item" href="#">Web Design</a>
              <a class="dropdown-item" href="#">Web Development</a>
          </div>
      </div>
  </div>
  <hr>
  <!-- vertical button groups -->
  <div class="btn-group-vertical">
      <a href="#" class="btn btn-primary">Home</a>
      <a href="#" class="btn btn-primary">About</a>
      <div class="btn-group">
          <a href="#" class="btn btn-primary dropdown-toggle" data-toggle="dropdown">Services</a>
          <div class="dropdown-menu">
              <a class="dropdown-item" href="#">Web Design</a>
              <a class="dropdown-item" href="#">Web Development</a>
          </div>
      </div>
  </div>
  <hr>
  <!-- justifying button groups -->
  <div class="btn-group d-flex">
      <button type="button" class="btn btn-primary">Home</button>
      <button type="button" class="btn btn-primary">About</button>
      <button type="button" class="btn btn-primary">Services</button>
  </div>

</div>
```
    
</details>

10. ## Images
    ![images.jpeg](https://github.com/RasbeeTech/Bootstrap-Test/blob/main/images/html%20prints/images.jpg)  
<details>
<summary>View code</summary>
    
```html
<h1>Images</h1>
<div class="container-fluid"> <!-- Acts as the wrapper for the page content-->
  <!-- Image styling:
  .img-fluid: responsive web design (max-width: 100%, height: auto)
  -->
  <img src="images/avatar.svg" class="rounded" alt="Rounded Image">
  <img src="images/avatar.svg" class="rounded-circle" alt="Circular Image">
  <img src="images/avatar.svg" class="img-thumbnail" alt="Thumbnail Image">
  <hr>
  <!-- Image alignment-->
  <!-- Horizontal alignment using float classes -->
  <div class="box clearfix">
      <img src="images/avatar.svg" class="pull-left" alt="Sample Image">
      <img src="images/avatar.svg" class="pull-right" alt="Sample Image">
  </div>

  <!-- Left alignment using text alignment classes -->
  <div class="box text-left">
      <img src="images/avatar.svg" alt="Sample Image">
  </div>

  <!-- Right alignment using text alignment classes -->
  <div class="box text-right">
      <img src="images/avatar.svg" alt="Sample Image">
  </div>

  <!-- Center alignment using text alignment classes -->
  <div class="box text-center">
      <img src="images/avatar.svg" alt="Sample Image">
  </div>

  <!-- Center alignment of block-level image using auto margin -->
  <div class="box">
      <img src="images/avatar.svg" class="d-block mx-auto" alt="Sample Image">
  </div>
</div>
```
    
</details>

11. ## Cards
    ![alt text](https://github.com/RasbeeTech/Bootstrap-Test/blob/main/images/html%20prints/cards.jpg)  
<details>
<summary>View code</summary>
    
```html
<h1>Cards</h1>
<div class="container-fluid"> <!-- Acts as the wrapper for the page content-->
  <!-- Cards -->
  <div class="card" style="width: 300px;">
      <img src="images/avatar.svg" class="card-img-top" alt="...">
      <div class="card-body text-center">
          <h5 class="card-title">Alice Liddel</h5>
          <p class="card-text">Alice is a freelance web designer and developer based in London. She is specialized in HTML5, CSS3, JavaScript, Bootstrap, etc.</p>
          <a href="#" class="btn btn-primary">View Profile</a>
      </div>
  </div>
  <hr>
  <!-- Body-only card -->
  <div class="card">
      <div class="card-body">This is some text within a padded box.</div>
  </div>
  <hr>
  <!-- card with header and footer -->
  <div class="card text-center">
      <div class="card-header">Featured</div>
      <div class="card-body">
          <h5 class="card-title">NASA launches solar probe</h5>
          <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam eu sem tempor, varius quam at, luctus dui. Mauris magna metus, dapibus nec turpis vel, semper malesuada ante.</p>
          <a href="#" class="btn btn-primary">Know more</a>
      </div>
      <div class="card-footer text-muted">2 days ago</div>
  </div>
  <hr>
  <!-- List groups in card -->
  <div class="card" style="width: 18rem;">
      <div class="card-header">Featured</div>
      <ul class="list-group list-group-flush">
          <li class="list-group-item">Cras justo odio</li>
          <li class="list-group-item">Dapibus ac facilisis in</li>
          <li class="list-group-item">Vestibulum at eros</li>
      </ul>
      <div class="card-body">
          <a href="#" class="card-link">Add More</a>
          <a href="#" class="card-link">Share</a>
      </div>
  </div>
  <hr>
  <!-- Mix and match -->
  <div class="card" style="width: 300px;">
      <img src="images/avatar.svg" class="w-100 border-bottom" alt="Rounded Image">
      <div class="card-body">
          <h5 class="card-title">Card title</h5>
          <p class="card-text">Pulvinar leo id risus pellentesque el vestibulum. Sed diam libero egetve sodales sapien vel, aliquet nibhte bibendum enim porttitor orci.</p>
      </div>
      <ul class="list-group list-group-flush">
          <li class="list-group-item">Cras justo odio</li>
          <li class="list-group-item">Dapibus ac facilisis in</li>
          <li class="list-group-item">Vestibulum at eros</li>
      </ul>
      <div class="card-body">
          <a href="#" class="card-link">Card link</a>
          <a href="#" class="card-link">Another link</a>
      </div>
  </div>
  <hr>
  <!-- Background color for cards -->
  <!-- card colors:
  .bg-primary,
  .bg-secondary,
  .bg-success,
  .bg-danger,
  .bg-warning,
  .bg-info,
  .bg-dark,
  .bg-light
  -->
  <div class="row">
    <div class="col-sm-6">
        <div class="card text-white bg-warning mb-4">
            <div class="card-body">
                <h5 class="card-title">Primary card title</h5>
                <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam eu sem tempor.</p>
            </div>
        </div>
    </div>
  </div>
  <hr>
  <!-- card borders and text styling:
  .border/text-primary,
  .border/text-secondary,
  .border/text-success,
  .border/text-danger,
  .border/text-warning,
  .border/text-info,
  .border/text-dark,
  .border/text-light
  -->
  <div class="row">
    <div class="col-sm-6">
        <div class="card border-primary mb-4">
            <div class="card-body text-primary">
                <h5 class="card-title">Primary card title</h5>
                <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam eu sem tempor.</p>
            </div>
        </div>
    </div>
  </div>
  <hr>
  <h2> Card Layout </h2>
  <!-- Card Groups (uses display: flex) -->
  <div class="card-group">
      <div class="card">
          <img src="images/avatar.svg" class="card-img-top" alt="...">
          <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam eu sem tempor.</p>
          </div>
          <div class="card-footer">
              <small class="text-muted">Last updated 3 mins ago</small>
          </div>
      </div>
      <div class="card">
          <img src="images/avatar.svg" class="card-img-top" alt="...">
          <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p class="card-text">Vestibulum id metus ac nisl bibendum nibh scelerisque non purus in suspendisse.</p>
          </div>
          <div class="card-footer">
              <small class="text-muted">Last updated 3 mins ago</small>
          </div>
      </div>
      <div class="card">
          <img src="images/avatar.svg" class="card-img-top" alt="...">
          <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p class="card-text">Pulvinar leo id risus enim. Bibendum varius tincidunt pellentesque malesuada in.</p>
          </div>
          <div class="card-footer">
              <small class="text-muted">Last updated 3 mins ago</small>
          </div>
      </div>
  </div>
  <hr>
  <!-- Card decks: seperation between cards -->
  <div class="card-deck">
      <div class="card">
          <img src="images/avatar.svg" class="card-img-top" alt="...">
          <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam eu sem tempor.</p>
          </div>
          <div class="card-footer">
              <small class="text-muted">Last updated 3 mins ago</small>
          </div>
      </div>
      <div class="card">
          <img src="images/avatar.svg" class="card-img-top" alt="...">
          <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p class="card-text">Vestibulum id metus ac nisl bibendum nibh scelerisque non purus in suspendisse.</p>
          </div>
          <div class="card-footer">
              <small class="text-muted">Last updated 3 mins ago</small>
          </div>
      </div>
      <div class="card">
          <img src="images/avatar.svg" class="card-img-top" alt="...">
          <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p class="card-text">Pulvinar leo id risus enim. Bibendum varius tincidunt pellentesque malesuada in.</p>
          </div>
          <div class="card-footer">
              <small class="text-muted">Last updated 3 mins ago</small>
          </div>
      </div>
  </div>
  <hr>
  <!-- Card columns -->
  <div class="card-columns">
  <div class="card">
      <img src="images/thumbnail.svg" class="card-img-top" alt="...">
      <div class="card-body">
          <h5 class="card-title">Card title</h5>
          <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipi elit. Nam eu sem tempor, varius quam at, luctus dui. Mauris magna metus.</p>
          <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
      </div>
  </div>
  <div class="card p-3">
      <blockquote class="blockquote mb-0 card-body">
          <p>Nam eget purus consectetur in vehicula. Nullamr ultrices nisl risus, viverra libero.</p>
          <footer class="blockquote-footer">
              <small class="text-muted">Someone famous</small>
          </footer>
      </blockquote>
  </div>
  <div class="card">
      <img src="images/thumbnail.svg" class="card-img-top" alt="...">
      <div class="card-body">
          <h5 class="card-title">Card title</h5>
          <p class="card-text">Vestibulum id metus ac nisl bibendum scelerisque non dignissim purus.</p>
          <p class="card-text"><small class="text-muted">Last updated 2 mins ago</small></p>
      </div>
  </div>
  <div class="card bg-primary text-white text-center p-3">
      <blockquote class="blockquote mb-0">
          <p>Pulvinar leo risus vestibulum. Sed diam on sodales eget.</p>
          <footer class="blockquote-footer text-white">
              <small>Someone famous</small>
          </footer>
      </blockquote>
  </div>
  <div class="card text-center">
      <div class="card-body">
          <h5 class="card-title">Card title</h5>
          <p class="card-text">Enim arcu, interdum dignissim venenatis velc.</p>
          <p class="card-text"><small class="text-muted">Last updated 1 mins ago</small></p>
      </div>
  </div>
  <div class="card">
      <img src="images/thumbnail.svg" class="card-img-top" alt="...">
  </div>
  <div class="card p-3 text-right">
      <blockquote class="blockquote mb-0">
          <p>Quis quam ut magna consequat faucibus. Pellentesque eget nisi suscipit tincidunt. Pellentesque quam.</p>
          <footer class="blockquote-footer">
              <small class="text-muted">Someone famous</small>
          </footer>
      </blockquote>
  </div>
  <div class="card">
      <div class="card-body">
          <h5 class="card-title">Card title</h5>
          <p class="card-text">Convallis eget pretium, bibendum non leo. Proien suscipit purus adipiscing dolor gravida fermentum sapien blandit praest interdum vel metus.</p>
          <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
      </div>
  </div>
  </div>
  <hr>
  <!-- Horizontal Cards -->
  <div class="card" style="max-width: 500px;">
      <div class="row no-gutters">
          <div class="col-sm-5" style="background: #868e96;">
              <img src="images/avatar.svg" class="card-img-top h-100" alt="...">
          </div>
          <div class="col-sm-7">
              <div class="card-body">
                  <h5 class="card-title">Alice Liddel</h5>
                  <p class="card-text">Alice is a freelance web designer and developer based in London. She is specialized in HTML5, CSS3, JavaScript, Bootstrap, etc.</p>
                  <a href="#" class="btn btn-primary stretched-link">View Profile</a>
              </div>
          </div>
      </div>
  </div>
  <hr>
  <!-- Card image overlays -->
  <!-- use .card-img-overlay class -->
  <div class="card text-white" style="width: 350px;">
      <img src="images/avatar.svg" class="card-img-top" alt="...">
      <div class="card-img-overlay">
          <h5 class="card-title">Alice Liddel</h5>
          <p class="card-text">Alice is a freelance web designer and developer based in London. She is specialized in HTML5, CSS3, JavaScript, Bootstrap, etc.</p>
          <a href="#" class="btn btn-primary stretched-link">View Profile</a>
      </div>
  </div>
</div>
```
    
</details>

12. ## Icons
    ![alt text](https://github.com/RasbeeTech/Bootstrap-Test/blob/main/images/html%20prints/icons.jpeg)  
<details>
    <summary>View code</summary>
    
```html
<h1>Icons</h1>
<div class="container-fluid"> <!-- Acts as the wrapper for the page content-->
  <!-- Fonts and Icons-->
  <!-- require font-awesome.min.css -->
  <!--
  .fa: base class
  .fa-globe
  .fa-search
  .fa-user
  .fa-star
  .fa-calendar
  and more...
  -->
  <h1><i class="fa fa-globe"></i> Hello, world!</h1>
  <button type="submit" class="btn btn-primary"><span class="fa fa-search"></span> Search</button>
  <button type="submit" class="btn btn-secondary"><span class="fa fa-search"></span> Search</button>
</div>
```
    
</details>

13. ## Navbars
    ![navbars.jpeg](https://github.com/RasbeeTech/Bootstrap-Test/blob/main/images/html%20prints/navbars.jpg)  
<details>
<summary>View code</summary>
    
```html
<h1>Nav bar</h1>
<div class="container-fluid"> <!-- Acts as the wrapper for the page content-->
  <!-- Nav Bar -->
  <nav class="nav">
      <a href="#" class="nav-item nav-link active">Home</a>
      <a href="#" class="nav-item nav-link">Profile</a>
      <a href="#" class="nav-item nav-link">Messages</a>
      <a href="#" class="nav-item nav-link disabled" tabindex="-1">Reports</a>
  </nav>
  <hr>
  <!-- Alighnment of Navbar -->
  <nav class="nav justify-content-center">
      <a href="#" class="nav-item nav-link active">Home</a>
      <a href="#" class="nav-item nav-link">Profile</a>
      <a href="#" class="nav-item nav-link">Messages</a>
      <a href="#" class="nav-item nav-link disabled" tabindex="-1">Reports</a>
  </nav>
  <nav class="nav justify-content-end">
      <a href="#" class="nav-item nav-link active">Home</a>
      <a href="#" class="nav-item nav-link">Profile</a>
      <a href="#" class="nav-item nav-link">Messages</a>
      <a href="#" class="nav-item nav-link disabled" tabindex="-1">Reports</a>
  </nav>
  <nav class="nav flex-column">
      <a href="#" class="nav-item nav-link active">Home</a>
      <a href="#" class="nav-item nav-link">Profile</a>
      <a href="#" class="nav-item nav-link">Messages</a>
      <a href="#" class="nav-item nav-link disabled" tabindex="-1">Reports</a>
  </nav>
  <hr>
  <!-- Tabs of Nav bar -->
  <nav class="nav nav-tabs">
      <a href="#" class="nav-item nav-link active">Home</a>
      <a href="#" class="nav-item nav-link">Profile</a>
      <a href="#" class="nav-item nav-link">Messages</a>
      <a href="#" class="nav-item nav-link disabled" tabindex="-1">Reports</a>
  </nav>
  <!-- tabs with icons -->
  <nav class="nav nav-tabs">
      <a href="#" class="nav-item nav-link active">
          <i class="fa fa-home"></i> Home
      </a>
      <a href="#" class="nav-item nav-link">
          <i class="fa fa-user"></i> Profile
      </a>
      <a href="#" class="nav-item nav-link">
          <i class="fa fa-envelope"></i> Messages
      </a>
      <a href="#" class="nav-item nav-link disabled" tabindex="-1">
          <i class="fa fa-line-chart"></i> Reports
      </a>
  </nav>
  <hr>
  <!-- Pill based nav bar -->
  <nav class="nav nav-pills">
      <a href="#" class="nav-item nav-link active">Home</a>
      <a href="#" class="nav-item nav-link">Profile</a>
      <a href="#" class="nav-item nav-link">Messages</a>
      <a href="#" class="nav-item nav-link disabled" tabindex="-1">Reports</a>
  </nav>
  <hr>
  <!-- drop down menus -->
  <nav class="nav nav-tabs">
      <a href="#" class="nav-item nav-link active">Home</a>
      <a href="#" class="nav-item nav-link">Profile</a>
      <div class="nav-item dropdown">
          <a href="#" class="nav-link dropdown-toggle" data-toggle="dropdown">Messages</a>
          <div class="dropdown-menu">
              <a href="#" class="dropdown-item">Inbox</a>
              <a href="#" class="dropdown-item">Sent</a>
              <a href="#" class="dropdown-item">Drafts</a>
          </div>
      </div>
      <a href="#" class="nav-item nav-link disabled" tabindex="-1">Reports</a>
  </nav>
  <hr>
  <!-- fill and justify -->
  <nav class="nav nav-pills nav-fill">
      <a href="#" class="nav-item nav-link">Home</a>
      <a href="#" class="nav-item nav-link">About</a>
      <a href="#" class="nav-item nav-link active">Explore Products</a>
      <a href="#" class="nav-item nav-link">Contact Us</a>
  </nav>
  <hr>
  <h2 class="text-secondary">Responsive Nav Bar</h2>
  <!-- Nav Bar Plus+ -->
  <!-- collapes when used on smaller devices -->
  <nav class="navbar navbar-expand-md navbar-light bg-light">
      <a href="#" class="navbar-brand">Brand</a>
      <button type="button" class="navbar-toggler" data-toggle="collapse" data-target="#navbarCollapse">
          <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarCollapse">
          <div class="navbar-nav">
              <a href="#" class="nav-item nav-link active">Home</a>
              <a href="#" class="nav-item nav-link">Profile</a>
              <a href="#" class="nav-item nav-link">Messages</a>
              <a href="#" class="nav-item nav-link disabled" tabindex="-1">Reports</a>
          </div>
          <div class="navbar-nav ml-auto">
              <a href="#" class="nav-item nav-link">Login</a>
          </div>
      </div>
  </nav>
  <!-- setting logo in navbar (image height needs to be defined) -->
  <nav class="navbar navbar-expand-md navbar-light bg-light">
      <a href="#" class="navbar-brand">
          <img src="images/avatar.svg" height="28" alt="CoolBrand">
      </a>
      <button type="button" class="navbar-toggler" data-toggle="collapse" data-target="#navbarCollapse">
          <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarCollapse">
          <div class="navbar-nav">
              <a href="#" class="nav-item nav-link active">Home</a>
              <a href="#" class="nav-item nav-link">Profile</a>
              <a href="#" class="nav-item nav-link">Messages</a>
              <a href="#" class="nav-item nav-link disabled" tabindex="-1">Reports</a>
          </div>
          <div class="navbar-nav ml-auto">
              <a href="#" class="nav-item nav-link">Login</a>
          </div>
      </div>
  </nav>
  <hr>
  <!-- adding dropdowns and search bars in Navbar -->
  <nav class="navbar navbar-expand-md navbar-light bg-light">
      <a href="#" class="navbar-brand">Brand</a>
      <button type="button" class="navbar-toggler" data-toggle="collapse" data-target="#navbarCollapse">
          <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse justify-content-between" id="navbarCollapse">
          <div class="navbar-nav">
              <a href="#" class="nav-item nav-link active">Home</a>
              <a href="#" class="nav-item nav-link">Profile</a>
              <div class="nav-item dropdown">
                  <a href="#" class="nav-link dropdown-toggle" data-toggle="dropdown">Messages</a>
                  <div class="dropdown-menu">
                      <a href="#" class="dropdown-item">Inbox</a>
                      <a href="#" class="dropdown-item">Sent</a>
                      <a href="#" class="dropdown-item">Drafts</a>
                  </div>
              </div>
          </div>
          <form class="form-inline">
              <div class="input-group">
                  <input type="text" class="form-control" placeholder="Search">
                  <div class="input-group-append">
                      <button type="button" class="btn btn-secondary"><i class="fa fa-search"></i></button>
                  </div>
              </div>
          </form>
          <div class="navbar-nav">
              <a href="#" class="nav-item nav-link">Login</a>
          </div>
      </div>
  </nav>
  <hr>
  <h2>Nav bar coloring</h2>
  <!-- Nav bar coloring -->
  <!--

  -->
  <nav class="navbar navbar-expand-md navbar-dark bg-dark">
      <h3>navbar-dark bg-dark</h3>
  </nav>

  <nav class="navbar navbar-dark bg-primary">
      <h3>navbar-dark bg-primary</h3>
  </nav>

  <nav class="navbar navbar-light" style="background-color: #ddeeff;">
      <h3>navbar-light" style="background-color: #ddeeff;"</h3>
  </nav>
  <hr>
  <!-- Navbar sticky/fixed -->
  <!--
  .sticky-top
  .fixed-bottom
  -->
  <nav class="navbar navbar-expand-md navbar-dark bg-dark fixed-top">
      <h3>fixed top</h3>
  </nav>
  <hr>
  <h2>BreadCrumbs</h2>
  <!-- BreadCrumbs -->
  <nav>
      <ol class="breadcrumb">
          <li class="breadcrumb-item"><a href="#">Home</a></li>
          <li class="breadcrumb-item"><a href="#">Products</a></li>
          <li class="breadcrumb-item active">Accessories</li>
      </ol>
  </nav>
</div>
```
    
</details>

14. ## Pagination
    ![alt text](https://github.com/RasbeeTech/Bootstrap-Test/blob/main/images/html%20prints/pagination.jpeg)  
<details>
<summary>View code</summary>
    
```html
<h1>Pagination</h1>
<div class="container-fluid"> <!-- Acts as the wrapper for the page content-->
  <!-- pagination -->
  <nav>
      <!--
      sizing can be added by:
      .pagination-lg,
      .pagination-sm

      alignment classes:
      .justify-content-center,
      .justify-content-end
      -->
      <ul class="pagination">
          <li class="page-item"><a href="#" class="page-link">Previous</a></li>
          <li class="page-item"><a href="#" class="page-link">1</a></li>
          <li class="page-item"><a href="#" class="page-link">2</a></li>
          <li class="page-item"><a href="#" class="page-link">3</a></li>
          <li class="page-item"><a href="#" class="page-link">4</a></li>
          <li class="page-item"><a href="#" class="page-link">5</a></li>
          <li class="page-item"><a href="#" class="page-link">Next</a></li>
      </ul>
  </nav>
  <!-- disable -->
  <nav>
      <ul class="pagination">
          <li class="page-item disabled"><a href="#" class="page-link" tabindex="-1">Previous</a></li>
          <li class="page-item active"><a href="#" class="page-link">1</a></li>
          <li class="page-item"><a href="#" class="page-link">2</a></li>
          <li class="page-item"><a href="#" class="page-link">3</a></li>
          <li class="page-item"><a href="#" class="page-link">4</a></li>
          <li class="page-item"><a href="#" class="page-link">5</a></li>
          <li class="page-item"><a href="#" class="page-link">Next</a></li>
      </ul>
  </nav>
</div>
```
    
</details>

15. ## Badges
    ![alt text](https://github.com/RasbeeTech/Bootstrap-Test/blob/main/images/html%20prints/badges.jpeg)  
<details>
<summary>View code</summary>
    
```html
<h1>Badges</h1>
<div class="container-fluid"> <!-- Acts as the wrapper for the page content-->
  <!-- Badges -->
  <h1>Bootstrap heading <span class="badge badge-secondary">New</span></h1>
  <h2>Bootstrap heading <span class="badge badge-secondary">New</span></h2>
  <h3>Bootstrap heading <span class="badge badge-secondary">New</span></h3>
  <h4>Bootstrap heading <span class="badge badge-secondary">New</span></h4>
  <h5>Bootstrap heading <span class="badge badge-secondary">New</span></h5>
  <h6>Bootstrap heading <span class="badge badge-secondary">New</span></h6>
  <hr>
  <!-- Badge colors -->
  <span class="badge badge-primary">Primary</span>
  <span class="badge badge-secondary">Secondary</span>
  <span class="badge badge-success">Success</span>
  <span class="badge badge-danger">Danger</span>
  <span class="badge badge-warning">Warning</span>
  <span class="badge badge-info">Info</span>
  <span class="badge badge-dark">Dark</span>
  <span class="badge badge-light">Light</span>
  <hr>
  <!-- Badge pilling -->
  <span class="badge badge-pill badge-primary">Primary</span>
  <span class="badge badge-pill badge-secondary">Secondary</span>
  <span class="badge badge-pill badge-success">Success</span>
  <span class="badge badge-pill badge-danger">Danger</span>
  <span class="badge badge-pill badge-warning">Warning</span>
  <span class="badge badge-pill badge-info">Info</span>
  <span class="badge badge-pill badge-dark">Dark</span>
  <span class="badge badge-pill badge-light">Light</span>
  <hr>
  <!-- Counter Badges -->
  <ul class="nav nav-pills">
      <li class="nav-item">
          <a href="#" class="nav-link">Home</a>
      </li>
      <li class="nav-item">
          <a href="#" class="nav-link">Profile</a>
      </li>
      <li class="nav-item">
          <a href="#" class="nav-link active">Messages <span class="badge badge-light">24</span></a>
      </li>
      <li class="nav-item">
          <a href="#" class="nav-link">Notification <span class="badge badge-primary">5</span></a>
      </li>
  </ul>
</div>
```
    
</details>

16. ## Progress-Bars
    ![alt text](https://github.com/RasbeeTech/Bootstrap-Test/blob/main/images/html%20prints/progress-bar.jpeg)  
<details>
<summary>View code</summary>
    
```html
<h1>Progress-bar</h1>
<div class="container-fluid"> <!-- Acts as the wrapper for the page content-->
  <!-- Progress bar -->
  <div class="progress">
      <div class="progress-bar" style="width: 50%"></div>
  </div>
  <hr>
  <!-- progress bar with label -->
  <div class="progress">
      <div class="progress-bar" style="width: 60%">
          60%
      </div>
  </div>
  <hr>
  <!-- If showing percentage -->
  <div class="progress">
      <div class="progress-bar" style="min-width: 20px;">
          0%
      </div>
  </div>
  <hr>
  <div class="progress">
      <div class="progress-bar" style="min-width: 20px; width: 2%;">
          2%
      </div>
  </div>
  <hr>
  <!-- Height of Progress Bar -->
  <!-- Progress bar with 1px height -->
  <div class="progress" style="height: 1px;">
      <div class="progress-bar" style="width: 50%;"></div>
  </div>
  <hr>
  <!-- Progress bar with 20px height -->
  <div class="progress" style="height: 20px;">
      <div class="progress-bar" style="width: 50%;"></div>
  </div>
  <hr>
  <!-- Striped progress bar -->
  <div class="progress">
      <div class="progress-bar progress-bar-striped" style="width: 60%;"></div>
  </div>
  <hr>
  <!-- Animated progress bar -->
  <div class="progress">
      <div class="progress-bar progress-bar-striped progress-bar-animated" style="width: 60%"></div>
  </div>
  <hr>
  <!-- Stacked progress bar -->
  <div class="progress">
      <div class="progress-bar bg-success" style="width: 40%">
          Program Files (40%)
      </div>
      <div class="progress-bar bg-warning" style="width: 25%">
          Residual Files (25%)
      </div>
      <div class="progress-bar bg-danger" style="width: 15%">
          Junk Files (15%)
      </div>
  </div>
  <hr>
  <!-- Coloring progress bar -->
  <div class="progress">
      <div class="progress-bar bg-info" style="width: 20%"></div>
  </div>
  <div class="progress">
      <div class="progress-bar bg-success" style="width: 40%"></div>
  </div>
  <div class="progress">
      <div class="progress-bar bg-warning" style="width: 80%"></div>
  </div>
  <div class="progress">
      <div class="progress-bar bg-danger" style="width: 90%"></div>
  </div>
</div>
```
    
</details>

17. ## Spinners
    ![alt text](https://github.com/RasbeeTech/Bootstrap-Test/blob/main/images/html%20prints/spinners.jpeg)  
<details>
<summary>View code</summary>
    
```html
<h1>Spinners</h1>
<div class="container-fluid"> <!-- Acts as the wrapper for the page content-->
  <!-- Spinners-->
  <div class="spinner-border">
      <span class="sr-only">Loading...</span>
  </div>
  <!-- Growing spinners -->
  <div class="spinner-grow">
      <span class="sr-only">Loading...</span>
  </div>
  <!-- Sizing spinners -->
  <div class="spinner-border spinner-border-sm">
      <span class="sr-only">Loading...</span>
  </div>
  <div class="spinner-grow spinner-grow-sm">
      <span class="sr-only">Loading...</span>
  </div>
  <div class="spinner-border" style="width: 40px; height: 40px;">
      <span class="sr-only">Loading...</span>
  </div>
  <div class="spinner-grow" style="width: 40px; height: 40px;">
      <span class="sr-only">Loading...</span>
  </div>
  <hr>
  <!-- Colored spinners -->
  <div class="spinner-border text-primary">
      <span class="sr-only">Loading...</span>
  </div>
  <div class="spinner-border text-secondary">
      <span class="sr-only">Loading...</span>
  </div>
  <div class="spinner-border text-success">
      <span class="sr-only">Loading...</span>
  </div>
  <div class="spinner-border text-danger">
      <span class="sr-only">Loading...</span>
  </div>
  <div class="spinner-border text-warning">
      <span class="sr-only">Loading...</span>
  </div>
  <div class="spinner-border text-info">
      <span class="sr-only">Loading...</span>
  </div>
  <div class="spinner-border text-dark">
      <span class="sr-only">Loading...</span>
  </div>
  <div class="spinner-border text-light">
      <span class="sr-only">Loading...</span>
  </div>
  <!-- colored growing spinners -->
  <div class="spinner-grow text-primary">
      <span class="sr-only">Loading...</span>
  </div>
  <div class="spinner-grow text-secondary">
      <span class="sr-only">Loading...</span>
  </div>
  <div class="spinner-grow text-success">
      <span class="sr-only">Loading...</span>
  </div>
  <div class="spinner-grow text-danger">
      <span class="sr-only">Loading...</span>
  </div>
  <div class="spinner-grow text-warning">
      <span class="sr-only">Loading...</span>
  </div>
  <div class="spinner-grow text-info">
      <span class="sr-only">Loading...</span>
  </div>
  <div class="spinner-grow text-light">
      <span class="sr-only">Loading...</span>
  </div>
  <div class="spinner-grow text-dark">
      <span class="sr-only">Loading...</span>
  </div>
  <hr>
  <!-- Spinners in buttons -->
  <!-- Border spinners inside buttons -->
  <button class="btn btn-primary" type="button" disabled>
      <span class="spinner-border spinner-border-sm"></span>
      <span class="sr-only">Loading...</span>
  </button>
  <button class="btn btn-primary" type="button" disabled>
      <span class="spinner-border spinner-border-sm"></span>
      Loading...
  </button>
  <!-- Growing spinners inside buttons -->
  <button class="btn btn-primary" type="button" disabled>
      <span class="spinner-grow spinner-grow-sm"></span>
      <span class="sr-only">Loading...</span>
  </button>
  <button class="btn btn-primary" type="button" disabled>
      <span class="spinner-grow spinner-grow-sm"></span>
      Loading...
  </button>
  <hr>
  <!-- Alignment of spinners -->
  <!-- Center alignment using flex utilities -->
  <div class="d-flex justify-content-center">
      <div class="spinner-border" role="status">
          <span class="sr-only">Loading...</span>
      </div>
  </div>
  <!-- Center alignment using text alignment utilities -->
  <div class="text-center">
      <div class="spinner-border" role="status">
          <span class="sr-only">Loading...</span>
      </div>
  </div>
  <!-- Right alignment using float utilities -->
  <div class="clearfix">
      <div class="spinner-border float-right" role="status">
          <span class="sr-only">Loading...</span>
      </div>
  </div>
</div>
```
    
</details>

18. ## Jumbotron
    ![alt text](https://github.com/RasbeeTech/Bootstrap-Test/blob/main/images/html%20prints/jumbotron.jpg)  
<details>
<summary>View code</summary>
    
```html
<h1>Jumbotron</h1>
<div class="container-fluid"> <!-- Acts as the wrapper for the page content-->
  <!-- Jumbotron -->
  <div class="jumbotron">
      <h1>Learn to Create Websites</h1>
      <p class="lead">In today's world internet is the most popular way of connecting with the people. At <a href="https://www.tutorialrepublic.com" target="_blank">tutorialrepublic.com</a> you will learn the essential of web development technologies along with real life practice example, so that you can create your own website to connect with the people around the world.</p>
      <p><a href="https://www.tutorialrepublic.com" target="_blank" class="btn btn-primary btn-lg">Start learning today</a></p>
  </div>
  <!-- Full Page Jumbotron -->
  <div class="jumbotron jumbotron-fluid">
      <div class="container">
          <h1>Learn to Create Websites</h1>
          <p class="lead">In today's world internet is the most popular way of connecting with the people...</p>
          <p><a href="#" class="btn btn-primary btn-lg">Start learning today</a></p>
      </div>
  </div>
</div>
```
    
</details>

19. ## Helper-Classes
    ![alt text](https://github.com/RasbeeTech/Bootstrap-Test/blob/main/images/html%20prints/helper-classes.jpg)  
<details>
<summary>View code</summary>
    
```html
<title>Helper Classes</title>
    <!-- Bootstrap CSS file -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css">
    <!-- Icons and font styling CSS file -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
    <style>
      #border-classes {
        display: inline-block;
        width: 100px;
        height: 100px;
        margin: 10px;
        background-color: #f5f5f5;
      }
      #spacing-classes {
        padding: 15px;
        font-size: 18px;
        background: #dbdfe5;
      }
      #float-classes {
        font-size: 18px;
        padding: 20px;
        background: #abb1b8;
      }
      #sizing-classes {
        background: #dbdfe5;
        margin: 10px;
      }
    </style>
</head>
<h1>Helper Classes</h1>
<div class="container-fluid"> <!-- Acts as the wrapper for the page content-->
  <h2>Color Classes</h2>
  <p class="text-primary">.text-primary</p>
  <p class="text-secondary">.text-secondary</p>
  <p class="text-success">.text-success</p>
  <p class="text-danger">.text-danger</p>
  <p class="text-warning">.text-warning</p>
  <p class="text-info">.text-info</p>
  <p class="text-light bg-dark">.text-light</p>
  <p class="text-dark">.text-dark</p>
  <p class="text-body">.text-body</p>
  <p class="text-muted">.text-muted</p>
  <p class="text-white bg-dark">.text-white</p>
  <p class="text-black-50">.text-black-50</p>
  <p class="text-white-50 bg-dark">.text-white-50</p>
  <hr>
  <h2>Background Color Classes</h2>
  <div class="p-3 mb-2 bg-primary text-white">.bg-primary</div>
  <div class="p-3 mb-2 bg-secondary text-white">.bg-secondary</div>
  <div class="p-3 mb-2 bg-success text-white">.bg-success</div>
  <div class="p-3 mb-2 bg-danger text-white">.bg-danger</div>
  <div class="p-3 mb-2 bg-warning text-dark">.bg-warning</div>
  <div class="p-3 mb-2 bg-info text-white">.bg-info</div>
  <div class="p-3 mb-2 bg-light text-dark">.bg-light</div>
  <div class="p-3 mb-2 bg-dark text-white">.bg-dark</div>
  <div class="p-3 mb-2 bg-white text-dark">.bg-white</div>
  <div class="p-3 mb-2 bg-transparent text-dark">.bg-transparent</div>
  <hr>
  <h2>Text Alignment Classes</h2>
  <p>.text-left: Align the text to the left.</p>
  <p>.text-center: Align the text to the center.</p>
  <p>.text-right: Align the text to the right.</p>
  <p>.text-justify: Justify the text content.</p>
  <p>.text-wrap: Wrap the overflowing text.</p>
  <p>.text-nowrap: Prevent text from wrapping.</p>
  <p>.text-truncate: Truncate the text with an ellipsis.</p>
  <p>.text-break: Break the long words to prevent overflow.</p>
  <p>.text-lowercase: Transform the text to lowercase.</p>
  <p>.text-uppercase: Transform the text to uppercase.</p>
  <p>.text-capitalize: Capitalize the first letter of each word.</p>
  <p>.font-weight-bold: Set the font-weight of an element to bold.</p>
  <p>.font-weight-bolder: Set the font-weight of an element to bolder (relative to the parent).</p>
  <p>.font-weight-normal: Set the font-weight of an element to normal.</p>
  <p>.font-weight-light: Set the light font-weight for an element.</p>
  <p>.font-weight-lighter: Set the lighter font-weight for an element (relative to the parent).</p>
  <p>.font-italic: Set the font-style of an element to italic.</p>
  <p>.text-monospace: Set the font-family of an element to monospace font (fixed-width)</p>
  <p>.text-reset: Reset the color of a text or link (inherits the color from its parent).</p>
  <p>.text-decoration-none: Remove the text decoration such as underline from a text.</p>
  <hr>
  <h2>Border Classes</h2>
  <span id="border-classes" class="border"></span>
  <span id="border-classes" class="border-top"></span>
  <span id="border-classes" class="border-right"></span>
  <span id="border-classes" class="border-bottom"></span>
  <span id="border-classes" class="border-left"></span>
  <hr>
  <h2>Spacing Classes</h2>
  <div id="spacing-classes" class="mt-0">.mt-0</div>
  <div id="spacing-classes" class="mt-1">.mt-1</div>
  <div id="spacing-classes" class="mt-2">.mt-2</div>
  <div id="spacing-classes" class="mt-3">.mt-3</div>
  <div id="spacing-classes" class="mt-4">.mt-4</div>
  <div id="spacing-classes" class="mt-5">.mt-5</div>
  <div id="spacing-classes" class="mt-auto">.mt-auto</div>
  <hr>
  <h2>Float Classes</h2>
  <div class="wrapper clearfix">
      <div id="float-classes" class="float-left">.float-left</div>
  </div>
  <div class="wrapper clearfix">
      <div id="float-classes" class="float-right">.float-right</div>
  </div>
  <div class="wrapper clearfix">
      <div id="float-classes" class="float-left">.float-left</div>
      <div id="float-classes" class="float-right">.float-right</div>
  </div>
  <div class="wrapper clearfix">
      <div id="float-classes" class="float-none" style="float: right;">.float-none</div>
  </div>
  <hr>
  <h2>Shadow Classes</h2>
  <div class="shadow-none p-3 mb-5 bg-light rounded">No shadow</div>
  <div class="shadow-sm p-3 mb-5 bg-white rounded">Small shadow</div>
  <div class="shadow p-3 mb-5 bg-white rounded">Regular shadow</div>
  <div class="shadow-lg p-3 mb-5 bg-white rounded">Larger shadow</div>
  <hr>
  <h2>Sizing Classes</h2>
  <div id="sizing-classes" class="w-50 p-3">w-50 p-3 (Width 50%)</div>
  <div id="sizing-classes" class="w-75 p-3">w-75 p-3 (Width 75%)</div>
  <div id="sizing-classes" class="w-100 p-3">w-100 p-3 (Width 100%)</div>
  <div id="sizing-classes" class="w-auto p-3">w-auto p-3 (Width auto)</div>
  <hr>
  <h2>Vertical Alignment Classes</h2>
  <h5>With inline elements:</h5>
  <p>
      <span class="align-baseline">baseline</span>
      <span class="align-top">top</span>
      <span class="align-middle">middle</span>
      <span class="align-bottom">bottom</span>
      <span class="align-text-top">text-top</span>
      <span class="align-text-bottom">text-bottom</span>
  </p>
  <hr>
  <h5>With table cells:</h5>
  <table class="table-bordered" style="height: 100px;">
      <tbody>
          <tr>
              <td class="align-baseline">baseline</td>
              <td class="align-top">top</td>
              <td class="align-middle">middle</td>
              <td class="align-bottom">bottom</td>
              <td class="align-text-top">text-top</td>
              <td class="align-text-bottom">text-bottom</td>
          </tr>
      </tbody>
  </table>
</div>
```
    
</details>


20. ## Modals
    ![alt text](https://github.com/RasbeeTech/Bootstrap-Test/blob/main/images/html%20prints/modals.jpeg)  
<details>
<summary>View code</summary>
    
```html
<h1>Modals</h1>
<div class="container-fluid"> <!-- Acts as the wrapper for the page content-->
  <!-- Modals -->

  <div id="myModal" class="modal" tabindex="-1">
      <!-- sets width, horizontal-alignment, and vertical alignment
      .modal-sm: small,
      .modal-lg: large,
      .modal-xl: extra-large
      .modal-dialog-centered: vertically centers,
      .modal-dialog-scrollable: make modal scrollable,
      *Grids can be used inside modals
      -->
      <div class="modal-dialog modal-sm">
          <!-- sets sytles: text, background, borders, round corners, etc... -->
          <div class="modal-content">
              <div class="modal-header">
                  <h5 class="modal-title">Confirmation</h5>
                  <button type="button" class="close" data-dismiss="modal">&times;</button>
              </div>
              <div class="modal-body">
                  <p>Do you want to save changes to this document before closing?</p>
                  <p class="text-secondary"><small>If you don't save, your changes will be lost.</small></p>
              </div>
              <div class="modal-footer">
                  <button type="button" class="btn btn-secondary" data-dismiss="modal">Cancel</button>
                  <button type="button" class="btn btn-primary">Save changes</button>
              </div>
          </div>
      </div>
  </div>
  <!-- to trigger modal -->
  <a href="#myModal" class="btn btn-lg btn-primary" data-toggle="modal">Launch Demo Modal</a>
  <hr>
</div>
```
    
</details>

21. ## Dropdowns
    ![alt text](https://github.com/RasbeeTech/Bootstrap-Test/blob/main/images/html%20prints/dropdown.jpeg)  
<details>
<summary>View code</summary>
    
```html
<h1>Dropdown</h1>
<div class="container-fluid"> <!-- Acts as the wrapper for the page content-->
  <!-- Drop Down menus -->
  <div class="dropdown">
      <a href="#" class="dropdown-toggle" data-toggle="dropdown">Dropdown</a>
      <div class="dropdown-menu">
          <a href="#" class="dropdown-item">Action</a>
          <a href="#" class="dropdown-item">Another action</a>
      </div>
  </div>
  <!-- Dropup menu -->
  <div class="btn-group dropup">
      <button type="button" class="btn btn-primary dropdown-toggle" data-toggle="dropdown">Dropup</button>
      <div class="dropdown-menu">
          <a href="#" class="dropdown-item">Action</a>
          <a href="#" class="dropdown-item">Another action</a>
          <div class="dropdown-divider"></div>
          <a href="#" class="dropdown-item">Separated link</a>
      </div>
  </div>
  <hr>
  <!-- Dropleft menu -->
  <div class="btn-group dropleft">
      <button type="button" class="btn btn-primary dropdown-toggle" data-toggle="dropdown">Dropleft</button>
      <div class="dropdown-menu">
          <a href="#" class="dropdown-item">Action</a>
          <a href="#" class="dropdown-item">Another action</a>
          <div class="dropdown-divider"></div>
          <a href="#" class="dropdown-item">Separated link</a>
      </div>
  </div>
  <hr>
  <!-- Dropright menu -->
  <div class="btn-group dropright">
      <button type="button" class="btn btn-primary dropdown-toggle" data-toggle="dropdown">Dropright</button>
      <div class="dropdown-menu">
          <a href="#" class="dropdown-item">Action</a>
          <a href="#" class="dropdown-item">Another action</a>
          <div class="dropdown-divider"></div>
          <a href="#" class="dropdown-item">Separated link</a>
      </div>
  </div>
  <hr>
  <!-- dropdown with headers -->
  <div class="btn-group">
      <button type="button" class="btn btn-primary dropdown-toggle" data-toggle="dropdown">Products</button>
      <div class="dropdown-menu">
          <div class="dropdown-header">ELECTRONICS</div>
          <a href="#" class="dropdown-item">Mobiles</a>
          <a href="#" class="dropdown-item">Tablets</a>
          <a href="#" class="dropdown-item">Laptops</a>
          <div class="dropdown-header">FASHION</div>
          <a href="#" class="dropdown-item">Clothing</a>
          <a href="#" class="dropdown-item">Sunglasses</a>
      </div>
  </div>
</div>
```
    
</details>

22. ## Alerts
    ![alt text](https://github.com/RasbeeTech/Bootstrap-Test/blob/main/images/html%20prints/alerts.jpg)  
<details>
<summary>View code</summary>
    
```html
<h1>Alerts</h1>
<div class="container-fluid"> <!-- Acts as the wrapper for the page content-->
  <!-- Alerts -->
  <!-- Success Alert -->
  <div class="alert alert-success alert-dismissible fade show">
      <strong>Success!</strong> Your message has been sent successfully.
      <button type="button" class="close" data-dismiss="alert">&times;</button>
  </div>
  <!-- Error Alert -->
  <div class="alert alert-danger alert-dismissible fade show">
      <strong>Error!</strong> A problem has been occurred while submitting your data.
      <button type="button" class="close" data-dismiss="alert">&times;</button>
  </div>
  <!-- Warning Alert -->
  <div class="alert alert-warning alert-dismissible fade show">
      <strong>Warning!</strong> There was a problem with your network connection.
      <button type="button" class="close" data-dismiss="alert">&times;</button>
  </div>
  <!-- Info Alert -->
  <div class="alert alert-info alert-dismissible fade show">
      <strong>Info!</strong> Please read the comments carefully.
      <button type="button" class="close" data-dismiss="alert">&times;</button>
  </div>
  <hr>
  <!-- Primary Alert -->
  <div class="alert alert-primary alert-dismissible fade show">
      <strong>Primary!</strong> This is a simple primary alert box.
      <button type="button" class="close" data-dismiss="alert">&times;</button>
  </div>
  <!-- Secondary Alert -->
  <div class="alert alert-secondary alert-dismissible fade show">
      <strong>Secondary!</strong> This is a simple secondary alert box.
      <button type="button" class="close" data-dismiss="alert">&times;</button>
  </div>
  <!-- Dark Alert -->
  <div class="alert alert-dark alert-dismissible fade show">
      <strong>Dark!</strong> This is a simple dark alert box.
      <button type="button" class="close" data-dismiss="alert">&times;</button>
  </div>
  <!-- Light Alert -->
  <div class="alert alert-light alert-dismissible fade show">
      <strong>Light!</strong> This is a simple light alert box.
      <button type="button" class="close" data-dismiss="alert">&times;</button>
  </div>
  <hr>
  <!-- Additional information -->
  <div class="alert alert-warning alert-dismissible fade show">
      <h4 class="alert-heading"><i class="fa fa-warning"></i> Warning!</h4>
      <p>Please enter a valid value in all the required fields before proceeding. If you need any help just place the mouse pointer above info icon next to the form field.</p>
      <hr>
      <p class="mb-0">Once you have filled all the details, click on the 'Next' button to continue.</p>
      <button type="button" class="close" data-dismiss="alert">&times;</button>
  </div>
</div>
```
    
</details>

23. ## Accordian
    ![alt text](https://github.com/RasbeeTech/Bootstrap-Test/blob/main/images/html%20prints/accordian.jpg)  
<details>
<summary>View code</summary>
    
```html
<h1>Accordian</h1>
<div class="container-fluid"> <!-- Acts as the wrapper for the page content-->
  <!-- Accordian -->
  <div class="accordion" id="myAccordion">
      <div class="card">
          <div class="card-header" id="headingOne">
              <h2 class="mb-0">
                  <button type="button" class="btn btn-link" data-toggle="collapse" data-target="#collapseOne">1. What is HTML?</button>
              </h2>
          </div>
          <div id="collapseOne" class="collapse" aria-labelledby="headingOne" data-parent="#myAccordion">
              <div class="card-body">
                  <p>HTML stands for HyperText Markup Language. HTML is the standard markup language for describing the structure of web pages. <a href="https://www.tutorialrepublic.com/html-tutorial/" target="_blank">Learn more.</a></p>
              </div>
          </div>
      </div>
      <div class="card">
          <div class="card-header" id="headingTwo">
              <h2 class="mb-0">
                  <button type="button" class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapseTwo">2. What is Bootstrap?</button>
              </h2>
          </div>
          <div id="collapseTwo" class="collapse show" aria-labelledby="headingTwo" data-parent="#myAccordion">
              <div class="card-body">
                  <p>Bootstrap is a sleek, intuitive, and powerful front-end framework for faster and easier web development. It is a collection of CSS and HTML conventions. <a href="https://www.tutorialrepublic.com/twitter-bootstrap-tutorial/" target="_blank">Learn more.</a></p>
              </div>
          </div>
      </div>
      <div class="card">
          <div class="card-header" id="headingThree">
              <h2 class="mb-0">
                  <button type="button" class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapseThree">3. What is CSS?</button>
              </h2>
          </div>
          <div id="collapseThree" class="collapse" aria-labelledby="headingThree" data-parent="#myAccordion">
              <div class="card-body">
                  <p>CSS stands for Cascading Style Sheet. CSS allows you to specify various style properties for a given HTML element such as colors, backgrounds, fonts etc. <a href="https://www.tutorialrepublic.com/css-tutorial/" target="_blank">Learn more.</a></p>
              </div>
          </div>
      </div>
  </div>
</div>
```
    
</details>

24. ## Carousal
    ![alt text](https://github.com/RasbeeTech/Bootstrap-Test/blob/main/images/html%20prints/carousal.jpeg)  
<details>
<summary>View code</summary>
    
```html
<h1>Carousal</h1>
<div class="container-fluid"> <!-- Acts as the wrapper for the page content-->
  <!-- Carousel -->
  <div id="myCarousel" class="carousel slide" data-ride="carousel">
      <!-- Carousel indicators -->
      <ol class="carousel-indicators">
          <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
          <li data-target="#myCarousel" data-slide-to="1"></li>
          <li data-target="#myCarousel" data-slide-to="2"></li>
      </ol>
      <!-- Wrapper for carousel items -->
      <div class="carousel-inner bg-primary">
          <div class="carousel-item active text-center">
              <img src="images/avatar.svg" height=300px alt="First Slide">
          </div>
          <div class="carousel-item text-center">
              <img src="images/avatar.svg" height=300px alt="Second Slide">
          </div>
          <div class="carousel-item text-center">
              <img src="images/avatar.svg" height=300px alt="Third Slide">
          </div>
      </div>
      <!-- Carousel controls -->
      <a class="carousel-control-prev" href="#myCarousel" data-slide="prev">
          <span class="carousel-control-prev-icon"></span>
      </a>
      <a class="carousel-control-next" href="#myCarousel" data-slide="next">
          <span class="carousel-control-next-icon"></span>
      </a>
  </div>
</div>
```
    
</details>


### Details
Created with the help of [www.tutorialrepublic.com](https://www.tutorialrepublic.com/twitter-bootstrap-tutorial/).
