# Plant App
A react native app for android and iOS to browse plants and related products for your garden. Distribution with expo. 
Code originally written by [dribbble2react](https://github.com/react-ui-kit/dribbble2react). This is my implementation of same design.

Original screen designs : [Dribble](https://dribbble.com/shots/4569970-Plant-Freebie-2-Dribbble-Invites)

![](https://github.com/shubhamgupta2901/plant-app-react-native/blob/master/screenshot.png)

### Planned improvements on original app:
  1. All dimensions in React Native are unitless, and represent density-independent pixels. Setting dimensions this way is common for *components that should always render at exactly the same size, regardless of screen dimensions*. Due to this, the application **does not scale well on Tablets and different size devices**. Will be looking to solve that issue.  Will also need to use **dynamic font sizes** (rem?).
  2. The implementation is iOS-first and hence there are certain **issues when running the app on android devices** (elevations etc). Need to fix that.
  3. Browse Screen uses a very ineffcient way to implement tabs, and only shows list of categories in all three tabs. Would be replacing the tabs with react-native's **tab-view and navigation**. Will be showing **categories, articles and galleries** in the three tabs.
  4. Explore Screen's images rendering is hardcoded. Will be replacing with a **Pinterest-like Staggered Gridview** for dynamic image sizes.
  5. Will be working on implementing and **dark mode** of application.
  6. Will allow users to **save/bookmark articles and galleries**.
