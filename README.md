# Table of Contents
1. [Skills](#skills)
2. [Projects : Checklist](#checklist)
3. [Projects : Chat App](#chat)
4. [Projects : String Calculator](#calculator)
5. [Project : Bar Chart - Svg](#svg)
6. [Project : D3 - Bar Chart](#d3-bar-chart)
7. [Project : DOM Control](#domcontrol)
8. [Project : Visualization - D3](#visualization)

# Skills

* Libraries
    * Redux : redux, react-redux, redux-thunk, redux-logger, remote-redux-devtools
    * Data : reselect, normalizr, lodash
    * Debugger : chrome(default), reactotron
    * UI : native-base, react-native-elements, shoutem, expo, bootstrap, react-bootstrap
    * Visualization : d3, svg, react-native-svg
    * Map : react-native-maps(airbnb)
    * Etc : react-native-firestack, react-native-router-flux
    * Reviewed
        * Redux : redux-actions, redux-saga, redux-orm, Ducks
        * Data : immutable.js, typescript
        * Visualization : react-d3
        * Etc : react-native-background-timer, react-native-navbar
        * Framework : vue.js, next.js, angularJS(1.x), ionic(1.x)
* Focus
    * codes with vanilla JS and vanilla RN
    * Redux : separate Smart component, presentational component
    * Flatten objects : able to convert and restore
    * Reduce computation with memoize pattern
    * CSS : CSS3, sass
    * Browser Optimization(iOS, Android) : Chrome, Safari, Firefox, WebView(Google, FB, KakaoTalk, RN), etc.
    * Custom Components used : Custom elements, React.js, RN
* Design Pattern
    * Self defining function
    * call back pattern
    * module pattern
    * delegation pattern
    * proxy pattern
    * curring pattern
* Data Structure
    * convert to flatten objects and able to restore
    * make able to undo
* Redux
    * Multi reducers with combine reducer
    * Compose and Middleware : redux-thunk, redux-logger
    * BindActionCreators
    * Normalizing state shape
    * Updating normalized data
* React Native
    * Reusable Components : presentational component
    * Understanding on LifeCycle
    * Code without jsx
    * UI design with Flexbox
    * setState with updater function
    * controlled components
    * Reviews : Higher-Order Components
* JavaScript
    * ES6
        * Spread operator, Rest params
        * Destructuring
        * Promise
        * arrow function
        * tail call
        * Template literals
        * Dynamic key of object
    * ES7
        * Object spread
        * Async functions
    * Etc
        * shallow copy, deep copy, shallow merge
* Firebase
    * database
    * authentication
* IDE
    * Atom(nuclide), Expo XDE
* Github
    * Create a repo, Fork a repo, branch merge
* Etc
    * codewars : https://www.codewars.com/users/royj/

* * *    

# Checklist

* [Git(vanilla RN)](https://github.com/royjkim/React_Native-CheckLists)

* ~~[Open App on Expo](https://expo.io/@roykim/checklist-expo)~~

* ▼ Captures : App on iPhone

![Checklist App on iPhone - 1/3](https://github.com/royjkim/Skills/blob/master/Checklist_Expo_1.gif)

* Summary
    * made with React Native, Redux
    * Focus
        * coded with vanilla RN
        * Redux : separate Smart component, presentational component
        * Flatten objects : able to convert and restore
        * Reduce computation with memoize pattern.
* Libraries
    * Redux : redux, react-redux, redux-thunk, redux-logger, remote-redux-devtools
    * Data : reselect, normalizr, lodash
    * Debugger : chrome(default)
    * UI : react-native-elements
* Data Structure
    * convert to flatten objects and able to restore.
    * immutable data on needed state.
    * shallow copy, deep copy, shallow merge.    
* On Expo
    * differences
        * speed
        * UI : navigation position
* JavaScript(used skills, summary)
    * ES6
        * Spread operator, Rest params
        * Destructuring
        * Promise
        * arrow function
        * tail call
        * Template literals
        * Dynamic key of object
    * ES7
        * Object spread
        * Async functions
    * Etc
        * shallow copy
        * deep copy
        * shallow merge
* Redux(used skills, summary)
    * Multi reducers with combine reducer
    * Compose and Middleware : redux-thunk, redux-logger
    * Normalizing state shape
    * Updating normalized data
    * Transfer data with navigator and redux
* React Native(used skills, summary)
    * key points
        * Reusable Components : presentational component
        * Understanding on LifeCycle
        * Code without jsx
        * UI design with Flexbox
        * setState with updater function
        * controlled components
    * Navigate
        * Navigate with vanilla RN.
        * Prevent navigate when editing
            * including tab navigate.
        * Separate Each navigate by Tabs.
        * Double tap to navigate first page of each tab.
    * UI
        * with react-native-elements
        * Modal toggle customized.
        * Modal toggle area customized.
    * Etc
        * Multi Edit
            * Able to edit same data on different tab.
            * After deleted, page would be unmounted.
* Design Pattern(used skills, summary)
    * Self defining function.
    * call back pattern
    * module pattern
    * delegation pattern
    * proxy pattern
    * curring pattern
    * encapsulation


* * *

# Chat

* [Git(vanilla RN)](https://github.com/royjkim/React-Native_ChatDemoFirebase)

* ~~[Open App on Expo](https://expo.io/@roykim/chatdemo-expo)~~

* ▼ Captures : Chat App on iPhone

![Chat App on iPhone](https://github.com/royjkim/Skills/blob/master/Chat_Expo_1.gif)

* Summary
    * made with React Native, Redux, Firebase
    * Focus
        * coded with vanilla RN
        * Redux : separate Smart component, presentational component
        * use unique key made by Firebase as own unique key.
        * disable shallow render to realtime update
* Libraries
    * Redux : redux, react-redux, redux-thunk, redux-logger, remote-redux-devtools
    * Data : load from Firebase
    * Debugger : chrome(default), remote-redux-devtools
    * UI : shoutem
* Data Structure
    * each unique id is assigned from firebase’s unique key.
    * shallow copy, shallow merge.
* Firebase
    * for better fast loading use batch loading at initial loading. and realtime update at other case.
* On Expo
    * differences
        * speed
        * UI
            * use 'Expo loading’ instead of ‘ActivityIndicator’.
            * user custom Fonts of Expo
        * Debugger
            * remote-redux-devtools
* JavaScript(used skills, summary)
    * ES6
        * Spread operator, Rest params
        * Destructuring
        * Promise
        * arrow function
        * tail call
        * Template literals
        * Dynamic key of object
    * ES7
        * Object spread
    * Etc
        * shallow copy
        * shallow merge
* Redux(used skills, summary)
    * Compose and Middleware : redux-thunk
    * Not Shallow render(react-redux)
* React Native(used skills, summary)
    * key points
        * Calculate View size depends on devices
        * Event listener
        * Keyboard
        * KeyboardAvodingView
        * Make own similar to KeyboardAvodingView.
        * According to Keyboard status(show, hide), scroll to last position at chat and user list.
        * Understanding on LifeCycle
        * UI design with Flexbox
        * minimize the use of setState and controlled components to speed up
    * Navigate
        * Navigate with vanilla RN.
        * Prevent swipe back.
        * Transfer data with navigator and redux.
    * UI
        * with react-native-elements
        * Modal toggle customized.
        * Modal toggle area customized.
* Design Pattern(used skills, summary)
    * Self defining function.
    * call back pattern
    * module pattern
    * delegation pattern
    * proxy pattern
    * curring pattern
    * encapsulation pattern

* * *    

# Calculator

 * [Git(vanilla RN)](https://github.com/royjkim/React-Native_Calculate_String)

 * ~~[Open App on Expo](https://expo.io/@roykim/calculate-react-native-expo-2)~~

 * ▼ Captures : Calculator on Web

![Captures : Calculator on Web](https://github.com/royjkim/Skills/blob/master/Calculator_Web.gif)

 * ▼ Captures : App on iPhone

![Calculator App on iPhone](https://github.com/royjkim/Skills/blob/master/Calculator_Expo.gif)

 * Summary
     * made with reactJS with create-react-app
     * Focus
         * coded with vanilla : reactJS, RN
         * UI : react-bootstrap(reactJS), native-base(RN)
 * Libraries
     * UI : react-bootstrap(reactJS), native-base(RN)
 * On Expo
     * differences : speed
 * JavaScript(used skills, summary)
     * ES6
         * Spread operator, Rest params
         * Destructuring
         * arrow function
         * Template literals
         * Dynamic key of object
     * ES7
         * Object spread
 * ReactJS(used skills, summary)
     * key points
         * Regular expression
         * Understanding on LifeCycle
         * setState with updater function
         * controlled components
         * Exception handling
     * UI
         * react-bootstrap
 * React Native(used skills, summary)
     * key points
         * Customized for RN(different from reactJS)
         * Understanding on LifeCycle
         * UI design with Flexbox
         * setState with updater function
         * Exception handling
         * Replace ListView with List of native-base
      * UI : native-base
          * Floating action buttons
          * Toast
          * Drawer
 * Design Pattern(used skills, summary)
     * module pattern

* * *   

# Svg

* [Git(vanilla JS)](https://github.com/royjkim/React-Native-bar-chart-svg-expo)

* ~~[Open App on Expo](https://expo.io/@roykim/bar-chart-svg-expo)~~

* ▼ Captures : App on iPhone

![BarChart](https://github.com/royjkim/Skills/blob/master/BarChart_Svg.gif)


  * Summary
      * made with vanilla JS
      * Focus
          * coded with vanilla JS, SVG
          * make functions separate and reusable
          * works in RN WebView
          * dynamic interval between bars on various device : flexbox used
          * reset makes whole data different from existing one
          * on bigger number, the color of bar is more bright
          * etc : bootstrap(v3.x), jQuery(v3.x)
  * Libraries
      * bootstrap(v3.x), jQuery(v3.x)
  * On Expo
      * differences : nothing
  * JavaScript(used skills, summary)
      * Creates an element with the specified namespace URI
      * Make custom functions for better performace
          * reduces calling setAttributeNS during coding
          * message delay for user recognition
          * find equal interval on each bars
          * text node is inserted just onetime


* * *   

# D3-bar-chart

* [Git(vanilla JS)](https://github.com/royjkim/d3-bar-chart-expo)

* ~~[Open App on Expo](https://exp.host/@roykim/d3-bar-chart-expo)~~

* ▼ Captures : App on iPhone

![D3-barChart](https://github.com/royjkim/Skills/blob/master/d3-barChart-1.gif)


  * Summary
      * made with JS and d3
      * Focus
          * coded with vanilla style
          * make functions separate and reusable
          * works in RN WebView
          * able to add / remove / reset data considering sort state
          * sort states(3) : not ordered, ascended, descended
          * animations on adding / removing / reset data
          * size, width and interval are reponsive
          * d3.scale.linear and d3.scale.orinal are used
          * if the value is getting higher, the color is close to blue
  * Libraries
      * d3(v3.x), bootstrap(v3.x)
  * On Expo
      * differences : nothing
  * Details(used skills, summary)
      * label is added on inner bar or above it
      * the range of the number of bars is 5 ~ 23
      * the target of removing is first data of current sort state
      * new data would be added on sorted position on ascending or descending sort state
      * on 'not ordered' sort state, bar is getting back its original position even though new data added on ascending/descending state
      * assigning proper width and height on svg
      * calculate proper interval on each bars
      * d3.scale.ordinal is used for discrete data because the data deleted is not done at fixed address
      * d3.scale.linear is used for calculating position and size
      * Make custom functions for better performace
          * many work is separated as functions
          * button events are integrated
          * animations have delay and duration for user recognition

* * *   

# DOMControl

* ▼ Captures : App on iPhone

![DOMControl](https://github.com/royjkim/Skills/blob/master/domControl.gif)

  * Summary
      * a JS library for HTML(external)
      * Focus
          * support Mobile only : multi browsers(including devices)
          * Works : Chrome, Safari, Firefox, WebView(Google FB, KakaoTalk), UC Browser(PC only)
              * Partially works : In App Browsers
              * Unsupported : UC Browser(Mobile), Samsung Browser, Opera(Coast, Mini), QQ Browser, etc.
              * Devices(verified) : iPhone 5 ~ 8, GalaxyS5 ~ S8+, GalaxyNote4, GalaxyNote Edge, Pixel, NEXUS, LUNA, LG Gpro2, etc.
          * new text/image over originals at similar size and position
          * animations on new text/image and restore it
          * works based on the web standard
          * handling JS and CSS(with sass) at the same time
          * responding to unexpected layout changes
          * foreign languages support : Korean, English, Japanese, Chinese and etc.
          * Reviewed
              * test various devices(not simulators) and browsers
              * responding to latest browser updates
              * experiences on cross-browsing
  * Libraries
      * jQuery, requireJS, scrollMagic, TweenMax, splitText, imagesloaded
  * JavaScript(used skills, summary)
      * custom elements used
      * for better compatibility disable to use ES6, ES7
      * sustaining existing code architectures
      * for faster and less resources, performance optimized
  * Design Pattern(used skills, summary)
      * module pattern
      * delegation pattern
      * proxy pattern
      * Self defining function
      * call back pattern
      * encapsulation

* * *   

# Visualization

* preparing to update

* Summary
    * made with vanilla JS and d3
    * Focus
        * make functions separate and reusable
        * reset makes whole data different from existing one
        * on bigger number, the color of bar is more bright
* Libraries
    * d3(v4.x), bootstrap(v3.x)
* JavaScript(used skills, summary)
    * Creates an element with the specified namespace URI
    * Make custom functions for better performace
        * message delay for user recognition
