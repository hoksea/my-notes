+ 3 levels:
`container-fluid`  >  `row`  >  `col-md-*`

+ Those `col-*-*` inside each row * sum up must be 12, then they will stay on the same row.

+ Inside the `<div class="col-md-*"></div>`, create another `<div></div>`, and your actual content will be put inside this `div`.

|    col   |    device    |   size   |
| -------- |:------------:| --------:|
| col-lg-* | Large        | >=1200px |
| col-md-* | Medium       | >992px   |
| col-sm-* | Small        | >=768px  |
| col-xs-* | Extra-small  | <768px   |

![BootstrapGrid](/image/bootstrapGrid.png)

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

ACTUAL EXAMPLE:
![BootstrapGrid-example](/image/bootstrap_12grids-explain-example.png)
