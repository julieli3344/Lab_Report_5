# Lab Report 5
## Debugging Scenario
**Original Scenario on Edstem**

<img width="1440" alt="Screen Shot 2023-06-05 at 5 19 24 PM" src="https://github.com/julieli3344/Lab_Report_5/assets/83881461/7dd2040a-0b1c-4362-963c-3dada0833b5e">
<img width="1440" alt="Screen Shot 2023-06-05 at 5 19 37 PM" src="https://github.com/julieli3344/Lab_Report_5/assets/83881461/f845bfe6-ad83-4a0d-a42f-bd0094c63ad6">
<img width="1440" alt="Screen Shot 2023-06-05 at 5 19 41 PM" src="https://github.com/julieli3344/Lab_Report_5/assets/83881461/aa978128-14d6-4c35-934e-e120a95fbb89">

**A response from a TA(prented to be one) of what to try to fix error**
TA Response: for this kind of error, maybe try looking at the line decribed in the symptom to see where the error starts. Since you have written the test cases for reversed, try looking at the code in reversed and see what went wrong. 


**Another screenshot of trying the command and description of error**
I tried to follow the advice of the TA by looking at the reversed code to see what went wrong. The error was indeed within the code, and it was because the for loop was wrong, it should have been `array.length / 2` and the variable was set to the wrong thing. 

<img width="1440" alt="Screen Shot 2023-04-20 at 4 58 36 PM" src="https://github.com/julieli3344/Lab_Report_5/assets/83881461/e4f75d52-64dd-41ac-b2d3-e8c26230c143">

**info needed about setup(file and directory structure | contents of each file before fixing bug | full command line to run bug | decription of what to edit to fix bug)**

1.structure:
<img width="1440" alt="Screen Shot 2023-06-05 at 5 56 25 PM" src="https://github.com/julieli3344/Lab_Report_5/assets/83881461/9329017f-172e-4fb8-a91e-937408523046">

2. contents of each file:
<img width="1440" alt="Screen Shot 2023-06-05 at 5 57 41 PM" src="https://github.com/julieli3344/Lab_Report_5/assets/83881461/21aab2a8-4abc-48bf-86a3-27ec79ff1920">

3. What I ran to trigger the bug:
`javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java`
`java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ArrayTests`
4. What I did to fix bugz;
- first I changed the for loop, so instead of finishing the whole loop, it would stop half way, and I also set `var` equal to `arr[i]`. 


Reflection
During the second half of this class I have learned many things that were new to me. I have never heard of vim before, and after using it during a lab, it was extremely useful and easier to edit the text. When there was an error in the code, I can just put in for example vim arraylist.java and go into the editor mode. I can also use shortcuts and other ways to edit it through there making editing go faster.
