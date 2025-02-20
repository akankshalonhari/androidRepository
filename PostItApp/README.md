# Pre-work - PostIt App

PostIt is an android app that allows building a todo list and basic todo items management functionality including adding new items, editing and deleting an existing item.

Submitted by: Akanksha Lonhari

Time spent: 10 hours spent in total

## User Stories

The following **required** functionality is completed:

[*] User can **successfully add and remove items** from the todo list
[*] User can **tap a todo item in the list and bring up an edit screen for the todo item** and then have any changes to the text reflected in the todo list.
[*] User can **persist todo items** and retrieve them properly on app restart

The following **optional** features are implemented:

[*] Persist the todo items [into SQLite](http://guides.codepath.com/android/Persisting-Data-to-the-Device#sqlite) instead of a text file
* [ ] Improve style of the todo items in the list [using a custom adapter](http://guides.codepath.com/android/Using-an-ArrayAdapter-with-ListView)
* [ ] Add support for completion due dates for todo items (and display within listview item)
* [ ] Use a [DialogFragment](http://guides.codepath.com/android/Using-DialogFragment) instead of new Activity for editing items
* [ ] Add support for selecting the priority of each todo item (and display in listview item)
[*] Tweak the style improving the UI / UX, play with colors, images or backgrounds

The following **additional** features are implemented:

* [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

File name 1: FinalVideo_CodepathApp_AkankshaL.mov
Location 1: Included on GitHub repository
(Video file created on QuickTime player with .mov file extension)

File name 2: FinalVideo_CodepathApp_AkankshaL_2.mov
Location 2: Included on GitHub repository
(Video file created on QuickTime player with .mov file extension)

## Notes

The notes were very through and descriptive and did not have any trouble following them.
I did try implementing the custom Adapter and the UI/UX optional features, but had some issues executing them without errors.
Error with Custom Adapter : Was not able to link the standard android layout style for ListView in the custom adapter inflate call.

For UI/UX I successfully completed :
 1. Adding background image
 2. Changed UI layout relative to the background image
 3. Added styles for list rows for 'pressed' and 'select' states of rows
 4. Added list style selector according to current style of list rows
 5. Added border around a text-label
 6. Added gradient effect to buttons

## License

    Copyright [2017] [Akanksha Lonhari]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.