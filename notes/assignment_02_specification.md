## Assignment 2 - Echo, World!

In this assignment we want to extend the WebSocket app to Echo what we type in a text field into a composable Text element that fills most of the screen. You will send data to the echo server when you push the Button.

The App Design - feel free to rearrange this design, but you get the idea...

![The App Design](resources/assignment_02_design.png)

A Column layout seems appropriate to me with Text Field, Text, and Button elements.

The official Jetpack Compose page has an [article on User Input](https://developer.android.com/jetpack/compose/text/user-input) you should read.

### The WebSocket Echo Server

You have the web socket echo server code in the [GitHub repository for Lecture 2](https://github.com/palmerc/PGR208_Lecture02).

Under `scripts/wsecho` there is a python script that will serve as your Echo server and the README gives you a 'how-to' on getting it to run. I've add a bit of diagnostic output to help you identify your IP address and you should see incoming messages displayed on the console.

### Submission

Clean your project and Zip it and upload to Canvas. Alternatively, upload it to Github and send the link to the Canvas assignment. Also use the Screenshot app or similar to take a movie of your app in action. This is either uploaded to Canvas or added to the git repository.

### Note

Don't forget to change the IP address hardcoded in the example code of the client to use the one your machine has!

![The hardcoded URL](resources/assignment_02_url.png)

The IP address can be found in your network configuration or by starting the echo server.

On a Mac

    ifconfig en0

On Windows

    ipconfig /all

