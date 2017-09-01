
# AngularJS multi-level tab navigation

  - Allows for a nested structure
  - Works with (or without) `ng-repeat`
  - Allows sequencial multiple items selection


## Examples
  
  - TODO
  - [GitHub](http://www.antonio-rodrigues.github.io/nested-tab-navigation)
  

## Usage

  - `npm install nested-tab-navigation`, or get the files [from the repo](./dist).

  - Include `angular.js`, `angular-animate.js`, `nested-tab-navigation.js`, and `nested-tab-navigation.css`:
  ```html
  <link href="nested-tab-navigation.css" rel="stylesheet" />

  <script src="angular.js"></script>
  <script src="angular-animate.js"></script>

  <script src="nested-tab-navigation.js"></script>
  ```

  - Add `nestedTabNavigation` and `ngAnimate` as dependencies to your application module:
  ```js
  angular.module('myApp', ['nestedTabNavigation', 'ngAnimate']);
  ```

  - Put the following markup in your template:
  ```html
  <nested-tab-navigation class="nestedTabNavigation--default" multiple></nested-tab-navigation>
  ```

## API

#### Control

TODO


#### Scope

TODO

##### $tabNavigation

TODO

##### $pane

TODO

#### Events

TODO

## Callbacks

TODO

## Configuration

#### Module

```javascript
TODO
```

#### SCSS
If you are using SASS, you can import nestedTabNavigation.scss file and override the following variables:

```scss
.TODO { content: 'todo'; }
```


## Accessibility

```html
TODO
```