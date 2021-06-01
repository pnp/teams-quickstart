# teams-quickstart

Welcome to the Microsoft 365 PnP Teams Quickstart! A new and faster way to build Microsoft Teams Apps.

## What is this?

This is a ready to run Github Codespace with all the tools you need to build Microsoft Teams Apps.

## Ready to roll?

Just follow these easy steps and you will have your Microsoft Teams app up and running within minutes...

> NOTE: In order to follow these instructions you need to be part of the [Github Codespaces](https://github.com/features/codespaces) beta. It's just awesome!

1. Click on the green *Code* button and choose *Open with Codespaces*, then choose *+ New Codespace*
2. Wait for the Codespace to be provisioned
3. Once you have the Visual Studio Code experience in your browser, go to the Terminal window and create a new folder (`mkdir my-demo`) and then change to that new folder (`cd my-demo´)
4. Type `yo teams` to start the scaffolding of your project
5. Answer all the questions - for this demo, you can just accept the default values
6. Once the generator has asked all the questions and installed all dependencies you can start the application
7. Type `gulp codespace-serve --publish`
8. You will be asked to sign in to your Microsoft Teams tenant. Preferably sign in to your developer tenant
9. When the application is running you will get a notificationIn that your application is running on port 3007. Click on *See all forwarded ports* and then right-click on *Public (3007)* and choose *Make Public*
10. All is now set, go to the Teams tenant where you signed in and the application will be published and ready for you to use
11. If you created a Tab, all default options when running the generator, you can just go to a Team, add a new Tab and choose the Tab you just created. (You might have to click on *Apps* and then reload your Teams application for the application to appear, due to caching.)