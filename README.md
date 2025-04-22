# Prework - *iOS101.Prework*

Submitted by: Nathan Bui

iOS101.Prework is an iOS app that introduces basic user interface elements in Xcode and demonstrates how to link user actions/button taps to functional behavior (changing the background color). The app displays three labels and a button. When the button is tapped, the background color changes to a randomly generated color.

Time spent: 1 hour

## Required Features

The following **required** functionality is completed:

- [ ] Users see a screen with three labels and a button ✅
- [ ] Tapping the button changes the screen color to a random color ✅

## Some ideas to improve the app:
- Text Color Randomizer: In addition to changing the background, randomly change the color of the label text when the button is tapped.

- Font Switcher: Add a button or toggle to switch between different font styles (such as: bold, italic, cursive) for the labels.

- Color Visibility: When the text is at a fixed color, it becomes hard to see depending on the color change. (Light color font on a light color makes the text hard to see). Change so that the text color changes based on the shade of the color that it is changed to.

- Button Vibration Feedback: Make the phone vibrate lightly when the button is tapped.


## Video Walkthrough
<div>
    <a href="https://www.loom.com/share/81447dac0b324351b471c4b175d44883">
      <p> iOS 101 - Pre-Work Submission </p>
    </a>
    <a href="https://www.loom.com/share/81447dac0b324351b471c4b175d44883">
      <img style="max-width:300px;" src="https://cdn.loom.com/sessions/thumbnails/81447dac0b324351b471c4b175d44883-f0369dec24d1ff08-full-play.gif">
    </a>
  </div>

## App Brainstorming - Favortie App(s)
While building the app, I relied on my memory of using Storyboard from past experiences. I used that knowledge to quickly set up the layout, place the UI elements correctly, and navigate the interface efficiently.


Favorite Apps & its Features:

1. Pinterest
- Ability to visually plan out goals and inspiration

- Easy-to-use interface for saving and organizing ideas into separate groups

- Infinite pictures/posts with personalized recommendations

2. Notion

- Drag-and-drop customization

- Embedding multimedia (videos, links, images) in one of your pages

- Cross-device syncing for easy workflow

3. Instagram

- Visually immersive to chat with friends/family

- Easy saving of posts to collections

- Explore page that recommends content based on interests

4. TikTok

- An algorithm that understands me! Surfaces relevant content quickly

- Simple video editing and effects for content creation

- It makes it fun to share videos with friends/family; when shared for a long time, you can build a streak based on sending videos.

5. Spotify

- Personalizing playlists and music discovery

- Smooth transitions between different devices (phone, desktop, smart speakers)

- Creating/joining a Spotify Jam, you can join your friends " Spotify Jam" and queue music from your account/device.

- See what your friends are listening to and get to listen to their personalized playlist
  

## App-Idea

I want to create an app inspired by Pinterest that helps users visually plan and organize their personal bucket list goals. Whether it's travel destinations, fitness achievements, creative projects, or life milestones, users can "pin" images, quotes, or links that represent each goal. The app will also allow users to add notes, track their mood, and create savings plans for money-related goals.

What I envision is a user experience that focuses on a clean, minimal design with drag-and-drop functionality to make organizing goals intuitive and inspiring. As someone with a long list of personal bucket list items, I’ve found it hard to keep everything in one place, especially as a visual learner. This app aims to help people like me stay motivated and inspired while turning dreams into actionable plans!

## Notes

One challenge I ran into was connecting the color-changing logic to the button’s IBAction. Initially, the background color wouldn’t change when the button was tapped. After some trial and error, I created a new function called changeBackgroundColorTapped and connected it to the button’s action. Once I did that and called let randomColor = changeColor() followed by view.backgroundColor = randomColor, everything worked as expected.

## License

    Copyright 2025 Nathan Bui

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
