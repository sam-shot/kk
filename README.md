## Gritty Grammar

### Project Description

Gritty Grammar is a website and a bot-correction app that ensures accurate spelling, punctuation, and sentence structure in users' input as well as clear, compelling, and easy-to-read English and everything typed by its user.

### Design

This [link](https://www.figma.com/file/5m5Va82cgR06X1sOIQPSMZ) contains the design that will be implementd for the project.

## State Management

We will be using provider state management, as this state manager will be efficient for our app. provider is used to manage data shared between app screens. 
Introducing a state management system in our app is to enable smooth and responsive features. It is also to prevent the unnecessary rebuilding of screens and notify screens that need information on the recent updates that occurred as a result of an action.

#### Models
 > These are responsible for fetching the data from the server or local DB and transfer to the ViewModel.
 They are located in the `lib/models` folder.

#### ViewModel

 >ViewModel is used to transfer data between View and Model, which accept all the user events and request that to Model for data response. Once the Model has data then it returns to ViewModel and then ViewModel notifies that data to View.
 ViewModel can be used by multiple views, which means a single ViewModel can provide data to more than one View.
 All View-Models are located in the `lib/view_models` folder.

#### View
 >The view is where the user interacting with Widgets that are shown on the screen. User event request for some data from ViewModel, and the rest of ViewModel process the event as per the request to Model. Once the ViewModel gets the data from the model as requested then it reflects on the user view.
 All Views are located in the `lib/views` folder.


## Project Structure 

 - `lib` : *This is main directory of the project*
 - `lib/models` : *This directory will hold all the model classes for the API response*.
 - `lib/repo` : *This directory will hold all the repository classes used in the project for communicating with the ViewModel.*
 - `lib/res` : *This directory will hold all the classes related to the colors, style & strings files*
 - `lib/view_models` : *This directory will hold all the ViewModel-related classes with subdirectory if required.*
 - `lib/views` : *This directory will hold all the view-related classes with subdirectory as per the module & widget as well for the project.*

 ## Contribution Guide 

 - **Clone the repo (Do this by pasting this line on your terminal** `https://github.com/workshopapps/grammarcheckerai.mobile ` )
 - **Change your branch to the one you want to work with**
 - **Make your Changes**
 - **Commit your changes following** [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)
 - **Push your branch**
 - **Make your Pull Request and add a reviewer to merge your Pull Request**
