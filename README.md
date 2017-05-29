# messenger

Messenger follows a few basic concepts.

It receives (whether by database query or api) messages to be sent at a specific time. It then sends those messages and marks them as sent.

Import Factors:
1. Sends messages at specific times.
2. Sends messages by specific means (slack, text, email, mobile notification, desktop notification etc)
3. Can determine whether or not the message was read - See if email was read, phone was checked, or slack message was marked as read.
