# Library_management_front_end
"function Book(name, author, type) {
    this.name = name;
    this.author = author;
    this.type = type;
}"
Here 'Book' is the constructor function which takes 3 parameters(name,author,type)
'this' keyword is the instance of the object.this keyword is similar to 'self' keyword in Python
the 'new' keyword creates new object

"function Display() {

}"
This function doesn't have any functionality here,although it can be used to display any message on console log.

"Display.prototype.add = function (book) {
    console.log("Adding to UI");
    tableBody = document.getElementById('tableBody');
    let uiString = `<tr>
                        <td>${book.name}</td>
                        <td>${book.author}</td>
                        <td>${book.type}</td>
                    </tr>`;
    tableBody.innerHTML += uiString;
}"
'prototype' is used to add new method or properties to constructor.
