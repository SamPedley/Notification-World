# Notification World

Basically your classic "Hello World" app with a little extra.

## What's the point

The goal is to play with creating a highly available, scaleable, real time app.

### Setup to Use:
* [Kubernetes](https://kubernetes.io/)
* [Kafka](https://kafka.apache.org/)
* [WebSockets](https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API)
* [Rx.js](http://reactivex.io/rxjs/)

## Workflow

The app supports two workflows, a basic User and an Admin.

### A User can:
* Belong to groups.
* View notifications in real time.
* Ignore or acknowledge notifications.
* Respond to sender of notification with short message.

### An Admin can:
* Send notifications to Users.
* View users interactions with those notifications in real time, such as:
  * If the notification has appeared in the users viewport.
  * See if the user has chose to ignore or acknowledge the notification.
  * See if the user has responded with a message.
