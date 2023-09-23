# Cricket_scorecard

The program Cricket Scoresheet.c is a fully automated code and act as cricket scorer. We derived this idea from the APP - CricHeroes. <br>We created this program in the fall of 2021 (oct'21 and nov'21). This program has main_menu function which will first make you enter the playing XI of both the teams and Name of the teams for display. We have provided the cricket scorer with options to go with our default names(from the 2021 Eng vs Ind Series)<br>
The Default team members are:
India
1. Rohit
2. Rahul
3. Ishan
4. Kohli
5. Yadav
6. Dhoni
7. Thakur
8. Ashwin
9. Shami
10. Jassi
11. Jadeja

England
1. Jason
2. Root
3. Morgan
4. Jos
5. Malan
6. Johnny
7. Ali
8. Chris
9. Jordan
10. Wood
11. Khan


or they can add all the names themselves. Once this is done, we move on to the toss and display the result of the toss and the winning team is provided as the first team by the default as per the entry. The Game starts!!! Then, we show the following options:
- Add to Timeline events
- Enter details for the next innings
- Display Scorecard (if the scorer Chooses to)
- Display the timeline(this shows the last few balls faced)
- Display the result(if the game hands)
- Exit (if the game is over)
<br><br><br>

-  Timeline events is entered through the events() function:
The events functions covers all the possible events that may occur on a ball and is mentioned as follows:
1. Runs from the bats.
2. Leg-byes of the pads or body.
3. No-balls.
4. Wide.
5. Byes.
6. Wickets.
7. End-of-Over (Change Strike and Show the scorecard -by default)
8. End-of-innings
9. Option to go back to main-menu

- The new Innings will be first checked by our code and only then the 2nd innings will begin.

-  The scorecard can be displayed at any time the presenter wants to.

-  Shows the last few balls that were bowled

- The code will first check whether the game has ended and a result can be declared and then it will show the final result.
