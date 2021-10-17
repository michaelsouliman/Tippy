# Tip Calculator 

## Michael Souliman

**Tippy** computes the tip and total amount for a bill. The app uses the base amount and tip percentage to calculate the amount owed, and it also describes the quality of service based on the tip.

Time spent: **2** hours spent in total

## Functionality 

The following **required** functionality is completed:

* [ ] User can enter in a bill amount (total amount to tip on)
* [ ] User can enter a tip percentage (what % the user wants to tip).
* [ ] The tip and total amount are updated immediately when any of the inputs changes.
* [ ] The user sees a label or color update based on the tip amount. 

The following **extensions** are implemented:

* [ ] User can split the bill across multiple people and it will display the cost per person

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='http://i.imgur.com/link/to/your/gif/file.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

I did not encounter any challenges when going through the walkthrough or the extension I implemented, but
I did have difficulty trying to upload this project through GitHub. One challenge that I did encounter
was the app continuing to crash as I tried to implement my extension but using the log statements, I was able
to figure out the error and that it was not checking again if etBaseAmount was empty when I changed the
number of people the bill was split across.

## License

    Copyright [2021] [Michael Souliman]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
