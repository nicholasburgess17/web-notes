### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
const whatToDoForLunch = function(hungry, availableTime) {
  if (!hungry) {
    console.log("Get back to work");
    return;
  }
  if (availableTime <= 20) {
    console.log("Order takeout and eat at the lab");
  } else if (availableTime >= 30) {
    console.log("Are you sure you have this much time?");
  } else {
    console.log("go somewhere nearby");
  }
};

```