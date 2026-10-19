# mail-link

A one-file static page that turns an https link into an Apple Mail `message://` link, for chat apps that only open http/https links.

Usage: `https://cj.github.io/mail-link/#<percent-encoded Message-ID>`

Example: `https://cj.github.io/mail-link/#%3Cabc123%40example.com%3E` opens `message://%3Cabc123%40example.com%3E`.

The Message-ID is in the URL fragment, so it is never sent to the server. No external scripts, no analytics.
