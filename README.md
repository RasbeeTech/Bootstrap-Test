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
    <summary>Code</summary>

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
<summary>Code</summary>

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
<summary>Code</summary>

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
<summary>Code</summary>
    
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
<summary>Code</summary>
    
    ```html
    <body>
    <h1>Bootstrap Test</h1>
    <div class="container-fluid"> <!-- Acts as the wrapper for the page content-->
    
    </div>
    </body>
    ```
    
</details>

7. ## Lists
    ![alt text](https://github.com/RasbeeTech/Bootstrap-Test/blob/main/images/html%20prints/lists.jpg)  
<details>
<summary>Code</summary>
    
```html
<body>
    <h1>Bootstrap Test</h1>
    <div class="container-fluid"> <!-- Acts as the wrapper for the page content-->
    
    </div>
</body>
```
    
</details>

8. ## Forms
    ![alt text](https://github.com/RasbeeTech/Bootstrap-Test/blob/main/images/html%20prints/forms.jpg)  
    <details>
    <summary>Code</summary>
    
    ```html
    <body>
    <h1>Bootstrap Test</h1>
    <div class="container-fluid"> <!-- Acts as the wrapper for the page content-->
    
    </div>
    </body>
    ```
    
    </details>

9. ## Buttons
    ![alt text](https://github.com/RasbeeTech/Bootstrap-Test/blob/main/images/html%20prints/buttons.jpg)  
    <details>
    <summary>Code</summary>
    
    ```html
    <body>
    <h1>Bootstrap Test</h1>
    <div class="container-fluid"> <!-- Acts as the wrapper for the page content-->
    
    </div>
    </body>
    ```
    
    </details>

10. ## Images
    ![images.jpeg](https://github.com/RasbeeTech/Bootstrap-Test/blob/main/images/html%20prints/images.jpg)  
    <details>
    <summary>Code</summary>
    
    ```html
    <body>
    <h1>Bootstrap Test</h1>
    <div class="container-fluid"> <!-- Acts as the wrapper for the page content-->
    
    </div>
    </body>
    ```
    
    </details>

11. ## Cards
    ![alt text](https://github.com/RasbeeTech/Bootstrap-Test/blob/main/images/html%20prints/cards.jpg)  
    <details>
    <summary>Code</summary>
    
    ```html
    <body>
    <h1>Bootstrap Test</h1>
    <div class="container-fluid"> <!-- Acts as the wrapper for the page content-->
    
    </div>
    </body>
    ```
    
    </details>

12. ## Icons
    ![alt text](https://github.com/RasbeeTech/Bootstrap-Test/blob/main/images/html%20prints/icons.jpeg)  
    <details>
    <summary>Code</summary>
    
    ```html
    <body>
    <h1>Bootstrap Test</h1>
    <div class="container-fluid"> <!-- Acts as the wrapper for the page content-->
    
    </div>
    </body>
    ```
    
    </details>

13. ## Navbars
    ![navbars.jpeg](https://github.com/RasbeeTech/Bootstrap-Test/blob/main/images/html%20prints/navbars.jpg)  
    <details>
    <summary>Code</summary>
    
    ```html
    <body>
    <h1>Bootstrap Test</h1>
    <div class="container-fluid"> <!-- Acts as the wrapper for the page content-->
    
    </div>
    </body>
    ```
    
    </details>

14. ## Pagination
    ![alt text](https://github.com/RasbeeTech/Bootstrap-Test/blob/main/images/html%20prints/pagination.jpeg)  
    <details>
    <summary>Code</summary>
    
    ```html
    <body>
    <h1>Bootstrap Test</h1>
    <div class="container-fluid"> <!-- Acts as the wrapper for the page content-->
    
    </div>
    </body>
    ```
    
    </details>

15. ## Badges
    ![alt text](https://github.com/RasbeeTech/Bootstrap-Test/blob/main/images/html%20prints/badges.jpeg)  
    <details>
    <summary>Code</summary>
    
    ```html
    <body>
    <h1>Bootstrap Test</h1>
    <div class="container-fluid"> <!-- Acts as the wrapper for the page content-->
    
    </div>
    </body>
    ```
    
    </details>

16. ## Progress-Bars
    ![alt text](https://github.com/RasbeeTech/Bootstrap-Test/blob/main/images/html%20prints/progress-bar.jpeg)  
    <details>
    <summary>Code</summary>
    
    ```html
    <body>
    <h1>Bootstrap Test</h1>
    <div class="container-fluid"> <!-- Acts as the wrapper for the page content-->
    
    </div>
    </body>
    ```
    
    </details>

17. ## Spinners
    ![alt text](https://github.com/RasbeeTech/Bootstrap-Test/blob/main/images/html%20prints/spinners.jpeg)  
    <details>
    <summary>Code</summary>
    
    ```html
    <body>
    <h1>Bootstrap Test</h1>
    <div class="container-fluid"> <!-- Acts as the wrapper for the page content-->
    
    </div>
    </body>
    ```
    
    </details>

18. ## Jumbotron
    ![alt text](https://github.com/RasbeeTech/Bootstrap-Test/blob/main/images/html%20prints/jumbotron.jpg)  
    <details>
    <summary>Code</summary>
    
    ```html
    <body>
    <h1>Bootstrap Test</h1>
    <div class="container-fluid"> <!-- Acts as the wrapper for the page content-->
    
    </div>
    </body>
    ```
    
    </details>

19. ## Helper-Classes
    ![alt text](https://github.com/RasbeeTech/Bootstrap-Test/blob/main/images/html%20prints/helper-classes.jpg)  
    <details>
    <summary>Code</summary>
    
    ```html
    <body>
    <h1>Bootstrap Test</h1>
    <div class="container-fluid"> <!-- Acts as the wrapper for the page content-->
    
    </div>
    </body>
    ```
    
    </details>


20. ## Modals
    ![alt text](https://github.com/RasbeeTech/Bootstrap-Test/blob/main/images/html%20prints/modals.jpeg)  
    <details>
    <summary>Code</summary>
    
    ```html
    <body>
    <h1>Bootstrap Test</h1>
    <div class="container-fluid"> <!-- Acts as the wrapper for the page content-->
    
    </div>
    </body>
    ```
    
    </details>

21. ## Dropdowns
    ![alt text](https://github.com/RasbeeTech/Bootstrap-Test/blob/main/images/html%20prints/dropdown.jpeg)  
    <details>
    <summary>Code</summary>
    
    ```html
    <body>
    <h1>Bootstrap Test</h1>
    <div class="container-fluid"> <!-- Acts as the wrapper for the page content-->
    
    </div>
    </body>
    ```
    
    </details>

22. ## Alerts
    ![alt text](https://github.com/RasbeeTech/Bootstrap-Test/blob/main/images/html%20prints/alerts.jpg)  
    <details>
    <summary>Code</summary>
    
    ```html
    <body>
    <h1>Bootstrap Test</h1>
    <div class="container-fluid"> <!-- Acts as the wrapper for the page content-->
    
    </div>
    </body>
    ```
    
    </details>

23. ## Accordian
    ![alt text](https://github.com/RasbeeTech/Bootstrap-Test/blob/main/images/html%20prints/accordian.jpg)  
    <details>
    <summary>Code</summary>
    
    ```html
    <body>
    <h1>Bootstrap Test</h1>
    <div class="container-fluid"> <!-- Acts as the wrapper for the page content-->
    
    </div>
    </body>
    ```
    
    </details>

24. ## Carousal
    ![alt text](https://github.com/RasbeeTech/Bootstrap-Test/blob/main/images/html%20prints/carousal.jpeg)  
    <details>
    <summary>Code</summary>
    
    ```html
    <body>
    <h1>Bootstrap Test</h1>
    <div class="container-fluid"> <!-- Acts as the wrapper for the page content-->
    
    </div>
    </body>
    ```
    
    </details>


### Details
Created with the help of [www.tutorialrepublic.com](https://www.tutorialrepublic.com/twitter-bootstrap-tutorial/).
