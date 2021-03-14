# Bootstrap-Test

## Purpose
Create a Bootstrap 4 reference while practicing web-design.

# Bootstrap 4.3.1
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<!-- meta viewport tag enables touch zooming and proper rendering on mobile devices-->
<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
<title>Grid System</title>
<!-- Bootstrap CSS file -->
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css">
</head>
<body>
<h1>Grid System</h1>
<div class="container"> <!-- Acts as the wrapper for the page content-->
<!--Row with two equal columns-->
<div class="row">
<!-- Only cols can be children of rows -->
<!-- col total can not be greater than 12 -->
<div class="col-md-6">Column left</div>
<div class="col-md-6">Column right</div>
</div>
<!--Row with two columns divided in 1:2 ratio-->
<div class="row">
<div class="col-md-4">Column left</div>
<div class="col-md-8">Column right</div>
</div>
<!--Row with three equal columns-->
<div class="row">
<div class="col-lg-4">Column left</div>
<div class="col-lg-4">Column middle</div>
<div class="col-lg-4">Column right</div>
</div>
<!--Row with three columns divided in 1:4:1 ratio-->
<div class="row">
<div class="col-lg-2">Column left</div>
<div class="col-lg-8">Column middle</div>
<div class="col-lg-2">Column right</div>
</div>
<!--Row with two equal columns-->
<div class="row">
<div class="col">Column one</div>
<div class="col">Column two</div>
</div>
<!-- nesting cols and rows-->
<div class="row">
<div class="col-sm-8">Column left</div>
<div class="col-sm-4">
<!--Column right with nested rows and columns-->
<div class="row">
<div class="col-12">hi</div>
</div>
<div class="row">
<div class="col-6">hello</div>
<div class="col-6">ok</div>
</div>
</div>
</div>
<!-- col-{breakpoint}-auto to resize cols based on content width -->
<div class="row justify-content-md-center">
<div class="col-md-3">Column left</div>
<div class="col-md-auto">Variable width column</div>
<div class="col-md-3">Column right</div>
</div>
<div class="row">
<div class="col">Column left</div>
<div class="col-auto">Variable width column</div>
<div class="col">Column right</div>
</div>

<!-- Vertical alignment row-->
<div class="row align-items-start">
<div class="col">Column one</div>
<div class="col">Column two</div>
<div class="col">Column three</div>
</div>
<div class="row align-items-center">
<div class="col">Column one</div>
<div class="col">Column two</div>
<div class="col">Column three</div>
</div>
<div class="row align-items-end">
<div class="col">Column one</div>
<div class="col">Column two</div>
<div class="col">Column three</div>
</div>
<!-- vertical align individual cols-->
<div class="row">
<div class="col align-self-start">Column one</div>
<div class="col align-self-center">Column two</div>
<div class="col align-self-end">Column three</div>
</div>

<!-- horizontal align row-->
<div class="row justify-content-start">
<div class="col-4">Column one</div>
<div class="col-4">Column two</div>
</div>
<div class="row justify-content-center">
<div class="col-4">Column one</div>
<div class="col-4">Column two</div>
</div>
<div class="row justify-content-end">
<div class="col-4">Column one</div>
<div class="col-4">Column two</div>
</div>

<!-- Reordering columns with order-last and order-first-->
<div class="row">
<div class="col order-last">First, but ordered at last</div>
<div class="col">Second, but unordered</div>
<div class="col order-first">Last, but ordered at first</div>
</div>
<!-- Reordering columns with number system-->
<div class="row">
<div class="col order-4">First, but ordered at last</div>
<div class="col">Second, but ordered at first</div>
<div class="col order-1">Last, but ordered at second</div>
</div>

<!-- removes column padding -->
<div class="row no-gutters">
<div class="col-4">Column one</div>
<div class="col-4">Column two</div>
<div class="col-4">Column three</div>
</div>
</div>

<!-- JS files: jQuery first, then Popper.js, then Bootstrap JS -->
<!-- Added to bottom of <body> for better performance -->
<script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js"></script>
</body>
</html>


### Details
The tutorial on [www.tutorialrepublic.com](https://www.tutorialrepublic.com/twitter-bootstrap-tutorial/) to create a web application.   
