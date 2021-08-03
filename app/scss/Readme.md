If you want to use some bootstrap component go to
'node_modules/bootstrap/scss/bootstrap.min.scss' and choose your component
after select import that you need copy it and paste to your own component

Example: 

    bootstrap.scss
        - @import "nav";

    MOVE IT TO YOUR COMPONENT AND CHANGE THE PATH

    _my-component.scss
        - @import "bootstrap/scss/nav"

Just add the prefix "bootstrap/scss/" to your import - done!