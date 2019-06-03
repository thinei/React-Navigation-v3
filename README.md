# React-Navigation-v3

  **This application contains only two screen.**
  
  **This is just a simple react-navigation application.**

### Without using "react-native-gesture-handler"

    while I am on second screen and pressing hardware back of android

        Expected Result  -->  going back to first screen
        Real             -->  application is closing (crashed)
        
    This error solved after using "react-native-gesture-handler"
    
        Result  -->  Successfully go back to first screen
        

### In this project , use the following dependencies:
  ```
    "react": "^16.8.6",
    "react-native": "^0.59.8",
    "react-native-gesture-handler": "^1.0.12",
    "react-navigation": "^3.0.9",
    "react-navigation-redux-helpers": "^2.0.8",
    "react-redux": "^6.0.0",
    "redux": "^4.0.1"
