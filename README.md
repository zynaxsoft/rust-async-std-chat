# Async chat server/client

![](https://github.com/zynaxsoft/rust-async-std-chat/raw/master/chat-demo.gif)

This code is a result of following a quite heavy tutorial from [async_std](https://book.async.rs/tutorial/index.html).
It is a chat server built with async_std.

# Usage

* `cargo run` for running a server on localhost:8080
* `cargo run --bin client` for running a client to connect a server on localhost:8080
(The client could be anything. You could also use `netcat` for this)

## To chat
After successfully setup the client and server. Enter your name and press enter.
input the recipient's name follow by : and then follow by a message.
For example, `John: Hey John how are you!`
