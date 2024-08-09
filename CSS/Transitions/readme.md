## 6. Transitions & Animations

- **`transition`**:
  - **Purpose**: Specifies the transition effect between two states of an element, including the properties to be transitioned, duration, timing function, and delay.
  - **Example**:
    ```css
    button {
        transition: background-color 0.3s ease;
    }
    button:hover {
        background-color: #d35400;
    }
    ```
  - **Explanation**: This smoothly transitions the button's background color over 0.3 seconds when the user hovers over it.