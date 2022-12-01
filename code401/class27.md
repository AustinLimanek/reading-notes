# Class 27

[Journal Home](README.md)

Current Readings:

1. [Android SharedPreferences](https://developer.android.com/training/data-storage/shared-preferences)
2. [Espresso Testing (read Overview, Basics, and Recipes, plus any others that look interesting)](https://developer.android.com/training/testing/espresso)
3. [Ridiculous superpower: the Espresso Test Recorder](https://developer.android.com/studio/test/other-testing-tools/espresso-test-recorder)
4. [Android Tasks and the Back Stack](https://developer.android.com/guide/components/activities/tasks-and-back-stack)

## Reading Notes

### Android SharedPreferences

This article gives a quick introduction of how to access information that is stored in the application. One can use a key-value pair setup to access either shared data, or data that is localized to a single action.

### Espresso Testing

This short article defines a collection of packages that are included in Espresso Testing. In addition, the article persuades the reader into implementing tests on their apps, especially with the suite that is being introduced.

### Ridiculous superpower: the Espresso Test Recorder

This article introduces the amazing tool Espresso Test Recorder that allows the user to record their actions as they navigate through the app UI. The recorder will in situ write tests that are dependent on the view of the recorder and the code that is being rendered. The user can also add additional tests when necessary or change the tests that are automatically written by the Recorder.

### Android Tasks and the Back Stack

The back stack exists for each application on the phone. When the application is open, the tasks can be stacked on that given back stack. When the back button is pressed, the stack pops the task and jumps to the task below in the initial top. When the home screen button is pressed, all call back stacks are jumped out of and are now paused. Pressing on an application button will call that call back stack to where it was previously.

If the application is opened from a notification, a virtual call back stack in constructed and allows for the user to have the ability to press back as if they navigated to that location in the application on their own.

## Things I want to know more about

I would like to know more about how the virtual back stack is constructed. Does the path need to be specified for the application, or is there a shortest path principal that is followed by default?

## Questions

1. What is a technology you’ve used before that is similar to Shared Preferences?

    This process is similar to a hash map or an object in JavaScript. In addition, it is similar to a NoSQL database in general.

2. Why is testing important? Give at least 4 reasons, and explain which is the most important to you and why.

    1. The UI should behave reliably under that same circumstances for all users. This means that the program has been tested and will allow for an enjoyable experience for the user.
    2. Catch unforeseen consequences for a given written code. If random behavior is unwanted, then this could result in bad bugs in the future when addition features are added.
    3. Continuous experience from the user. If the app crashes, the users attention will be pulled form the application.
    4. Testing allows the programmer to anticipate edge cases in the future.

3. Create an analogy for Tasks and the back stack. Have we used a similar system before? Explain.

    This is the exact method used for recursive function. There is a call stack that piles onto the call stack. Once there are no more additions, the methods begin executing their functionality by popping from the top of the call stack.

&copy; 2022, NoMichi
