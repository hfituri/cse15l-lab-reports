# ***Lab Report 4***

## Keys Pressed to Fix the Code for ListExamples
---
* (up)(enter)  executed: ssh cse15lfa23hu@ieng6.ucsd.edu. The up arrow went to the previopus command and i pressed enter to execute it.
* 'g' 'i' 't'(space)'c' 'l' 'o' 'n' 'e'(space)(Ctrl-V)(enter) executed: git clone git@github.com:hfituri/lab7.git. The next step I typed "git clone" and already had the ssh for the repository copied to my clipboard to I pasted it after git clone and pressed enter to execute.
* 'c' 'd'<space>'l'(tab)(enter) executed: cd lab7/. In this step, we changed our directory to lab7 and used tab to finish the word instead of typing it out.
* 'b' 'a' 's' 'h'(space)'t'(tab)(enter) executed: bash test.sh. This step required us to run our test to make sure that it initially failed and used tab, like the previous step, to autofill.
```
JUnit version 4.13.2
..E
Time: 0.542
There was 1 failure:
1) testMerge2(ListExamplesTests)
org.junit.runners.model.TestTimedOutException: test timed out after 500 milliseconds
        at ListExamples.merge(ListExamples.java:44)
        at ListExamplesTests.testMerge2(ListExamplesTests.java:19)

FAILURES!!!
Tests run: 2,  Failures: 1
```
*'v' 'i' 'm'(space)'l' 'i'(tab)(enter) executed: vim ListExample.java. We opened up vim in this step and used <tab> like previous steps to auto complete.
*'6'(up)(down)'13'(right)(left)'i'(backspace)'2'(esc)':' 'w' 'q' '!'(enter). For this step, we were in vim and needed to make the necessary changes to the code. I went 6 up, one down, 13 to the right, one to the left, and then I entered 'i' to enter insert mode and change "index1" to "index2" and saved useing ":wq!". Using a number before pressing the arrow key allows you to go that many spaces in that dierection.
*(up)(up)(enter) executed: bash test.sh. Since I have already used this command before, I can access it by using the up arrow key twice and pressing enter.
```
JUnit version 4.13.2
..
Time: 0.014

OK (2 tests)
```
*'g' 'i' 't'(space)'a' 'd' 'd'(space)'l' 'i' 's'(tab)(enter) executed: git add ListExamples.java. This step we add the the file that was changed to github.
*'g' 'i' 't'(space)'c' 'o' 'm'(tab)(enter) executed: git commit. This step we now committed the code that we wanted to github.
*"Changed index1 to index2"(esc)'':' 'w' 'q' '!'(enter). In this step, we wrote down the commit message and then I saved and quit like it was vim.
*'g' 'i' 't'(space)'p' 'u' 's' 'h'(enter) executed: git push. As the final step, we pushed our changes into github and now are changes can be seen there.
