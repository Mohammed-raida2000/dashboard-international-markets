<!-- # Sass-Architecture-Structure

sass/
|
|– base/
|   |– _reset.scss       # Reset ALl Elements
|   |- _container.scss   # Main Container For Layouts
|   |– _typography.scss  # Typography rules
|   |- _base.scss        # @forward All Files in base Folder
|   ...                  # Etc…
|
|– components/
|   |– _buttons.scss     # Buttons
|   |– _components.scss  # @forward All Files in components Folder
|   ...                  # Etc…
|
|– helpers/
|   |– _variables.scss   # Sass Variables
|   |– _functions.scss   # Sass Functions
|   |– _mixins.scss      # Sass Mixins
|   |– _breakPoints.scss # To make layouts Responsive
|   |– index.scss        # @forward All Files in helpers Folder
|   ...                  # Etc…
|
|– layout/
|   |– _header.scss      # Header
|   |– _navigation.scss  # Navigation
|   |– _grid.scss        # Grid system
|   |– _footer.scss      # Footer
|   |– _sidebar.scss     # sidebar
|   |– _layout.scss      # @forward All Files in layout Folder
|   ...                  # Etc…
|
|– pages/
|   |– _homepage.scss    # Home specific styles
|   |– _contact.scss     # Contact specific styles
|   |– _about.scss       # Contact specific styles
|   |– pages.scss        # @forward All Files in pages Folder
|   ...                  # Etc…
|
|– vendors/
|   |– _bootstrap.scss   # Bootstrap
|   |– _fontawesome.scss # fontawesome Library
|   |– _normalize.scss   # normalize
|   ...                  # Etc…
|
`– main.scss             # Primary Sass file
``` -->


- Below is one of examples of a website layout using the semantic elements.

![semantic elements.] (https://res.cloudinary.com/practicaldev/image/fetch/s--LwQ0kiOg--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_800/https://raw.githubusercontent.com/ToshitaSingh/Files/master/dark-html5semantics.png)   
- https://dev.to/toshitasingh/a-beginners-guide-to-html5-semantics-1c2p