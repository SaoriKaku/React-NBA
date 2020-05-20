# React JS based NBA Player Strength Visualization

## Part 1: A simple presentation this ReactJS project

1. Command: npm start, you will see a default webpage with Stephen Curry's information.
![image](https://github.com/SaoriKaku/React-NBA/blob/master/images/nba-1.png)

2. If you search "James", you will see the suggestions with players' image and name in the dropdown.
![image](https://github.com/SaoriKaku/React-NBA/blob/master/images/nba-2.png)

3. Click "James Harden", you will see the webpage with James Harden's information with slider's value equal to "1", chart type "hexbin" and switch "off".
![image](https://github.com/SaoriKaku/React-NBA/blob/master/images/nba-5.png)

4. If you change to switch to "on", you can see a tooltip when your mouse hover on a position.
![image](https://github.com/SaoriKaku/React-NBA/blob/master/images/nba-4.png)

5. You can move the slider from "1" to "20"(the current value is 10 points), it only shows positions which the player gets points no less than slider's value.
![image](https://github.com/SaoriKaku/React-NBA/blob/master/images/nba-3.png)

6. By default, the chart type is "hexbin", you can change it to "scatter".
![image](https://github.com/SaoriKaku/React-NBA/blob/master/images/nba-7.png)

7. With the switch "on", a tooltip will pop up when you mouse hover on a position.
![image](https://github.com/SaoriKaku/React-NBA/blob/master/images/nba-6.png)

## Part 2: techinical points

1. Built a dashboard using React, D3 and Ant Design backed by API from stats.nba.com to visualize individual player’s shot data, including a shot chart and user profile view.
2. Created 4 extra filters and 2 shot themes (hexbin and scatter) to provide more customized visualization on shot chart.
3. Constructed a autocomplete player search bar providing a list of players (image and name) in a suggestion list.

**Thank you for reading.**
