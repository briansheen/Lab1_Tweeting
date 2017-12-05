# Lab1_Tweeting

## Objective:  

To post a tweet using Twitter account @bsman

## How To Use (for Mac):
  - create a directory in Finder or in Termial where the program will be located
  - open Terminal 
  - in Terminal, enter the following:
    ```
    cd {location of directory you created above}
    ```
    ```
    git clone https://github.com/briansheen/Lab1_Tweeting.git
    ```
    ```
    javac -cp {enter the directory path to Lab1_Tweeting folder}/lib/twitter4j-core-4.0.3.jar:. com/company/Main.java
    ```
    ```
    java -cp {enter the directory path to Lab1_Tweeting folder}/lib/twitter4j-core-4.0.3.jar:. com/company/Main '{enter your tweet message here}'
    ```
