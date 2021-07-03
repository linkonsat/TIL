Today I learned about key pairs in javascript. 
What it does is allows you store an value with a key in an array.
for example let bob = { org: "machines",
           time: 24, } 
These are treated as objects. key pairs also have a unique loop. 
This unique loop is a for---in loop which iterates over the key pairs.
for example for (let key in bob) {
    alert( key );
    alert (bob[key]);
} 
the for starts the loop with the  key which refers to the org and outputs machine in the second alert.
Thereby allowing these key pairs to be called in the context of a for loop. 
