This serves as a guide on how to set up the infrastructure necessary to run an instance of bluesky on a server & set up a local dev environment to develop the app.

## Frontend Overview 

The Bluesky app is written in [React Native](https://reactnative.dev/) and is powered by the [Expo](https://expo.dev/) framework.

See [[Frontend|this guide]] for the full summary about the Bluesky frontend.

Official Bluesky client-side API is written in TypeScript and is [available here](https://github.com/bluesky-social/atproto/tree/main/packages/api).

## Protocol Overview

Bluesky is built on the [AT Protocol](https://atproto.com/guides/overview). What that means in simple terms is that instead of a simple REST API combined with an SQL database, it's using a brand new & much more complex system to manage user information and communication between servers.

See [[Protocol|this guide]] for the full summary about the AT Protocol.

## Backend Overview 

The backend is written in [Go](https://go.dev/) along with a portion written in [TypeScript](https://www.typescriptlang.org/).

#### Palomar
Repo: [GitHub](https://github.com/bluesky-social/indigo/tree/main/cmd/palomar) 
Lang: Go

Palomar is an Elasticsearch/OpenSearch frontend and ATP (AT Protocol) repository crawler designed to provide search services for the Bluesky network.

#### BGS (Big Graph Server)
Repo: [GitHub](https://github.com/bluesky-social/indigo/blob/main/cmd/bigsky)
Lang: Go

Description goes here

#### PDS (Personal Data Server)
Repo: [Github](https://github.com/bluesky-social/atproto/tree/main/packages/pds)
Lang: TypeScript

description goes here

