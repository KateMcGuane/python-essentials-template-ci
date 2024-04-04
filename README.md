![PYTHON TEMPLATE LOGO/IMAGE](link_to_file_in_these_brackets_if_applicable)


---


# *Nine Lives*

"Nine Lives" is a classic word-guessing game that puts players' vocabulary and deduction skills to the test. Much like its counterpart, Hangman, players attempt to guess a hidden word by suggesting letters one at a time. However, in "Nine Lives," the stakes are higher as players are granted a limited number of incorrect guesses, represented by the titular nine lives. With each incorrect guess, a life is lost, bringing them one step closer to failure. The challenge lies in strategically selecting letters to unveil the mystery word before all nine lives are depleted. "Nine Lives" offers a thrilling and engaging experience, combining elements of wordplay and suspense to keep players on the edge of their seats until the very end.

[View Python here](live_link_to_website)


---


## User Experience

   ### How to Play (OPTIONAL)

    EDIT AS REQUIRED.
    1. Describe the basic premise of the game. Link to Wikipedia with more detail.
    2. Distinguish any differences in this game and others.
    3. Give a clear organised list of instructions. This may be separate from the previous two points.

   ### User Story (OPTIONAL)

   #### External user’s goal:(OPTIONAL)

    - Goal 1
    - Goal 2
    - Goal None: You may have 1 or none.

   #### Site owner's goal:(OPTIONAL)

    - Goal 1
    - Goal 2
    - Goal None: You may have 1 or none.


---


## Design


   ### Colours

    EDIT AS REQUIRED.
    You can use [Colorama](https://pypi.org/project/colorama/), a built-in Python module which displays text in different styles and colours. It offers three formatting options of: Back, Fore and Style, which can change the colour of the text itself, the background of the text and the thickness of the text.


   ### Typography

    DETAIL SPECIFIC TYPOGRAPHIES (IF) USED.


   ### Flow Chart

    DELETE ANYTHING NOT APPLICABLE TO THIS PROJECT.
    There are some nice schema applications you can use for planning your project:
    - [Miro](https://miro.com/app/board/uXjVNiugb1U=/)
    - [Lucidchart](https://www.lucidchart.com/pages)

    I used _____ to illustrate some of the main logical points before I began to code.
    ![Flowchart](link_to_flowchart_documentation_here)
    I used _____ to plan the logic of my applicaiton.
    ![Flowchart](link_to_flowchart_documentation_here)


   ### Additional Features

    ADD ANY EXTRAS, SPECIFIC TO THIS REPOSITORY.

---


## Features


| Feature | Existing Features | Future Implementations | Screenshots |
| --- | --- | --- | --- |

### Gameplay
---


## Technologies Used


   ### Language

   - [Python](https://www.python.org/) - core language used.

   ### Libraries

   ### Frameworks & Tools

    DELETE ANYTHING NOT APPLICABLE TO THIS PROJECT.
   - [ChatGPT](https://chat.openai.com/)
   - [Colorama](https://pypi.org/project/colorama/) was used to add colors and styles to the project.
   - [Ezgif.com](https://ezgif.com/maker)
   - [GitHub](https://github.com/) was used to create & store my repository.
   - [Gitpod](https://www.gitpod.io/) was used as my workspace.
   - [Heroku](https://www.heroku.com/) was used to deploy the application.
   - [Lucid Chart](https://www.lucidchart.com/pages/)
   - [Miro](https://miro.com/app/board/uXjVNiugb1U=/)
   - [Visual Studio Code IDE](https://code.visualstudio.com/)


---


## Deployment & Local Development


  ### Deployment

REVIEW & EDIT THIS SECTION WHERE RELEVENT TO THIS PROJECT.
  The site was deployed early using Github Pages. The is how the live site was deployed:

  1. Log in (or sign up) to Heroku.
  2. Go to the user dashboard & click "Create new app". Keep in mind that each app name on Heroku has to be unique.
  3. Select the region & click "Create app".
  4. Go to the settings tab & scroll to the "Config vars" section.
  5. Click "Reveal Config Vars".
  6. Create a Config Var, set the key field to "PORT" & the value key to "8000".
  7. If you have credentials, insert "CREDS" for the key field. Copy & paste the entire JSON file to the value field.
  8. Scroll to the "Buildpacks" section.
  9. Click "Add buildpacks". Select "Python" and "nodejs", and in that order.
  10. Go to the “Deploy” tab.
  11. Scroll to the “Deployment Method” section.
  12. Click on "Github" followed by "Connect to Github".
  13. A pop up window will show. Click "Authorize Heroku". From here you will be asked to login to Github.
  14. Click on “Connect to Github”. Search for the repository name ‘REPOSITORY_NAME’ & click "Connect".
  15. Scroll to the "Manual Deploys" section.
  16. Click "Deploy Branch". A message will show up to say "Your app was usccessfully deployed. The "View" button will take you to your deployed link.


  ### Local Development

  #### How to Fork

  To fork the Hobby repository:

  1. Log in (or sign up) to Github.
  2. Go to the repository for this project, [YOUR_AC_NAME / REPOSITORY_NAME](insert_webpage_link).
  3. Click the Fork button in the top right corner. This action will create a copy of the repository under your GitHub account.


  #### How to Clone

  To clone the PROJECT_NAME repository:

  1. Log in (or sign up) to GitHub.
  2. Go to the repository for this project, [YOUR_AC_NAME / REPOSITORY_NAME](insert_webpage_link).
  3. Click on the code button, select whether you would like to clone with HTTPS, SSH or GitHub CLI and copy the link shown.
  4. Open the terminal in your code editor and change the current working directory to the location you want to use for the cloned directory.
  5. Type 'git clone' into the terminal and then paste the link you copied in step 3. Press enter.


---


## Testing

Please see [TESTING.md](TESTING.md) for a comprehensive list of tests performed.


---


## Credits

  ### Markup

    The markup outline for this project was taken from the following README files:
    - [Kate McGuane / hobby](https://github.com/KateMcGuane/hobby)
    - [PedroCristo / portfolio_project_3](https://github.com/PedroCristo/portfolio_project_3/blob/main/README.md)


  ### Content

  - The terminal function & template for the deployable application was created by Code Instutute for their [Python Essentials Template](https://github.com/Code-Institute-Org/python-essentials-template).
  - The introduction for the README file was generated by Chat GPT.
  - CREDIT ANY OTHER CONTENT USED


  ### Code

  - CREDIT CODE & CREATOR.
  - CAN SPECIFY CERTAIN AREAS OF THE CODE THAT WERE USED.
  - I followed the format of the XXXXXX XXXXXX. This was to ensure best practice in creating my first interactive Front-End web application.


  ###  Media

  - YOUTUBE VIDEOS


  ###  Acknowledgments

  - PERSONALISE YOUR ACKNOWLEDGEMENTS HERE
  - Thank you to my mentor, cohort leader & CI team for your support in getting this project complete.
  - To Sarah, thank you for all the 1:1 zoom calls.
  - To Mikhail, thank you for your continued support.


---


## DELETE ON FINAL REVIEW OF PROJECT:

This is the Code Institute student template for deploying your third portfolio project, the Python command-line project. The last update to this file was: **August 17, 2021**

## Reminders

* Your code must be placed in the `run.py` file
* Your dependencies must be placed in the `requirements.txt` file
* Do not edit any of the other files or your code may not deploy properly.

## Constraints

The deployment terminal is set to 80 columns by 24 rows. That means that each line of text needs to be 80 characters or less otherwise it will be wrapped onto a second line.