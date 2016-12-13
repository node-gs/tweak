# A small CSS library for tweaking CSS, useful for maintaining a codebase, or fixing/tweaking developer work.

* padding: p
* margin: m

### Position of margin or padding:

* sides: h (horizontal)
* top and bottom: v (vertical)
* top: t
* right: r
* bottom: b
* left: l

### Sizes:

* n: 0px !important
* xxs: 2.5px
* xs: 5px
* sm: 10px
* m: 15px
* md: 20px
* lg: 30px
* xl: 50px

### Examples:

`m-t-xs` = margin top extra small = `margin-top: 5px;`

`.p-h-xl` = padding horizontal extra large = `padding: 0 50px;`

------------

### Text Alignment

* ta: text align

* r: right;
* l: left;
* c: center;

* xs: devices up to 768px
* sm: devices up to 968px;
* md: devices up to 1200px;
* lg: devices larger than 1200px;

### Examples:

`.ta-c-xs .ta-l-sm` = `text-align: center;` up to 768px and `text-align: left` on viewports > 768px 