<h1>No BS Framework</h1>
<p>This is a project which aims to recreate a simplified version of bootstrap's grid with scss without actually including bootstrap and needing to overwrite a million bootstrap things.</p>
<p>The base markup and class structure will basically remain the same from standard bootstrap; ie: the use of 'container', 'row' and various 'col-' classes.</p>
<p>The major differnce here is both base 10 as well as the standard base 12 grid classes are included. Grid classes are based on percentage of 100; so col-sm-33 is 33% of the container width, col-sm-83 is 83% of the container width and so on. This allows for more complexity and flexibilty in your designs and builds.</p>

```html
<div class="row">
    <div class="col-xs-8">
        <p>col-xs-8</p>
    </div>
    <div class="col-xs-91">
        <p>col-xs-91</p>
    </div>
    <div class="col-xs-16">
        <p>col-xs-16</p>
    </div>
    <div class="col-xs-83">
        <p>col-xs-83</p>
    </div>
    <div class="col-xs-25">
        <p>col-xs-25</p>
    </div>
    <div class="col-xs-75">
        <p>col-xs-75</p>
    </div>
    <div class="col-xs-33">
        <p>col-xs-33</p>
    </div>
    <div class="col-xs-66">
        <p>col-xs-66</p>
    </div>
    <div class="col-xs-41">
        <p>col-xs-41</p>
    </div>
    <div class="col-xs-58">
        <p>col-xs-58</p>
    </div>
</div>
```

<a href="https://codepen.io/msbtterswrth/pen/pdzzjB">View the Codepen</a>
