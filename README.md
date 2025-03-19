## Commit 1 Reflection

In this milestone, I built a simple Rust web server that listens for TCP connections at `127.0.0.1:7878`. I started by printing a message each time a client connected, then moved the connection handling into its own function to keep the code organized. I also learned how to deal with multiple requests and fix small warnings. This hands-on experience made the inner workings of a web server much clearer and set the stage for future improvements.

## Commit 2 Reflection

![commit 2 screenshot](./commit2.png)
This milestone focused on returning actual HTML to the browser. I updated the `handle_connection` method to build a proper HTTP response and serve a simple `hello.html` file. It was a great introduction to how HTTP responses work (status line, headers, body) and how Rust can read files and send them back to the client.