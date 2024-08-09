## 3. Backgrounds

- **`background-color`**:
  - **Purpose**: Sets the background color of an element.
  - **Example**:
    ```css
    header {
        background-color: #e67e22;
    }
    ```
  - **Explanation**: This sets the background color of the header to orange.

- **`background-image`**:
  - **Purpose**: Sets an image as the background of an element.
  - **Example**:
    ```css
    body {
        background-image: url('background.jpg');
    }
    ```
  - **Explanation**: This sets a specified image as the background for the entire document.

- **`background-size`**:
  - **Purpose**: Specifies the size of the background image. Values can be `cover`, `contain`, or specific dimensions.
  - **Example**:
    ```css
    .hero {
        background-size: cover;
    }
    ```
  - **Explanation**: This makes the background image cover the entire area of the `.hero` element, scaling the image as necessary.

- **`background-repeat`**:
  - **Purpose**: Defines how the background image repeats. It can be set to `repeat`, `repeat-x`, `repeat-y`, or `no-repeat`.
  - **Example**:
    ```css
    .pattern {
        background-repeat: repeat-x;
    }
    ```
  - **Explanation**: This repeats the background image horizontally across the `.pattern` element.
