# Skeletal Sass

Boilerplate for Sass projects


## Naming Methodology - BEM

**Block**
`.block-name`
  - Describes its purpose
    - "What is it?" — menu or button
  - Doesn't describe state
    - "What does it look like?" — red or big
 - If a section of code might be reused and it doesn't depend on other page
   components being implemented.

**Element**
`.block-name__element-name`
  - Describes its purpose
    - "What is this?" — item, text, etc.
  - Doesn't describe state
    - "What type, or what does it look like?" — red, big, etc.
  - `block-name__element-name`
  - If a section of code can't be used separately without the parent entity
    (the block).
    - The exception is elements that must be divided into smaller parts –
      subelements – in order to simplify development. In the BEM methodology,
      you can't create elements of elements. In a case like this, instead of
      creating an element, you need to create a service block.

**Modifier**
`.block-name__element-name--modifier-name` or `.block-name--modifier-name`
  - Defines the appearance, state, or behavior of a block or element
    - "What size?" or "Which theme?"


## Definition of Layers

- **Config**
  Setup the base variables of your application incuding colour definitions.

- **Libaries**
  Sass mixins or functions that can be use by any of the layers below.

- **Base**
  Element classes (`.input`, `.button`) or direct (`html`, `body`) that build up
  the base building blocks of the app/site.

- **Components**
  Self contained, reusable blocks of style (`.media`, `.navigation`) that can be
  used in conjuction with other components but never dependant

- **UI**
  Grouped components for specific use cases (`.page-header`, `.site-navigation`)
  but may not nessarly be used more than one within an app/site.


## Resources

- [@include-media](http://include-media.com/)


## License

MIT License (MIT) - see [LICENSE.md](LICENSE.md)
