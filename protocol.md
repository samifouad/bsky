Bluesky is built on the [AT Protocol](https://atproto.com/guides/overview). What that means in simple terms is that instead of a simple REST API & SQL database powering the app, it's using a brand new system to manage user information and communication between servers.

here's a few noteworthy features of their system design:

- Most data is public
- Independently managed servers talk together to form a federation
- Users are allowed to switch between servers without losing access to their data & social connections
- Username are just URLs with at @ before them, eg. `@bob.bsky.social`
- Account verification is done through proving domain ownership instead of any central authority deciding who gets a blue checkmark, eg. `@bobscoolsite.com`
