# CSS: Journey to Ninjahood

## cssmania: Mozilla Playground
#### https://mozilladevelopers.github.io/playground/css-grid

1. Grid Layout
2. fr Unit
    - A unit representing a fraction of the available space in the grid container.
3. Mixing Columns
    - <code>grid-template-columns</code> and <code>grid-template-rows</code> accept fixed sizes (px and em) or flexible sizes (% and fr) or a miz of any of those sizes.
4. Position Grid Items
5. Basic Grid Layout
    - Header, sidebar, content1, content2, content3, footer.
6. Template Areas
    - Instead of applying <code>grid-row: 1 / 2</code> or any other size to each area of the main container, use

    ```
    grid-template-areas:
        "header header header"
        "sidebar content-1 content-1"
        "sidebar content-2 content-3"
        "footer footer footer";
    ```

    to each section of the container and then the rest of the css will look like this example:

    ```
    .header {
      grid-area: header;
    }
    ```
