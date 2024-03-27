# JoesRobotShop

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.0.2.

## Notes/ Things I learned

#### Getting Started With Angular
* the reason why the styleUrl section under decorators is an array is to give you the ability to apply several css files in your component
* the prefix of your selector(in this case bot) is determined by what short word you selected as a prefix in your angular.json
* modules are used to organize and group content into self contained modules
* you have to declare components in modules before you use them
* OnInit is used to fetch data for your components and is the lifecycle hook that is most frequently used

#### Using Angular Template Syntax
* attribute binding
* square brackets create a one way binding from component to template
* ngFor is used to loop over each item in an array
* whichever element hosts the ngFor directive will be the element that is duplicated, same goes for the content inside it.
* square brackets bind in the direction from the component to the template while parentheses bind from the template to the component
 * brackets to expression(experession have a return ) parentheses to statements(statements have no return and signal change)
* | this is a pipe | currency this is a currency pipe | currency: 'GBP' this is a pound currency pipe. They're more built in pipes in angular

#### Communicating Between Angular Components
* injectable decorator marks a class as a service
* pipe function helps you modify data before you subscribe.
* Behavior Subjects have next which allows you to add new values into the observable.

#### Routing and Navigating With Angular
* if you use redirectTo you also have to use pathMatch when routing in angular(use pathMatch full when redirecting)
* order matters when routing

#### Creating Angular Forms
* ngModel since it has both parentheses and brackets is a way to bind data two ways ( ie () from model to template and [] from template to model [(ngModel)])
* you can also use the built in error function when you subscribe to an observable to display user feedback
* template variables while not exclusive to forms are generally discouraged to use outside of forms unless you have a really good use case for them
* <em> is emphasis and can use to display form validation messages or errors

#### Organizing Angular Applications With Modules
 * a module is a container that can contain components, custom pipes,services and routes
 * default modules include all of the components we have included in our app
 * we don't have to be explicit with  services in our modules just because if a service is used in a component that we have included in our main module then it already belongs to the module.
 * it's unusual to put components in a routing module usually this module has no service or component
 * the reason we export the router module is so that the main module/ the rest of the application can use it( example siteHeader component uses routerLink)
 
#### Testing Angular Applications
* E2E are end to end tests the entire applciation
* Unit and E2E tests are great at stopping regression bugs


## Things that are kind of new
* Behavior Subjects are just observables with extra functionality



