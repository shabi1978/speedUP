# speedUP

Objective of this tool to speedUP your development in a smooth way. Being in IT industry as a developer we experienced lots of repetation work which takes lots of our precious time and lost of interest due to same kind of work hence we came up with an idea where you can do copy of your work with new values in minimal efforts and in a click.

# Requirement

Your machine must have installed Java8.

# Follow the steps to generate the copy of your work.

Step 1. Download speedUP from "https://github.com/shabi1978/speedUP.git".

Step 2. Unzip speedUP-main.

Step 3. Copy "speedUP-main" in to C drive .

Step 4. Go to into "C:\speedUP-main\speedUP-main\configuration".

Step 5. Modify "gitCredentials.yaml" and add your Git credentials.

Step 6. Add your Git repo link in "gitPosConfiguration.yaml".

Step 7. Add your values in "posConfiguration.yaml" which you want to replace with the existing one(LeftHand is Old Value and RightHand is New Value). Kindly take note it will rename your files, file reference and directory according to your input.

Step 8. Go to into "C:\speedUP-main\speedUP-main" click on SpeedUP.jar and  <b> wait for few seconds </b> your new directory will generate according to destinationDirectoryPath which exist in "gitCredentials.yaml"

Enjoy and happy learning....!

above steps follow to generate the copy of code with new values from git and same thing can be done in order to generate code from the local machine also after modify "C:\speedUP-main\speedUP-main\configuration\inputType.yaml" . Change form "gitFlag: yes" to "gitFlag: no" and add your local code path in "posConfiguration.yaml" instead of Git repo link.