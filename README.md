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

## Todo's
- [ ] Flexbox implementation
- [ ] Add optional components (buttons, navbar, typography, etc.)

#### Contributing to Spacegrid
- [Fork](http://guides.github.com/activities/forking/) the repository and clone it locally. Connect your local to the original ‘upstream’ repository by adding it as a remote. Pull in changes from ‘upstream’ often so that you stay up to date so that when you submit your pull request, merge conflicts will be less likely. See more detailed instructions [here](https://help.github.com/articles/syncing-a-fork).
- Create a [branch](http://guides.github.com/introduction/flow/) for your edits.
- Contribute in the style of the project to the best of your abilities. This may mean using indents, semi colons or comments differently than you would in your own repository, but makes it easier for the maintainer to merge, others to understand and maintain in the future.
- Once you’ve opened a pull request a discussion will start around your proposed changes. Other contributors and users may chime in, but ultimately the decision is made by the maintainer(s). You may be asked to make some changes to your pull request, if so, add more commits to your branch and push them – they’ll automatically go into the existing pull request.
