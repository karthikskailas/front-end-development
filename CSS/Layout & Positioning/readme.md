## 4. Layout & Positioning

- **`display`**:
  - **Purpose**: Controls the layout behavior of an element. Common values include `block`, `inline`, `inline-block`, `flex`, and `none`.
  - **Example**:
    ```css
    nav {
        display: flex;
    }
    ```
  - **Explanation**: This makes the `<nav>` element a flex container, allowing for flexible layouts of its children.

- **`position`**:
  - **Purpose**: Specifies how an element is positioned in the document. Common values include `static`, `relative`, `absolute`, `fixed`, and `sticky`.
  - **Example**:
    ```css
    .box {
        position: absolute;
        top: 50px;
        left: 100px;
    }
    ```
  - **Explanation**: This positions the `.box` element 50 pixels from the top and 100 pixels from the left of its containing block.

- **`top`, `bottom`, `left`, `right`**:
  - **Purpose**: These properties control the offset of a positioned element relative to its containing block.
  - **Example**:
    ```css
    .menu {
        position: fixed;
        top: 0;
        right: 0;
    }
    ```
  - **Explanation**: This fixes the `.menu` element at the top-right corner of the viewport.
