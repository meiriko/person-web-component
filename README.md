Task
===
Create a person view component as a same element (same HTML syntax) with different scopes of view.

1. **Large**
2. **Medium**
3. **Small**

The component should highlight all persons that are VP (i.e. have the term VP in their title) with a different background color and a border.

Bonus 1:
When clicking on a small or medium contact, display it in the large contact.

Bonus 2:
Enable sorting of contacts by drag/drop in the small and medium list.

![Person view component](/design-spec.fw.png "Spec")

Write as less code as possible, with focus on clean and reusable code. Try to take advantage from frameworks available below or add another familiar to you.
The project use a number of open source projects to work properly.

**Example of person item data:**
```json
{
    "image": "09811ea.jpg",
    "fullName": "Roee Adler",
    "position": "Chief Product Officer",
    "company": "WeWork",
    "summary": ""
}
```

### Technologies

* [Bootstrap] - UI boilerplate
* [LESS] - CSS pre-processor
* [AngularJS] - HTML enhanced for web apps
* [jQuery] - WTF!?
* [Node.js] - Evented I/O for the backend
* [Gulp] - The streaming build system

### How to run the project?

Node.js sould be installed.

- Download this repository
- Open terminal in project folder
- Run dependencies installation
```sh
npm install
```

- Run project with gulp
```sh
gulp
```

- Go to: [http://localhost:3000/](http://localhost:3000/).


[Bootstrap]:http://getbootstrap.com/
[LESS]:http://lesscss.org/
[AngularJS]:http://angularjs.org
[jQuery]:http://jquery.com/
[Node.js]:http://nodejs.org
[Gulp]:http://gulpjs.com
