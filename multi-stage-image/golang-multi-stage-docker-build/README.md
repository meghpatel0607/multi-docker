# Multi Stage Docker Build

Choosing a Golang-based application for this example is because Golang is a programming language that compiles directly to machine code, skipping the need for a runtime environment like some other languages. This makes Golang applications more straightforward and faster.

The cool part is using a multi-stage Docker build and distro-less images. This makes the final container much smaller. In simple terms, it's like packing only what's needed for your app to run, and nothing extra. This smaller size is great because it makes your app faster to deploy and takes up less space on servers. So, Golang and distro-less images together make things efficient and speedy!
