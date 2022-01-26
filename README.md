Used the const declaration for variables since most of the variables would not be reassigned throughout the file. After using several methods for manipulating the DOM in this project, I believe I have a basic understanding of the process. First, I used addEventListener(). This gave added benefit of not having to add the event listeners in the HTML file, thus causing less clutter. 
Next was using innerHTML to render text as textContent wasn’t able to render list items as needed. Finally, used input.value to retrieve the values users entered into the input field on the extension. 

Taking another forward step in the world of functions, I used function parameters. Defining the parameters in the render() function allowed the ability to use the variable inside the body of the function as well. It also required to pass in the argument of myLeads when the function was invoked.

Next were template strings/literals. By using the $ and {}, I was able to escape out of the string. This helps to refactor code and gives the ability to write strings on multiple lines, making it easier for humans to understand. 

Moving forward something super cool was localStorage. This ablility to save things to localStorage allowed access to work across page refreshes. This is a first exposure to a database, a simple one, but a database nonetheless.

Working with localStorage forces us to look at JSON. After turing an array into a JSON array using JSON.stringify, and going the other way around with JSON.parse, I can say this is a very common way of storing data in web development. I also began to configure the manifest.json file which helps with deployment.

The final thing that sums up the scope of this project would be objects inside of arrays. This is a very common concept within web development. One of the most common things to do is fetch out an index with the value of an object. ( e.g myLeads.push(tabs[0].url) )
 