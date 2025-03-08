# Lesson 1 - Your First Ditto App 🚀

> [!NOTE] 
>This is a proof of concept for the Ditto iOS Introduction to Ditto Learning Module.  It is a simple to-do list app that uses Ditto to store and sync the task data.  This is not production ready code and is only meant to be used as a reference for the POC of Ditto University learning modules. 

## Prerequisites

You will need the following to complete this learning module:

- [Xcode](https://developer.apple.com/xcode/) 15 or greater
- Git installed on your machine 
- A Ditto Portal account with an app created (directions provided below)
- Ditto SDK installed as a package dependency using Swift Package Manager (already done for you)


### The Big Peer and Cloud Storage

The `Big Peer` is a trusted cloud deployment of Ditto's sync engine and associated services that enables advanced platform capabilities. Every Ditto Portal account includes a Big Peer instance that serves as a central hub for data storage and synchronization.

In our Tasks app, data is stored in a collection called `tasks` within the Big Peer instance. Each task is stored as a JSON document in this collection. The Ditto SDK provides a unified API for:
- Reading and writing data to the Big Peer
- Synchronizing with other devices (called `Small Peers`) running the same app
- Managing offline data persistence
- Handling real-time updates

This architecture enables seamless data synchronization between:
- Your device and the cloud (Big Peer)
- Your device and other users' devices (Small Peers)
- The cloud and all connected devices



## Table of Contents

1. [Getting Started](1.1/README.md)

2. [Setting Up Your Development Environment](1.2/README.md)

3. [Try Out The Sample Data](1.3/README.md)
   - Understanding The Data Model
   - The TaskModel Struct
   - Building and Running the iOS Application

4. [Create Your First Ditto Document](1.4/README.md)
   - Intro to DQL
   - Update the App
   - View Changes in the Portal

5. [Subscriptions and Observers](1.5/README.md)



