<div align="center">
    <img style="width:100px;height:auto;" src="https://cdn.rawgit.com/JonathanSpeek/spacegrid/master/spacegrid-logo.svg"/>
    <p align="center">
  <img src="https://img.shields.io/github/tag/jonathanspeek/spacegrid.svg" alt="Tag">
  <a href="https://rubygems.org/gems/spacegrid"><img src="https://img.shields.io/gem/dt/spacegrid.svg" alt="Downloads"></a>
  <a href="https://www.npmjs.com/package/spacegrid"><img src="https://img.shields.io/npm/dt/spacegrid.svg" alt="Downloads"></a>
  <a href="https://github.com/JonathanSpeek/spacegrid/blob/master/LICENSE.txt"><img src="https://img.shields.io/github/license/jonathanspeek/spacegrid.svg" alt="License"></a>
</p>
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
		<link rel="stylesheet" href="path_to/space-grid/css/spacegrid.min.css">
	</head>
</html>
```

## Check out a basic demo [here](http://spacegrid.jonathanspeek.com/), or see it out in the wild [here](http://about.jonathanspeek.com/).


## Quick Installation

### Install with NPM
See [documentation](https://www.npmjs.com/search?q=spacegrid)

    $ npm install spacegrid

Add this to the head of your pages:
```html
<script src="path_to/node_modules/spacegrid/build/bundle.js"></script>
```

### Install with Bower
See [documentation](https://github.com/JonathanSpeek/spacegrid_bower.git)

    $ bower install spacegrid

Add this to the head of your pages:
```html
<link href="path_to/bower_components/spacegrid/spacegrid.css" rel="stylesheet" type="text/css">
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
### Compatibility
#### CSS3 media queries are utilitized, which are well-supported amongst most modern browsers. Here's a compatibility [chart](http://caniuse.com/#search=CSS3%20Media%20Queries).
---

## Ghost Theme
- For you [Ghost](http://ghost.org) bloggers, I've made a [theme](https://github.com/JonathanSpeek/spacegrid_ghost_theme) using Spacegrid

## Contributing to Spacegrid
- Spacegrid CSS is currently maintained by [@JonathanSpeek](http://github.com/jonathanspeek)
- Checkout the [Contribution Guide](https://github.com/JonathanSpeek/spacegrid/blob/master/CONTRIBUTING.md) if you'd like to lend a hand.

## Follow Us
- For announcements and updates, follow Spacegrid CSS on Twitter: [@spacegridcss](http://twitter.com/spacegridcss)
- Feel free to buy me a [coffee](https://ko-fi.com/A378OHL)! 
