# BlogScroll: Dynamic Tumblr Feed Viewer

## Introduction

**Name of your app** is an app that dynamically fetches and displays a feed of Tumblr blog posts, presenting them in a user-friendly, scrollable table view. By leveraging the Tumblr API, the app showcases the latest posts, including images and summaries, from selected Tumblr blogs. Users can explore a variety of content seamlessly within the app, with each post tailored to offer a quick glance or a deeper dive into the blog's offerings. Through custom table view cells, the app enhances visual engagement by incorporating blog post images alongside concise summaries, creating an interactive and engaging user experience. Additionally, BlogScroll integrates features such as pull-to-refresh, enabling users to easily update their feed with the latest posts. This app serves as an accessible gateway for users to discover and enjoy content from their favorite Tumblr blogs directly on their iOS devices.


## Features

The following features are implemented:

- [x] App has a configured table view and table view call
- [x] App populates the table view with data fetched from an API
- [x] App fetches posts from a different Tumblr blog
- [x] App has a refresh control to update the table view
- [x] Changed the display name of the app

## Getting Started

To dive into the world of Tumblr with BlogScroll:
1. Clone the repository to your local machine.
2. Open the `ios101-project5-tumblr.xcodeproj` file with Xcode.
3. Build and run the project on your iOS device or emulator.

## Video Walkthrough

<div>
    <a href="https://www.loom.com/share/02a1d3962b0d45caa81f6b4cf7a59292">
      <p>Humans of NewYork</p>
    </a>
    <a href="https://www.loom.com/share/02a1d3962b0d45caa81f6b4cf7a59292">
      <img style="max-width:300px;" src="https://cdn.loom.com/sessions/thumbnails/02a1d3962b0d45caa81f6b4cf7a59292-with-play.gif">
    </a>
  </div>

<div>
    <a href="https://www.loom.com/share/c36ca02ddd6942cfb778ee92150c776e">
      <p>Humans of Seoul</p>
    </a>
    <a href="https://www.loom.com/share/c36ca02ddd6942cfb778ee92150c776e">
      <img style="max-width:300px;" src="https://cdn.loom.com/sessions/thumbnails/c36ca02ddd6942cfb778ee92150c776e-with-play.gif">
    </a>
  </div>

## Notes

Designing custom table view cells to display blog posts attractively and learning to load images asynchronously with the Nuke library were key hurdles to maintaining smooth scrolling performance. Additionally, implementing the pull-to-refresh feature to update the feed seamlessly involved understanding and applying the UIRefreshControl in a way that meshed well with the app's data fetching logic. These challenges were tackled through persistent experimentation and leveraging the rich features of Swift and iOS development tools.

## License

    Copyright [2024] [Pragnavi Ravuluri Sai Durga]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
