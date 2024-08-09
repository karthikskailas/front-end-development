## 2. Box Model

- **`margin`**:
  - **Purpose**: Controls the space outside of an element, between the element and its neighbors. It can be set for all sides or individually (top, right, bottom, left).
  - **Example**:
    ```css
    div {
        margin: 10px;
    }
    ```
  - **Explanation**: This sets a 10px margin around all `<div>` elements.

- **`padding`**:
  - **Purpose**: Controls the space inside an element, between the content and the element's border. Like margin, it can be set for all sides or individually.
  - **Example**:
    ```css
    .container {
        padding: 20px;
    }
    ```
  - **Explanation**: This sets 20px of padding inside the `.container` element, creating space between the content and the border.

- **`border`**:
  - **Purpose**: Defines the border around an element. It can include the border width, style (e.g., `solid`, `dashed`, `dotted`), and color.
  - **Example**:
    ```css
    img {
        border: 2px solid #000;
    }
    ```
  - **Explanation**: This adds a 2px solid black border around all images.

- **`width`, `height`**:
  - **Purpose**: Sets the width and height of an element. These can be defined in pixels, percentages, or other units.
  - **Example**:
    ```css
    .box {
        width: 300px;
        height: 200px;
    }
    ```
  - **Explanation**: This defines a box that is 300 pixels wide and 200 pixels tall.