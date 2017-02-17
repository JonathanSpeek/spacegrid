<div align="center">
    <img style="width:100px;height:auto;" src="https://cdn.rawgit.com/JonathanSpeek/spacegrid/master/spacegrid-logo.svg"/>
</div>

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

## Check out a basic demo [here](https://jonathanspeek.github.io/spacegrid/), or see it out in the wild [here](http://jspeek.me).

![alt tag](https://github.com/JonathanSpeek/spacegrid/blob/master/spacegrid-layout.png?raw=true)

## Quick Installation

### Install with NPM
See [documentation](https://www.npmjs.com/search?q=spacegrid)

    $ npm install spacegrid

Add this to the head of your pages:
```html
<script src="build/bundle.js"></script>
```

### Install using Ruby Gem
See [documentation](https://rubygems.org/gems/spacegrid)

Add this line to your application's Gemfile:

```ruby
gem 'spacegrid'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install spacegrid

Add this to your application.css file:
```css
*= require spacegrid
```

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
```
---
### With Added Flexibility

#### Here are a few add-ons:

* 25% width
* 40% width
* 60% width
* 66% width
* 75% width

```
<!-- these works too :D -->

<div class="row">
    <div class="space-3">This is 33.3% width</div>
    <div class="space-66">This is 66.6% width</div>
</div>

<div class="row">
    <div class="space-75">This is 75% width</div>
    <div class="space-25">This is 25% width</div>
</div>

<div class="row">
    <div class="space-40">This is 40% width</div>
    <div class="space-60">This is 60% width</div>
</div>
```
---
#### Customize widths by adding your own!
