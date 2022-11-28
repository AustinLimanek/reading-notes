# Class 26

[Journal Home](README.md)

Current Readings:

[Android Fundamentals](https://developer.android.com/guide/components/fundamentals)

## Reading Notes

### Android Fundamentals

Each application runs on it's own Linux process unless explicitly stated otherwise. In addition, each application is run on it's own VM (virtual machine) that allows for an application to run safely on a device without letting it access other applications or memory units in the device.

**Activities** are subclasses of the `Activity` class. These activities are used to allow for the user to accomplish some single goal, maintain state of the other activities that are stopped, and, finally, the ability to kill an activity once the user wants to end the experience.

**Services** typically run in the background of a device. The typical example is playing music while one looks at other applications more directly. There are started and bounded services. Bound services run when called by another application that is being used. In particular, if a user is using a service or application that uses another service or application as an API then the API or bound service is marked as important. Services are also a subclass of `Service`.

**Broadcast Receiver** is a way for applications to get further information about the user to allow more interactive engagement. For example, the system can send information to an application that is currently closed that it is a certain time, or that there is a given status on the battery, and the app will be able to send a notification to the user. This allows for applications to be shutdown but still receive stimuli from the environment. In addition, `BroadcastReceiver` is the class and `Intent` is the object.

**Content Provider** acts as a database and a security protocol for information sharing between parallel applications on a device. The `ContentProvider` is the class that is used.

Android works in a way that allows for application components to be accessed from other applications without the first application having access to the full second application. However, the Android system is actually accessing the rest of the application.

## Questions

1. What is an Intent in Android Studios? Give some fresh examples of when you might use it.

    When a weather application identifies a GPS location the weather app sends an Intent to Google Maps or something similar to get information about the user's location.

2. Describe an Activity in your own words.

    An application caries out a calculation or accomplishes a task for the user depending on some type of user input or pre-programmed trigger.

## Things I want to know more about

I would like to learn more about applications on ios. Is there a similar architecture in how information and permissions are laid out for an application?

&copy; 2022, NoMichi
