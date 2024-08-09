## 5. Flexbox (for responsive layouts)

-   **`display: flex`**:

    -   **Purpose**: Enables a flex context, making the container flexible and
        allowing its children to be arranged in a more responsive manner.
    -   **Example**:
        ```css
        .flex-container {
        	display: flex;
        }
        ```
    -   **Explanation**: This turns `.flex-container` into a flex container,
        with its children becoming flex items.

-   **`flex-direction`**:

    -   **Purpose**: Specifies the direction of the flex items inside a flex
        container. Common values include `row`, `row-reverse`, `column`, and
        `column-reverse`.
    -   **Example**:
        ```css
        .flex-container {
        	flex-direction: column;
        }
        ```
    -   **Explanation**: This arranges the flex items inside the
        `.flex-container` in a column.

-   **`justify-content`**:

    -   **Purpose**: Defines the alignment of flex items along the main axis
        (x-axis for `row` direction).
    -   **Example**:
        ```css
        .flex-container {
        	justify-content: space-between;
        }
        ```
    -   **Explanation**: This distributes the space between the flex items with
        space between them, leaving equal space at the start and end of the
        container.

-   **`align-items`**:
    -   **Purpose**: Defines the alignment of flex items along the cross axis
        (y-axis for `row` direction).
    -   **Example**:
        ```css
        .flex-container {
        	align-items: center;
        }
        ```
    -   **Explanation**: This aligns the flex items vertically in the center of
        the container.
