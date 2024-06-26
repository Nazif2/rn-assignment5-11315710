# rn-assignment5-11146019
rn-assignment5-11146019 project

Overview
Finance Tracker is a mobile application built with React Native that helps users manage their financial transactions. Users can view their recent transactions, manage different financial operations like sending, receiving, loans, and top-ups, and switch between light and dark themes.

Features
Home Screen with user profile, financial operations, and recent transactions.
Settings Screen with various options and a theme toggle.
Light and Dark mode support.
Navigation between Home and Settings screens.

Home Screen Component
The HomeScreen component displays the user's profile, a list of financial operations (Send, Receive, Loan, Topup), and recent transactions. It also includes navigation to the Settings screen and a toggle for dark mode.

Settings Screen Component
The SettingsScreen component provides various settings options like changing language, profile management, contact support, changing password, and privacy policy. It includes a toggle switch to change the theme.

Navigation
React Navigation is used to switch between the Home and Settings screens.

Dark Mode Implementation
A state variable isDarkMode is used to track the current theme. Conditional styling is applied to the components based on the isDarkMode state.

Styles
Styles are defined using StyleSheet.create and applied conditionally based on the isDarkMode state. 

![HomeScreen Lightmode](https://github.com/PAA-KWASI08/rn-assignment5-11146019/assets/170183141/4bccd94f-daa7-42b6-ad63-06485f9a4f52)
![HomeScreen Dark mode](https://github.com/PAA-KWASI08/rn-assignment5-11146019/assets/170183141/e47692ae-34ed-4318-a4ba-f4420e0f2790)
![Settings Screen light mode](https://github.com/PAA-KWASI08/rn-assignment5-11146019/assets/170183141/db86ae19-a691-40ef-934e-917708d2e6c4)
![Setting Screen Dark mode](https://github.com/PAA-KWASI08/rn-assignment5-11146019/assets/170183141/61df7b8b-6ea4-43a6-a65c-329f6d0ed796)
