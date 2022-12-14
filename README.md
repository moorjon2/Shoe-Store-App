# The Shoe Store

This project will consist of five screens. You don't have to create a shoe store, you can use any other item as long as you create the following screens. You will be creating:

1. Login screen: Email and password fields and labels plus create and login buttons
2. Welcome onboarding screen
3. Instructions onboarding screen
4. Shoe Listing screen
5. Shoe Detail screen for adding a new shoe

## Getting Started

Open the starter project in the latest stable version of Android Studio.

Open the starter project in Android Studio


## Steps

[comment]: <> (Added TODO's to be able to track them within Android Studio, thats why they are duplicated)

[//]: # (TODO: 1. Open the starter project in Android Studio)
1. Open the starter project in Android Studio

[//]: # (TODO: 2. Add the navigation libraries to the app build.gradle file)
2. Add the navigation libraries to the app build.gradle file

[//]: # (TODO: 3. Add the safe-arg plugin to the main and app build.gradle file)
3. Add the safe-arg plugin to the main and app build.gradle file

[//]: # (TODO: 4. Create a new navigation xml file)
4. Create a new navigation xml file

[//]: # (TODO: 5. Create a new Login destination)
5. Create a new Login destination.

   * Include email and password labels 

   - Include email and password fields
   - Create buttons for creating a new login and logging in with an existing account
   - Clicking either button should navigate to the Welcome Screen.

[//]: # (TODO: 6. Create a new Welcome screen destination that includes:)
6. Create a new Welcome screen destination that includes:

   * A new layout
   * At least 2 textviews
   * A navigation button with actions to navigate to the instructions screen

[//]: # (TODO: 7. Create a new Instruction destination that includes)
7. Create a new Instruction destination that includes:

   * A new layout
   * At least 2 textviews
   * A navigation button with actions to navigate to the shoe list screen

[//]: # (TODO: 8. Create a class that extends ViewModel)
8. Create a class that extends ViewModel

   *  Use a LiveData field that returns the list of shoes

[//]: # (TODO: 9. Create a new Show List Destination that includes:)
9. Create a new Shoe List destination that includes:

   * A new layout
   * A ScrollView
   * A LinearLayout for Shoe Items
   * A FloatingActionButton with an action to navigate to the shoe detail screen

[//]: # (TODO: 10. In MainActivity, setup the nav controller with the toolbar and an AppBarConfiguration.)
10. In MainActivity, setup the nav controller with the toolbar and an AppBarConfiguration.

[//]: # (TODO: 11. Create a new Show Detail destination that includes:)
11. Create a new Shoe Detail destination that includes:

    * A new layout
    * A TextView label and EditView for the
      * Shoe Name
      * Company
      * Shoe Size
      * Description
    * A Cancel button with an action to navigate back to the shoe list screen
    * A Save button with an action to navigate back to the shoe list screen and add a new Shoe to the Shoe View Model

[//]: # (TODO: 12. Make sure you can't go back to onboarding screens)
12. Make sure you can’t go back to onboarding screens

[//]: # (TODO: 13. In the Shoe List screen:)
13. In the Shoe List screen:

    * Use an Activity level ViewModel to hold a list of Shoes (use by activityViewModels)
    * Observe the shoes variable from the ViewModel
    * Use DataBindingUtil to inflate the shoe_list layout
    * Add a new layout item into the scrollview for each shoe.