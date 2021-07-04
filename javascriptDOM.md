Today I learned about Dom manipulation methods. Specifically the DOM 
tree layout in a html document. For example in html document one can have a 
<div id ="container">. This div container is the parent node with the child nodes
being created in javascript. 
Such as const container = document.querySelector('#container') calling backing to the container id in the HTML document. one can then create create content to manipulate using conter.appendChild(containerchild) to attach that container as a 
child in the dom tree to the parent "container" in the html document.
