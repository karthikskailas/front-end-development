Forms & Inputs
-----------------
<form>:

    Purpose: Creates an HTML form for user input. Forms are used to collect data from the user, which can then be sent to a server.
Attributes:
    action: Specifies the URL where the form data should be submitted (e.g., action="/submit-form").
    method: Specifies the HTTP method to use when sending form data (e.g., method="POST" for sensitive data or GET for simple data submission).
    enctype: Specifies how the form data should be encoded when submitting it to the server (e.g., enctype="multipart/form-data" for file uploads).

===========================================================================================================================================================================

<input>:

    Purpose: Represents an interactive field where users can enter data. The type of input is determined by the type attribute.
Common Attributes:
    type: Specifies the type of input (e.g., type="text", type="password", type="submit", etc.).
    name: Specifies the name of the input field, which is submitted with the form data (e.g., name="username").
    value: Specifies the initial value of the input field (e.g., value="Submit" for a submit button).
    placeholder: Provides a short hint that describes the expected value of the input field (e.g., placeholder="Enter your name").
    required: Specifies that the input field must be filled out before submitting the form.
    readonly: Specifies that the input field is read-only and cannot be modified.
    disabled: Specifies that the input field is disabled and cannot be interacted with.
===========================================================================================================================================================================

<textarea>:

    Purpose: Represents a multi-line text input field.
Attributes:
    name: Specifies the name of the text area, submitted with the form data (e.g., name="message").
    rows: Specifies the visible number of lines in the text area (e.g., rows="5").
    cols: Specifies the visible width of the text area in characters (e.g., cols="40").
    placeholder: Provides a short hint that describes the expected value of the text area (e.g., placeholder="Enter your message").

===========================================================================================================================================================================

<button>:

    Purpose: Represents a clickable button, which can be used to submit forms or trigger JavaScript functions.
Attributes:
    type: Specifies the type of button (e.g., type="button", type="submit", type="reset").
    disabled: Specifies that the button should be disabled and not interactable.

===========================================================================================================================================================================

<select>, <option>:

    Purpose: <select> creates a drop-down list, and <option> defines the items in the list.

Attributes for <select>:
    name: Specifies the name of the drop-down list, submitted with the form data (e.g., name="options").
    multiple: Allows multiple options to be selected.

Attributes for <option>:
    value: Specifies the value sent to the server when the option is selected (e.g., value="option1").
    selected: Specifies that the option should be pre-selected when the page loads.
    
===========================================================================================================================================================================
