# position.css

A simple CSS layout & positioning library created to ease CSS position absolute & relative curves.

I recently used CSS position properties on my portfolio page (https://devhammed.github.io) and it is not easy to put things in desired position and i know am not the only only experiencing this so i created thi minimal utility to make positioning easy as ABC.

## Classes

Below is the usage and documentation of classes provided by this library.

### .position
> This is a base class for container parent elements, it is required if you don't want the positioned elements to be positioned in relative to the viewport.

```html
  <div class="position">
    ...
  </div>
```

### .position-left
> Position element to the vertical left of the containing `.position` element or viewport.

```html
  <div class="position">
    <div class="position-left">
      ...
    </div>
  </div>
```

### .position-right
> Position element to the vertical right of the containing `.position` element or viewport.

```html
  <div class="position">
    <div class="position-right">
      ...
    </div>
  </div>
```

### .position-center
> Position element to the vertical center of the containing `.position` element or viewport.

```html
  <div class="position">
    <div class="position-center">
      ...
    </div>
  </div>
```

### .position-top-left
> Position element to the top-left of the containing `.position` element or viewport.

```html
  <div class="position">
    <div class="position-top-left">
      ...
    </div>
  </div>
```

### .position-top-right
> Position element to the top-right of the containing `.position` element or viewport.

```html
  <div class="position">
    <div class="position-top-right">
      ...
    </div>
  </div>
```

### .position-top-center
> Position element to the top-center of the containing `.position` element or viewport.

```html
  <div class="position">
    <div class="position-top-center">
      ...
    </div>
  </div>
```

### .position-bottom-left
> Position element to the bottom-left of the containing `.position` element or viewport.

```html
  <div class="position">
    <div class="position-bottom-left">
      ...
    </div>
  </div>
```

### .position-right
> Position element to the bottom-right of the containing `.position` element or viewport.

```html
  <div class="position">
    <div class="position-bottom-right">
      ...
    </div>
  </div>
```

### .position-bottom-center
> Position element to the center of the containing `.position` element or viewport.

```html
  <div class="position">
    <div class="position-bottom-center">
      ...
    </div>
  </div>
```

## TODO
- Add responsive classes (sm, md, lg)

## Contribute
Check above TODO, can you add any of it or do you want to improve the existing CSS code?

Fork & Send your pull request to contribute, i will review it and merge.
