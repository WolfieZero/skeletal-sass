# Skeletal Sass

Boilerplate for Sass projects


## Introduction

...


## Developing

...


## Definition of Layers

### Config
- ...

### Base
- Sets the sensible defaults for styles.

### Libraries
- Sass mixins and functions.
- Can be use by components and specifics.

### Layouts
- ...

### Components
- Self-contained and should be reusable.
- Should only think of itself and never be dependant on other CSS classes but
  be allowed to be used with others.
- They can use Sass libraries or variables that are external to their scope.

### Specifics
- Specific to a particular section.
- Not written to be reused but more one off use.


## Resources

- [@include-media](http://include-media.com/)


## License

MIT License (MIT) - see [LICENSE.md](LICENSE.md)
