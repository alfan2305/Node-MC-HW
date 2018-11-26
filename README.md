# Homework Assignment #1

## Create a simple "Hello World" API. Meaning:

1. It should be a RESTful JSON API that listens on a port of your choice.

2. When someone posts anything to the route /hello, you should return a welcome message, in JSON format. This message can be anything you want.

## Solution

Solution consist 'Not Found Handler' on every other path different than `/hello`
On `/hello` it return greeting in english.

You can add lang query param to get different language greetings (ex. `/hello?lang=id`) and name query param to add name to display name (ex. `/hello?name=Alfan`)

Available languages parameter:
p en -> English
p id -> Indonesia