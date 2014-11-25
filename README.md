# Easy to Remember Flat-UI colors.

## What is this?
A set of easy to remember sass variables referencing colors from
[Flat UI](http://designmodo.github.io/Flat-UI/).

## How does it work?

Colors are divided into 7 named groups:
  * **blue**        (4 shades)
  * **gray**        (4 shades)
  * **green**       (4 shades)
  * **orange**      (3 shades)
  * **purple**      (2 shades)
  * **red**         (2 shades)
  * **yellow**      (1 shade)

#### Want the lightest shade of gray from Flat UI?
```sass
  #myDiv {
    color: $flat-gray-1; // clouds
  }
```

#### How about darkes shade of blue?
```sass
  #myDiv {
    color: $flat-blue-4; // midnight blue
  }
```

#### Or the darkest shade of orange:
```sass
  #myDiv {
    color: $flat-orange-3; // pumpkin
  }
```

#### Or the only shade of yellow:
```sass
  #myDiv {
    color: $flat-yellow-1; // sun flower
  }
```

### Naming Convention

Each Flat-UI color is assigned an alias using: **"$flat-{group name}-{shade number}"**
where:
  * ```{group name}``` is one of the color groups above
  * ```{shade number}``` is a number between 1 and the number of shades in that group
  (1 being the lightest shade).

Thus, since the ```purple``` group has two shades, there are two variables:
```$flat-purple-1```, and ```$flat-purple-2```.

## Install
Clone the repo:
```sh
 git clone git@github.com:obibring/flat-ui-colors-sass.git
```

Copy ```_flat_colors.scss``` into your sass import path:
```sh
  cp flat-ui-colors-sass/_flat_colors.scss <some directory in your sass include path>
```

Import the file at the top of your stylesheet:
```sass
  @import "flat-colors";
```
