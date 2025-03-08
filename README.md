# Welcome to Ditto University! 🚀

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



## The Scenario

You've just joined a development team for the company Acmezon that recently demonstrated a task management app to company leadership. The app demo was a hit - the UI was polished, the interactions were smooth, and leadership was ready to ship it immediately. There was just one catch: the entire app was running on mock data.

The prototype lacks several critical features modern users expect:
- No offline support - data disappears when the app closes
- No data persistence - changes aren't saved between sessions
- No synchronization - changes don't sync between devices
- No real-time updates - users don't see each other's changes

Rather than rebuilding from scratch, the team has decided to integrate Ditto to add these essential features. Your mission is to transform this prototype into a production-ready application with robust offline-first capabilities and peer-to-peer synchronization, all while maintaining the existing user experience.

## Learning Objectives

Through this module, you'll learn how to:
1. Replace mock data with a real Ditto database
2. Implement offline-first data persistence
3. Enable real-time updates across devices


## Ready to Begin?

Head to [Lesson 1 - Your First Ditto App](lesson-1/README.md) to get started! 🚀


