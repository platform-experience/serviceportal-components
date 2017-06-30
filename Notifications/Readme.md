# Notifications

## Description

Notifications are used to tell the user when an event has occurred.

A notification can be used to let a user know that changes they made were saved. There are two ways for notifications to be dismissed - by clicking the X or through auto-dismissal.


There are typically four types of notifications, and they are distinguished by color.

<p><br/><br/><br/><br/></p>

## Informational
---
Inform users about neutral events (blue).

![alt text](../images/notification-info.png "Notification Info")

```HTML
<div class="notification notification-info">You have 5 new messages<button class="btn-icon close icon-cross"></button></div>
```

<p><br/><br/><br/><br/></p>

## Positive
---
Inform users about success events (green).

![alt text](../images/notification-success.png "Notification Success")

```HTML
<div class="notification notification-success">Your report has been saved.<button class="btn-icon close icon-cross"></button></div>
```

<p><br/><br/><br/><br/></p>

## Warning 
---
Inform users about potentially negative events (yellow).

![alt text](../images/notification-warning.png "Notification Warning")

```HTML
<div class="notification notification-warning">The application is now read-only mode<button class="btn-icon close icon-cross"></button></div>
```

<p><br/><br/><br/><br/></p>

## Error
---
Inform users about failure events (red).

![alt text](../images/notification-error.png "Notification Error")

```HTML
<div class="notification notification-error">The file couldn't be uploaded, because its size is over 10MB<button class="btn-icon close icon-cross"></button></div>
```

**Note** Notification colors have been standardized and should not be changed.

<p><br/><br/><br/><br/><br/></p>
