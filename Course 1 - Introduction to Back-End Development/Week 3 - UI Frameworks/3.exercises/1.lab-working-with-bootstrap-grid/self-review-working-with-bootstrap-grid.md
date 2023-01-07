# Self Review: Working with Bootstrap Grid

1. When viewing the page in the web browser, is the logo centered on the webpage?
    - Yes
    - No
    ```
    Answer: Yes
    Explanation: The text-center CSS class centers the image.
    ```

2. When viewing the page in the web browser on a desktop, do the four menu items display in one column?
    - Yes
    - No
    ```
    Answer: No
    Explanation: The two div elements take up half the row each on desktop. This is specified using the col-lg-6 CSS class (6 out of 12 Bootstrap columns).
    ```

3. Use the developer tools to preview the webpage on a mobile device. How many columns does the content display in?
    - 0
    - 1
    - 2
    - 3
    ```
    Answer: 1
    Explanation: The two div elements take up a full row each on mobile. This is specified using the col-12 CSS class (12 out of 12 Bootstrap columns).
    ```