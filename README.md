# filo-chat-wellknown

Serves one file, `/.well-known/matrix/client`, for the name `chat.filoliving.it`, so that Matrix apps that scan a sign-in QR code can find the chat. The chat itself is reachable only on the private tailnet.

Undo: delete the DNS record `chat` for filoliving.it and this repository.
