<div align="center"><img src="https://github.com/JonathanSpeek/spacegrid/blob/master/helmet.png?raw=true"/></div>

A basic, responsive grid layout to help you get started on your next project.
---

### Setup your project

Download either the [spacegrid.min.css](https://raw.githubusercontent.com/JonathanSpeek/spacegrid/master/spacegrid.min.css) or [spacegrid.css](https://raw.githubusercontent.com/JonathanSpeek/spacegrid/master/spacegrid.css) file and link it to your project:

```html
<html>
	<head>
		<!-- for the @media queries to function -->
		<meta name="viewport" content="width=device-width" />

		<!-- include the space-grid css -->
		<link rel="stylesheet" href="path/to/space-grid/css/spacegrid.min.css">
	</head>
</html>
```

## Check out a quick and easy demo [here](https://jonathanspeek.github.io/spacegrid/).

![alt tag](https://github.com/JonathanSpeek/spacegrid/blob/master/spacegrid-layout.png?raw=true)

### Examples

```html
<!-- full width example -->
<div class="row">
	<div class="space-1">This is 100% width</div>
</div>

<!-- three columns -->
<div class="row">
    <div class="space-3">This is 33.3% width</div>
    <div class="space-3">This is 33.3% width</div>
    <div class="space-3">This is 33.3% width</div>
</div>

<!-- two columns -->
<div class="row">
    <div class="space-2">This is 50% width</div>
    <div class="space-2">This is 50% width</div>
</div>

<!-- four columns -->
<div class="row">
    <div class="space-4">This is 25% width</div>
    <div class="space-4">This is 25% width</div>
    <div class="space-4">This is 25% width</div>
    <div class="space-4">This is 25% width</div>
</div>

<!-- this works too :D -->
<div class="row">
    <div class="space-3">This is 33.3% width</div>
    <div class="space-66">This is 66.6% width</div>
</div>
```
