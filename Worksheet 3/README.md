# comp110-worksheet 3

##Database structure:

Levels:
![](https://raw.githubusercontent.com/Alli1223/comp110-worksheets/master/Worksheet%203/levels.png "Levels")

Players:
![](https://raw.githubusercontent.com/Alli1223/comp110-worksheets/master/Worksheet%203/players.png "Players")

Scores:
![](https://raw.githubusercontent.com/Alli1223/comp110-worksheets/master/Worksheet%203/scores.png "Scores")


##Entity-Relationship Diagram:

![](https://raw.githubusercontent.com/Alli1223/comp110-worksheets/master/Worksheet%203/Entity%20Relationship.png "Entity Relationship")

___

##Pseudo Code for client-server communication

###Client Side:
```
Connect to database

Send Highscore to server

Retrieve Highscores

Terminate connection
```
###Server Side:

```
Retrieve Highscores from database

IF userID is not in database ADD them
    IF highscore is greater than previous highscore
        Update highscore
    END IF
END IF

Send Highscores to client
```