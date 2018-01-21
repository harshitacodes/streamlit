#### Demo

- objectives
  - **I want Lukas to appreciate the full power of logging as s company.**
    - Three really nice demos.
      - Speed Test
      - Keras Test
    - ONE OF
      - really beautiful slides about what's possible when this becomes a first
        class citizen in the logging world
      - The ability to do a save into an Amazon Store
        - Maybe first a janky version storing to a local file.
        - Use Aamazon Parse to store a separate version.
  - **I want lukas to think I'm a great coder.**
    - rename tiny_notebook to printf
    - Pip install method
    - Get the name printf.com.

#### Todo After the Demo

- Fix the problem with calling __call__ on multiple values
- Clean things up.
  - Rename it from tiny-notebook to printf
  - Rename notebook everywhere to printf.
  - Figure out how to make an installer with pip
  - Give it a nice favicon. (maybe the connect icon?)
- Get rid of DeltaList and just send Deltas
- Switch to `enqueue` and `dequeue` for the DeltaQueue
- Clean up some names in the code.
  - Make the `DataFrame` prop into `df`
  - make the `Chart` prop into `chart`
- Fix the problem where you have to sleep for another second.
- "info"     : prints out df.info() on a DataFrame-like object

#### More things to play with and try

- Reimplement core logic in Redux
- Fix resizing bug with the table dimensions.
- Put in properties for CHART_COMPONENTS
- Fix up charts.
  - Make chart component recursive.
  - Fix `radial_bar_chart`
  - Get `pie_chart` to work.. put dataframes in the components.   
- Fix the problem when you resize a table.
- Follow the docker tutorial
- Install node within docker
- make the awesomest library ever

#### Protobuf Messages

- Text
- Chart
- Image
- Dataframe

- Update
  - id
  - element

- AddRows
  - id
  - rows