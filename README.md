# Project 1 - *SimpleToDo App*

**SimpleToDo** is an android app that allows building a simple todo list and basic todo items management functionality including adding new items and deleting an existing item.

Submitted by: **Angelina Le**

Time spent: **12** hours spent in total

## User Stories

The following **required** functionality is completed:

* [x] User can **view a list of todo items**
* [x] User can **successfully add and remove items** from the todo list
* [x] User's **list of items persisted** upon modification and and retrieved properly on app restart

The following **optional** features are implemented:

* [ ] User can **tap a todo item in the list and bring up an edit screen for the todo item** and then have any changes to the text reflected in the todo list

The following **additional** features are implemented:

* [x] Add a clear button to remove all of the tasks instead of long clicking each item to remove.
* [x] Adjust the UI

## Video Walkthrough

Here's a walkthrough of implemented user stories:

![Simple TODO app walkthrough](https://user-images.githubusercontent.com/72471050/146596673-ef53c30a-26c0-4bb0-9660-e9d4e6b0a9e5.gif)

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Describe any challenges encountered while building the app:

- I was struggling setting up the Android Studio app as well as all of the pre-requisite setup that is necessary to complete this prework.
- I didn't have any prior experience with Kotlin and XML so I had a hard time trying to implement additional features (i.e tap a todo item in the list and bring up an edit screen for the todo item)
- When I add the clear button, it messes up all of my UI due to the lack of constraints. However, after looking at the code for a bit longer, I realized that I forgot to include the Top/ Bottom/ Start/ End constraints for all of my components in the app (including my clear button). Thus, I added the constraints for all of the components and the UI looks like what I envision it to be.
- I also spent quite a bit of time trying to figure out how to emulate the app in my Android phone using a USB cable. But I finally learned how to do it and I am very excited!

## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
