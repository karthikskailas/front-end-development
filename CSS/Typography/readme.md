## 1. Typography

- **`font-family`**:
  - **Purpose**: Specifies the font or a list of fonts for the text. If the first font is unavailable, the browser will try the next one in the list.
  - **Example**:
    ```css
    p {
        font-family: Arial, Helvetica, sans-serif;
    }
    ```
  - **Explanation**: This example sets the font of paragraphs to Arial. If Arial is not available, it falls back to Helvetica, and if neither is available, it uses a generic sans-serif font.

- **`font-size`**:
  - **Purpose**: Sets the size of the font. It can be defined in pixels (px), ems, percentages, or other units.
  - **Example**:
    ```css
    h1 {
        font-size: 2em;
    }
    ```
  - **Explanation**: This sets the font size of all `<h1>` elements to 2 times the size of the parent element's font size.

- **`font-weight`**:
  - **Purpose**: Defines the thickness or boldness of the text. Common values are `normal`, `bold`, `lighter`, or numeric values ranging from 100 to 900.
  - **Example**:
    ```css
    strong {
        font-weight: bold;
    }
    ```
  - **Explanation**: This makes all text inside `<strong>` elements appear bold.

- **`color`**:
  - **Purpose**: Sets the color of the text. It can be defined using color names, HEX codes, RGB, or HSL values.
  - **Example**:
    ```css
    h2 {
        color: #e67e22;
    }
    ```
  - **Explanation**: This sets the color of all `<h2>` elements to a specific shade of orange using a HEX color code.

- **`text-align`**:
  - **Purpose**: Controls the horizontal alignment of the text within its container. Common values include `left`, `right`, `center`, and `justify`.
  - **Example**:
    ```css
    p {
        text-align: justify;
    }
    ```
  - **Explanation**: This justifies the text in all `<p>` elements, making the text edges align evenly on both sides.

- **`line-height`**:
  - **Purpose**: Specifies the amount of space between lines of text. It can be set in units or as a multiple of the font size.
  - **Example**:
    ```css
    body {
        line-height: 1.5;
    }
    ```
  - **Explanation**: This sets the line height for the entire document to 1.5 times the size of the text, improving readability.
