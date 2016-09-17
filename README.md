<div align="center"><img src="https://github.com/JonathanSpeek/spacegrid/blob/master/helmet.png?raw=true"/></div>

A basic, responsive grid layout to help you get started on your next project.
---

### Basic Usage

Download either the spacegrid.min.css or spacegrid.css file and link it to your project.

- ```<link rel="stylesheet" href="path/to/space-grid/css/spacegrid.min.css">```
- ```<link rel="stylesheet" href="path/to/space-grid/css/spacegrid.css">```

Do not forget to add this into the head for the @media queries to function: 

- ```<meta name="viewport" content="width=device-width" />```

![alt tag](https://github.com/JonathanSpeek/spacegrid/blob/master/spacegrid-layout.png?raw=true)

```
<div class="row">
	<div class="space-1">This is 100% width</div>
</div>
```
```
<div class="row">
    <div class="space-3">This is 33.3% width</div>
    <div class="space-3">This is 33.3% width</div>
    <div class="space-3">This is 33.3% width</div>
</div>
```
```
<div class="row">
    <div class="space-2">This is 50% width</div>
    <div class="space-2">This is 50% width</div>
</div>
```
```
<div class="row">
    <div class="space-4">This is 25% width</div>
    <div class="space-4">This is 25% width</div>
    <div class="space-4">This is 25% width</div>
    <div class="space-4">This is 25% width</div>
</div>
```
```
<div class="row">
    <div class="space-3">This is 33.3% width</div>
    <div class="space-66">This is 66.6% width</div>
</div>
```

### Basic Demo Site

Check out a quick and easy [demo](https://jonathanspeek.github.io/spacegrid/).