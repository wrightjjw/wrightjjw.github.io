<template>
    <div>
    <h1>Operation Catapult: Tetris Reborn</h1>
    <h2><a href="https://github.com/wrightjjw/tetris">github.com/wrightjjw/tetris</a></h2>
    <p>
        This is the first project I ever worked on!
        The summer before my senior year of high school,
        I was involved with a program called Operation Catapult
        hosted by Rose-Hulman Institute of Technology (RHIT).
        RHIT is a prestigious STEM school,
        and Operation Catapult is meant as a sort of prep for college and the workplace
        by working on a STEM related project for a few weeks in the summer.
        You can read more about Operation Catapult
        <a href="https://www.rose-hulman.edu/admissions-and-aid/early-planning/operation-catapult/index.html">here</a>.
    </p>
    <p>
        Everyone working in the same field worked at the same location,
        so all the computer science students worked in a computer lab.
        I was originally working on a team of two, but my partner ended up leaving the program a few days in,
        so I got to join my team of choice.
        There were a lot of interesting projects,
        but one team in particular was struggling with their project.
        Seemed like they could use another team member, so I ended up joining.
        I was the only one with prior programming experience,
        so I was able to help the team a lot.
        Immediately, I was able to help with rendering tetriminos and the logic behind stacking them,
        but the rest of the team definitely began pulling their weight as the days went on.
        I tended to work more on game logic than anything else.
    </p>
    <div class="showcase">
        <div id="img1"> <img src="@/assets/tetris/start.png" width="300px"> </div>
        <div id="img2"> <img src="@/assets/tetris/game.png" width="300px"> </div>
        <div id="img3"> <img src="@/assets/tetris/score.png" width="300px"> </div>
    </div>
    <p>
        We had a lot of fun working on this project.
        It was a blast not just to work on the actual game,
        but its own presentation as a piece of software.
        We had some good discussion about making graphics and picking music for the game.
    </p>
    <p>
        We also had to present the project at what was essentially an expo for every project at Operation Catapult.
        Friends, family, and judges all came to see our project.
        And we won 3rd best project of the entire event!
        I was pretty surprised, as there was a lot of engineering projects that looked way more impressive to me,
        but I've come to realize what made this project so good.
        Sure, in the beginning the group had no grasp on how even to proceed,
        but every team member put in a lot of work to make the best product they could.
        We had a plan and we followed it; loading in our blood, sweat, tears, and passion.
        To this day, I am still very proud of this project.
        And it still runs on modern Python 3 and Pygame!
    </p>
</div>
</template>

<style>
#img1 {
    grid-column: 1;
    grid-row: 0;
}

#img2 {
    grid-column: 2;
    grid-row: 0;
}

#img3 {
    grid-column: 3;
    grid-row: 0;
}

.showcase {
    display: grid;
}
</style>
