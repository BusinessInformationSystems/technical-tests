Angular components
==================

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
	selector: 'intro',
	template: `<h1>Introduction to {{productName}}!</h1>`,
	styles: [`h1 { font-family: Lato; }`]
})
export class IntroComponent  {
	@Input() productName: string;
}
```


Scope
-----
Please tell what will be displayed in each case:

- `<intro productName="SpaceShipApp"></welcome>`
- `<intro></intro>`
- `<intro productName="{{ name }}"></intro>`
- `<intro [productName]="{{ name }}"></intro>`
- `<intro [productName]="name"></intro>`
- `<intro productName=" 'name' "></intro>`
- `<intro productName="{{'name'}}"></intro>`
- `<intro (productName)="name"></intro>`



