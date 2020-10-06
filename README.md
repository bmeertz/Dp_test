# Dp_test
Testing your .NET Skills! 

# Tasks

1) Track the execution time and save the results for each function/method that you use to complete the tasks (2, 4, 5)
2) Connect to the API with the parameter https://dptest.meertzware.eu/?key=%YOUR_TEST_KEY%
3) The API will give you a encrypted string as a result
4) Decrypt the AES encrypted string with your personal key
5) Use the code sample or create your own code/project to connect to the NoSQL Firebase database and write your results based on the following JSON structure and store them in the NoSQL database (find the credentials in firebase.connect.txt)
5.A) Change the Values: 
  5.A.I) YOUR_KEY
  5.A.II) YOUR FUNCTION/METHOD NAME
  5.A.III) YOUR FUNCTION/METHOD DESCRIPTION
  5.A.IV) YOUR EXEC.TIME
6) Upload your Code to this github-repo in a separate branch with your name as the branch name

    "YOUR_KEY": {
        "functions": [
            {
              Function: YOUR FUNCTION/METHOD NAME
              Description: YOUR FUNCTION/METHOD DESCRIPTION
              Execetion_Time: YOUR EXEC.TIME
            },
            {
              Function: YOUR FUNCTION/METHOD NAME
              Description: YOUR FUNCTION/METHOD DESCRIPTION
              Execetion_Time: YOUR EXEC.TIME
            },
            {
              Function: YOUR FUNCTION/METHOD NAME
              Description: YOUR FUNCTION/METHOD DESCRIPTION
              Execetion_Time: YOUR EXEC.TIME
            },
            ...
        ]
     }
