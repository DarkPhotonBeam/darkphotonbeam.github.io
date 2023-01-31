# photon-generator

## Installation

Either execute directly using 
```shell
npx photon-generator
```
or clone and build yourself.

### How to build:
```shell
npm install && npm run compile
```

Afterwards executable is found at ``build/src/index.js``.

## Usage
### Example Folder structure

- index.html
- meta.json
- blog/
  - first-post/
    - first-post.md
    - meta.json
  - second-post/
    - foo.html
  - whatever/
    - idontcare.md
- about/
  - aboutme.html
  - meta.json
  - style.css
- assets/
  - portrait.jpg
  
### Example meta.json

```json
{
  "title": "A very cool page",
  "name": "Cool Page",
  "keywords": "cool,very cool,the coolest",
  "description": "The very coolest site."
}
```

Every keyword is optional.
"title" generates to <title>, i.e. the title of your tab.
"name" describes what a link linking to this page should be called in auto-generated navigation. "keywords" and "description" are for SEO.

## Coming Soon

* Custom Global Styling
* Custom per page styling
* Nav overrides
