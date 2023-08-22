# Drop-Down
Drop-Down Example

How to use

Add drop-down.js to your project

HTML
```
<div class="drop-down left">
    <ul class="menu override">
        <li><div>House</div><i class="fa-solid fa-house"></i></li>
        <li><div>Search</div><i class="fa-solid fa-magnifying-glass"></i></li>
        <li><div>Profile</div><i class="fa-solid fa-user"></i></li>
        <li><div>Send</div><i class="fa-solid fa-envelope"></i></li>
    </ul>
</div>
<div class="drop-down middle">
    <ul class="menu override">
    </ul>
</div>
<div class="drop-down right">
    <ul class="menu override">
    </ul>
</div>
```
JS
```
  import dropDown from "./drop-down";
  dropDown();
```

CSS
```
  .menu.override {
    *add custom css here*
  }
```
