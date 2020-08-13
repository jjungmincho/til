# Nesting

To nest your content with the default grid, add a new .row and set of .col-sm-_ columns within an existing .col-sm-_ column. Nested rows should include a set of columns that add up to 12 or fewer (it is not required that you use all 12 available columns).

```
<div class="row">
  <div class="col-sm-9">
    Level 1: .col-sm-9
    <div class="row">
      <div class="col-8 col-sm-6">
        Level 2: .col-8 .col-sm-6
      </div>
      <div class="col-4 col-sm-6">
        Level 2: .col-4 .col-sm-6
      </div>
    </div>
  </div>
</div>
```

## Reference

[Bootstrap](https://getbootstrap.com/docs/4.1/layout/grid/#nesting)
