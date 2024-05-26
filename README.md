# MyFramework Mini Framework

## Introduction

MyFramework is a lightweight JavaScript mini-framework designed to simplify the process of creating and managing tasks in a web application. It provides a set of functions and classes that facilitate the manipulation of DOM elements and the handling of user interactions.

## Getting Started

To use MyFramework in your project, follow these steps:

1. **Import MyFramework:**

    ```javascript
    import { MyFramework, ajoutTache } from "./main.js";
    ```

2. **Create an instance of MyFramework:**

    ```javascript
    const maListe = new MyFramework();
    ```

3. **Use `ajoutTache` function to add tasks:**

    ```javascript
    ajoutTache(maListe);
    ```

## Functions and Classes

### `ajoutTache(maListe)`

This function is responsible for adding tasks to the DOM. It includes functionality for creating, deleting, and updating tasks. It utilizes the MyFramework class methods to manipulate DOM elements.

### `MyFramework` Class

#### Methods:

- **`createElement(tagName, attributes = {}, content = '')`**: Creates a new DOM element with the specified tag, attributes, and content.

- **`addElement(parent, child)`**: Adds a child DOM element to a parent element.

- **`modifyElementContent(element, newContent)`**: Modifies the content of a DOM element.

- **`addEvent(element, eventType, eventHandler)`**: Adds an event listener to a DOM element.

- **`removeElement(parent, child)`**: Removes a child element from its parent.

- **`setStyle(element, styles)`**: Applies CSS styles to a DOM element.

- **`modifyAttributes(element, newAttributes)`**: Modifies the attributes of a DOM element.

- **`removeAllChildren(parent)`**: Removes all child elements from a parent.

- **`changeClass(element, oldClass, newClass)`**: Replaces a specified class in a DOM element.

## Example Usage

```javascript
const maListe = new MyFramework();

// Create a new task
ajoutTache(maListe);
```

Feel free to explore and customize the MyFramework mini-framework to suit your specific needs. For more details on available methods, refer to the comments within the code or the documentation provided.