# JoesRobotShop

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.0.2.

## Notes/ Things I learned

* the reason why the styleUrl section under decorators is an array is to give you the ability to apply several css files in your component
* the prefix of your selector(in this case bot) is determined by what short word you selected as a prefix in your angular.json
* modules are used to organixe and group content into self contained modules
* you have to declare components in modules before you use them
* OnInit is used to fetch data for your components and is the lifecycle hook that is most frequently used
* attribute binding
* square brackets create a one way binding from component to template
* ngFor is used to loop over each item in an array
* whichever element hosts the ngFor directive will be the element that is duplicated, same goes for the content inside it.
* square brackets bind in the direction from the component to the template while parentheses bind from the template to the component
 * brackets to expression(experession have a return ) parentheses to statements(statements have no return and signal change)
* | this is a pipe | currency this is a currency pipe | currency: 'GBP' this is a pound currency pipe. They're more built in pipes in angular
* injectable decorator marks a class as a service
* pipe function helps you modify data before you subscribe.
* Behavior Subject have next which allows you to add new values into the observable.
* if you use redirectTo you also have to use pathMatch when routing in angular(use pathMatch full when redirecting)
* order matters when routing




## Things that are kind of new
* Behavior Subjects are just observables with extra functionality



