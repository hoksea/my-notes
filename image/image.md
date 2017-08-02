3 levels:
`container-fluid`  >  `row`  >  `col-md-*`

Those `col-md-*` inside each row * sum up must be 12. So that they will stay on the same row.
In the `<div class="col-md-*"></div>`, create another `<div></div>`, and this div is the div that contain your actual content.

EXAMPLE:
```html
<div class="container-fluid">
   <div class="row">
      <div class="col-md-6"><div>
      <div class="col-md-6"><div>
    </div>
   <div class="row">
      <div class="col-md-4"><div>
      <div class="col-md-4"><div>
      <div class="col-md-4"><div>
    </div>
   <div class="row">
      <div class="col-md-7"><div>
      <div class="col-md-5"><div>
    </div>
   <div class="row">
      <div class="col-md-8"><div>
      <div class="col-md-4"><div>
    </div>
</div>  
```

![Bootstrap grid](bootstrapGrid.png)
