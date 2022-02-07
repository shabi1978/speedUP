# speedUP

The objective of this tool is to speedUP your app/api development process and to make it smooth. Being in the IT industry as developers, we the people at Ezygen, experienced a lot of repetative work which takes a lot of our time and also end up loosing our interest due to the monotony. To help with this we have developed a tool(speedUp.jar). Using this tool you will be able to generate a copy of your code with the new values desired with minimal efforts and that too with just a single 'click'.

# Requirement

Your must have Java8 installed in your device.

# Follow the following simple steps to generate the copy of your work:-

Step 1. Download speedUP from "https://github.com/shabi1978/speedUP.git"

Step 2. Unzip speedUP-main.

Step 3. Copy "speedUP-main" in your C drive .

Step 4. Go to into "C:\speedUP-main\speedUP-main\configuration".

Step 5. Enter your git credentials in "gitCredentials.yaml".

Step 6. Add your Git repo link in "gitPosConfiguration.yaml".

Step 7. Add the key values in "posConfiguration.yaml" (on the Left side will be Old Values and on Right side will be New Values, separated by a colon: ). Kindly note- this will rename your files, file references and directory according to your input.

Step 8. Go to into "C:\speedUP-main\speedUP-main", double click on SpeedUP.jar and  <b> wait for a few seconds. </b> The new directory will get generated according to destinationDirectoryPath which exists in "gitCredentials.yaml"



Follow the above steps to generate a copy of code with new values from git and the same thing can be done in order to generate code from the local machine also after modifying the file - "C:\speedUP-main\speedUP-main\configuration\inputType.yaml" . Change  "gitFlag: yes" to "gitFlag: no" and add your local code path in "posConfiguration.yaml" instead of Git repo link.

Happy learning....!
