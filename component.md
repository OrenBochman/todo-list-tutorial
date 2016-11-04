# Component

= Component

 the main componnet is named the index.html 

    ```html
        <app-root>Loading...</app-root>
    ```
    The definition of the main componet is in *app.componnet.ts*. 

    ```ts
        import { Component } from '@angular/core';

        @Component({
        selector: 'app-root',
        template: `
                <todo-list-manager></todo-list-manager>
            `,
            styleUrls: ['./app.component.css']
        })
        export class AppComponent {}        
    ```

    we start with an import and we end by exporting the class

    the componnet it self has three parts
    #. selector - which is the name of the tag that will be used in the html (as was used in  index.html)
    #. the template - if the component is visible it should be composed from some html or other elements. In this case it has a subcomponnent called <todo-list-manager>  
    #. the style or in this case importing an external style sheet. 

    another important aspect of angular 2 project is that all the modules are defined in components are defined in *app.modeule.ts*

    

== commits:

- move app-root template to inline
- add typescript to app-root title: private, type string

Move html to inline



One of the most excellent additions of Ecmascript 6 has introduced multiline strings. Multline strings are delmited by backtics `` (located left of the key for number 1).


Next change the title:


Next we want to add private and type string to title

