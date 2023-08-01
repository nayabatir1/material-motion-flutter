# Introduction

<strong>Material Design</strong> is a system for building bold and beautiful digital products. By uniting style, branding, interaction, and motion under a consistent set of principles and components, product teams can realize their greatest design potential.

Material Components (MDC) help developers implement Material Design. Created by a team of engineers and UX designers at Google, MDC features dozens of beautiful and functional UI components and is available for Android, iOS, web and Flutter.material.io/develop

## What is Material's motion system for Flutter?

The Material motion system for Flutter is a set of transition patterns within the animations package that can help users understand and navigate an app, as described in the Material Design guidelines.

#### The four main Material transition patterns are as follows:

- <strong>Container Transform</strong>: transitions between UI elements that include a container; creates a visible connection between two distinct UI elements by seamlessly transforming one element into another. ![alt text](https://codelabs.developers.google.com/static/codelabs/material-motion-flutter/img/11807bdf36c66657.gif)
- <strong>Shared Axis</strong>: transitions between UI elements that have a spatial or navigational relationship; uses a shared transformation on the x, y, or z axis to reinforce the relationship between elements. ![alt text](https://codelabs.developers.google.com/static/codelabs/material-motion-flutter/img/71218f390abae07e.gif)
- <strong>Fade Through</strong>: transitions between UI elements that do not have a strong relationship to each other; uses a sequential fade out and fade in, with a scale of the incoming element. <br>![alt text](https://codelabs.developers.google.com/static/codelabs/material-motion-flutter/img/385ba37b8da68969.gif)
- <strong>Fade</strong>: used for UI elements that enter or exit within the bounds of the screen. ![alt text](https://codelabs.developers.google.com/static/codelabs/material-motion-flutter/img/cfc40fd6e27753b6.gif)

The animations package offers transition widgets for these patterns, built on top of both the [Flutter animations library](https://api.flutter.dev/flutter/animation/animation-library.html) (flutter/animation.dart) and the [Flutter material library](https://api.flutter.dev/flutter/material/material-library.html) (flutter/material.dart):

In this codelab you will be using the Material transitions built on top of the Flutter framework and Material library, meaning you will be dealing with widgets. :)

## What you'll build

This codelab will guide you through building some transitions into an example Flutter email app called Reply, using Dart, to demonstrate how you can use transitions from the animations package to customize the look and feel of your app.

The starter code for the Reply app will be provided, and you will incorporate the following Material transitions into the app, which can be seen in the completed codelab's GIF below:

- <strong>Container Transform</strong> transition from email list to email detail page
- <strong>Container Transform</strong> transition from FAB to compose email page
- <strong>Shared Z-Axis</strong> transition from search icon to search view page
- <strong>Fade Through</strong> transition between disappearing mailbox title
- <strong>Fade Through</strong> transition between compose and reply FAB
- <strong>Fade Through</strong> transition between mailbox pages
- <strong>Fade Through</strong> transition between bottom app bar actions

![alt text](https://codelabs.developers.google.com/static/codelabs/material-motion-flutter/img/b26fe84fed12d17d.gif)

In this codelab you'll use transitions provided by the animations package. For further exploration into Material Flutter theming and component systems, check out the other Material Design codelabs.

What you'll need
Basic knowledge of Flutter development and Dart
A code editor
An Android/iOS emulator or device
The sample code (see next step)
