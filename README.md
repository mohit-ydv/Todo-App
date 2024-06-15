TypeScript Basics<br>
-----------------<br>

=> types:<br>
let name: string;<br>
let age: number = 23;<br>
let isStudent: boolean;<br>
let hobbies: string[];<br>
let role: [number, string];<br>
let id: number | string;<br>
let empCode: any;<br>
let personName: unknown;<br>

=> Create object:<br>
type Person = {<br>
   name: string;<br>
   age: number;<br>
   address?: string;<br>
}<br>

let person: Person = {<br>
	name: 'Mohit',<br>
	age: 27,<br>
}<br>

let lotsOfPerson: Person[];<br>

=> Function:<br>
let printName: (name: string) => void;<br>

=> Alias:<br>
	-type<br>
	-interface<br>

interface Person {<br>
    profession: string;<br>
}

Feature pending :<br>
- Drag & drop todos to completion<br>
- https://youtu.be/FJDVKeh7RJI?si=3KecFe_KeM4PM7_z&t=4049