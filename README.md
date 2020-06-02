# Jungle Devs - Frontend Challenge #004

  ## Description
  **Challenge goal**: The goal of this challenge is for you to organize your routes with Reach Router and use React Context API to have a global state and avoid prop drilling in complex scenarios. The challenge proposed is a very common issue in the web development world! Get ready!
  
  **Target level**: To tackle this challenge you must know how React states work, HTML, CSS and the idea is to familiarize yourself with Reach Router and Context API.
  
  **Final accomplishment**: By the end of this Hands-on you’ll have a well organized route system to your website and global states defined by your Context API. Your component will be able to update based on this state and your page will have a different behavior according to the route the user is in.
  
  
  ## Resources
  **Design**: **PENDING**
  
  
  ## Acceptance criteria
  * Your routes must be organized the with parent and child like described below:
    * App (”/” route and has the header of the application) - **Parent**
      * Update user (”/update-user” route with the inputs to change first and last name) - **Child**
      * User info (”/user” route with the user information that was saved) - **Child**
  * The save button should only appear in the “/update-user” route;
  * The header must be defined in the parent route;
  * Both routes must be children to the parent route;
  * The inputs must show the user first and last name if they were already between changing routes;
  * The “/user” route must only update values if the user clicked on save on the “/update-user” route;
  * No console warnings are acceptable.
  
## Prerequisites
  * Use Reach Router;
  * Use Context API;
  * The header must be in a parent component, with no repeating code between routes.
  
## Instructions to Run
  * Clone the repository and run `yarn start`.
  
## Additional Information
  None (:
