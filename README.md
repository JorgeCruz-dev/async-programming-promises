This is a small repo in which I learned about async programming using promises, async/await, axios and xhr calls.

In order to run it, please execute `npm install` so as to get the node_modules.
Then, run `npm run dev` command.

Once it's running, go to `http://localhost:3000/home`. You'll see 4 menus

-   Understanding Promises
Understanding how xhr works and how was the concept of callback hell.

-   Consuming Promises

Contains different usages for Promises, such as resolve and reject a promise with setTimeout and setInterval, stop an Interval call. It also contains how to use Promise.all, Promise.allSettled and Promise.race

-   Creating Promises
Contains ways to use catch. Also a way to use chain and chainCatch and the usage of finally

-   Iterating with Async and Await
usage of async/await. Also contains how to make a concurrent call, a parallel call and how to use chains with async/await