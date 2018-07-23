Alien Reporter
==============

Mobil Information Systems would like you to take a programming test.

Instructions
------------
Please create a gist with your solution and send us back the link.

Description
-----------
Consider the following component:

 ```es6
import { Component, Input } from '@angular/core';

@Component({
  selector: 'welcome',
  template: `<h1>Welcome to {{name}}!</h1>`,
  styles: [`h1 { font-family: Lato; }`]
})
export class WelcomeComponent  {
  @Input() name: string;
}
 ```

Scope
-----
The application will display the form Id, last changed date and last changed by at the top of the page, then display a list of all the elements in the form array. The user must be able to reorder any element in the list by simple drag and drop.

Valuation
---------
You can use any javascript/CSS framework you like although the Angular 4+ framework is preferred. Priority will be given to functionality then to attractiveness and usability of UI. Any use of programming patterns, code conventions, best practices and general coding style (including appropriate commenting) will be taken into consideration and valued accordingly. Please accompany your submission with a description of the work done and reference to any framework, plugin and component used across the application. 

Points will be given to each aspect of the application up to a total of 10 points:
- Functionality: 2 points max
- Usability: 2 points max
- Coding style: 2 points max
- Appropriate use of frameworks: 2 points max
- Documentation: 2 points max

