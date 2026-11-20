# Django room chat

Join a room and exchange messages over a WebSocket connection. Django Channels routes each connection to a room group, and the application saves chat messages for later retrieval.

## Follow a message

1. Start with the [WebSocket routes](mysite/chatapp/routing.py) to see how a room is selected.
2. Read the [chat consumer](mysite/chatapp/consumers.py) for connection handling, group broadcasts and database writes.
3. Open the [room template](mysite/chatapp/templates/chatapp/room.html) for the browser side of the conversation.
