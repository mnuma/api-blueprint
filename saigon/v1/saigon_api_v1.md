# Message of the Day API
A simple [MOTD](http://en.wikipedia.org/wiki/Motd_(Unix)) API.

# Message [/messages/{id}]
This resource represents one particular message identified by its *id*.

## Retrieve Message [GET]
Retrieve a message by its *id*.

+ Response 200 (text/plain)

        Hello World2

## Retrieve Message [POST]
Retrieve a message by its *id*.

+ Response 200 (text/plain)

        Hello World!

## Delete Message [DELETE]
Delete a message. **Warning:** This action **permanently** removes the message from the database.

+ Response 204
