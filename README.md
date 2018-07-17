# Project 1 - Tipster

Tipsteris a tip calculator application for iOS.

Submitted by: Ginger Dudley

Time spent: 5.5 hours spent in total

## User Stories

The following **required** functionality is complete:

* [X ] User can enter a bill amount, choose a tip percentage, and see the tip and total values.

The following **optional** features are implemented:
* [~X ] Settings page to change the default tip percentage.
* [X ] UI animations
* [ ] Remembering the bill amount across app restarts (if <10mins)
* [ ] Using locale-specific currency and currency thousands separators.
* [ ] Making sure the keyboard is always visible and the bill amount is always the first responder. This way the user doesn't have to tap anywhere to use this app. Just launch the app and start typing.

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://i.imgur.com/wGp3jPE.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

https://imgur.com/a/egDmAsN

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Describe any challenges encountered while building the app.

## Credits

List an 3rd party libraries, icons, graphics, or other assets you used in your app.

- [AFNetworking](https://github.com/AFNetworking/AFNetworking) - networking task library

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


Locality
App Description
-Locality is a location and photo centric travel app to help users conveniently find what attractions are around them. This app will let users sort though different categories of attractions around them, and then will populate a map with pin points of these attractions. The user can then click on these pin points and see a grid of images from this sight.

User Stories
Locality:

Required User Stories:

Login Page:

User can login to their account or create a new account using Parse
Error messages if the user has not entered both an email/ password
Sign-up/ login buttons segue to explore page
Incorporate parse to track users and favorites
OPTIONAL: Add profile photo optionally or set default photo
OPTIONAL: “Guest” flow optional
OPTIONAL: slideshow of instagrams top photos

Explore Map Page:

Display Map view (Apple Map API)
Get user location permissions
OPTIONAL: prompt to enable in Settings if they declined it
Center map view on current location
Display pins based on popular locations pulled from Four Square API
Have pins show different colors based on the category the attraction is in (based on Yelp API)
OPTIONAL: Search bar to change user location (Apple Map API, or location api)
Create a tap gesture segue from the pin to the collection view
OPTIONAL: Tap on pin shows a preview on the information
Display a tab bar to switch between profile/ explore pages
OPTIONAL: search refinement based on category
OPTIONAL: Tapping on a pin will show a text bubble if other people the user knows have visited that place

Photo Collection View Page:

(i.e. display the photos of the attraction that the user tapped on in the previous page)

Display photos from the place in a collection view
Incorporate the Flickr and Fource API to access the photos of the location
Have a details navigation button to segue to details page
OPTIONAL: Think/implement of better UX to segue to details page

Details View Page:

Display main photo from the collection (maybe Yelp’s first photo)
Display attraction’s name, distance, rating, phone number
Display a favorite button that the user can click to add the place to their profile
OPTIONAL: add sound to labels so user can see pronunciation
OPTIONAL: Come up with a gesture for localization/accessibility
OPTIONAL: Comments/Rating section where people can rate comment

Profile Page

Display in either a collection or table view a list of the user’s favorited places
Label for username
OPTIONAL: add headers to the view- maybe sorted by alphabet or by category
OPTIONAL: Add Profile Picture
OPTIONAL: Add a map of their own favorited places in profile page

Optionals:

Users can view other user profiles
Users can see other users’ favorites and comments
Users can friend other users

Considerations:
What is your product pitch?

-Problem Statement: Finding things to do nearby is a hassle, involving google searches and reading through reviews, etc

-Our solution: We want to build a hyper-local and visual experience for discovering nearby attractions and things to keep busy.

Who are our key stakeholders? Who will be using this app?

-Hip people under 30/ travelers ot new places

What mobile features will we leverage in our app?

Maps/Current location
Camera (for optional profile picture)
Text to speech (for optional accessibility)
