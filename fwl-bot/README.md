# FWL Discord Bot
A very simple Discord bot made with [**TypeScript**](https://www.typescriptlang.org/) & [**discord.js**](https://npmjs.com/package/discord.js) version 14.

## Installation
Install `typescript` globally:

```sh
npm i -g typescript
```

Install all the required dependencies:

```sh
npm i
```

> **Warning**
You will need a valid **.env** file.

To compile the TypeScript files to JavaScript files & run the compiled files, use the command below:

```sh
npm run start
```

## 📚 **How to use the Bot?**

### Updating Leaderboard

<h3 align="center">Small Disclaimer</h3>

⚠️ **The tournament and team fields in commands are always autofill, discord is sometimes slow u might have to wait**

⚠️ **Also Leaderboard will show the actual rounds like in the game instead of the surpassed, points still are based on surpassed**


<h3 align="center">Kill Race Template Leaderboard Update</h3>

1. The template uses the **1P per kill**, **15P per surpassed round**, **30P per win**.
2. It automatically calculates the surpassed rounds, only **enter whats on submitted screenshot eg. 3/4 => 3 rounds**
3. It automatically **saves all entered games** and **sets the score for the best 3 Games**.
4. For easier use the command has kills1,2,3 for player 1,2,3 so u dont have to add them.



<p align="center">
    <b>Use the command on the screenshot to update</b><br/>
</p>

![Drops](https://i.imgur.com/70nAXho.png)

<p align="center">
    <b>This results in the response</b><br/>
</p>

![Drops](https://i.imgur.com/QH0fFud.png)

<p align="center">
    <b>You can run this command as often as u want, tho discord embed can only show 24 games.</b><br/>
</p>

![Drops](https://i.imgur.com/yHhKrY0.png)

<p align="center">
    <b>As u can see the top3 games are 1 - 3 and 4 is shown but does not affect the overall score there for is crossed out.</b><br/>
</p>
<p align="center">
    <b>To remove the game 2 for example u can use the id after 2 - ...</b><br/>
    <b>This command has also the optional field "all" which can be set to true to delete all games</b><br/>
</p>

![Drops](https://i.imgur.com/kpaPJmS.png)

<p align="center">
    <b>This would respond with</b><br/>
</p>

![Drops](https://i.imgur.com/iugA98C.png)

<p align="center">
    <b>You can also use the info command to just get the currently saved games, same embed as before.</b><br/>
</p>

![Drops](https://i.imgur.com/oQwqbmo.png)

<h3 align="center">Kill Race Direct Leaderboard Update</h3>
1. Updates the score directly. Entering kills: -1 will subtract 1 and kills: 1 add one
2. If u used the template before the score will change based on what the team has currently. If u then use the template again it will use all submitted games instead.

<p align="center">
    <b>Example:</b><br/>
</p>

![Drops](https://i.imgur.com/a2FenQz.png)

<p align="center">
    <b>This results in:</b><br/>
</p>

![Drops](https://i.imgur.com/0kpWJnD.png)

<p align="center">
    <b>Now with -1:</b><br/>
</p>

![Drops](https://i.imgur.com/0kpWJnD.png)

<p align="center">
    <b>This results in:</b><br/>
</p>

![Drops](https://i.imgur.com/f355PAx.png)

### Role Command

<p align="center">
    <b>Add a role to all captains of a tournament. Use the remove command to undo.</b><br/>
    <b>⚠️ Make sure to set captain = true, its a optional option</b><br/>
</p>

![Drops](https://i.imgur.com/eP2vSBi.png)

### Info Commands
<p align="center">
    <b>Use info commands to get some info kinda self explanatory.</b><br/>
</p>

![Drops](https://i.imgur.com/jLKTQZy.png)

### Other Commands
<p align="center">
    <b>Most of other commands are just for easier interaction between website data without a need for a web ui.</b><br/>
</p>
