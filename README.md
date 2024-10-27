# Systems Project Ideas
This repository is for maintaining project ideas for the Systems and Security SIG.

---

## 1. Create a PostgreSQL Database Extension
- **Details**: Creating an extension for PostgreSQL can be done in C. The usefulness of the extension depends on the problem it aims to solve. For example, we could build an extension that displays the query plan of the SQL engine. Open to additional suggestions for potential functionalities.
- **References**: [List of Extensions](https://gist.github.com/joelonsql/e5aa27f8cc9bd22b8999b7de8aee9d47), [Tutorial](https://www.percona.com/blog/writing-postgresql-extensions-is-fun-c-language/), [Postgres docs for extension](https://www.postgresql.org/docs/current/sql-createextension.html).

## 2. P2P File Sharing Tool in Golang
- **Abstract** - The idea is to build a tool that allows people to share large files directly without having to load them on a third party storage service first. Although there are already a lot of such tools, we are hoping to use Golang's extensive support for concurrency to make it easier and faster to share multiple files and folders at the same time and with multiple recievers.  

- **Features**
  - Sharing files and folders directly between users
  - A clean and intuitive CLI tool for a good user experience.
  - Share files concurrency to a single or multiple recievers.
  - Ability to open up a temporary data server and allow clients to pick whichever files they want.
  - Support file compression.
  - Ability to generate one time share links (once a reciever uses the link its expired)
  - Allow users to resume pending transfers.
  - Provide E2E encryption to the users.

- **References**
  - [fs-cli](https://github.com/spectre10/fs-cli)
  - [pion/webrtc](https://github.com/pion/webrtc)
  - [gfile](https://github.com/Antonito/gfile)
