@echo off

:menu

title Maze for Dayz Game

color 0D

cls

echo.

echo.

echo Maze for dayz: your in a cave and its dark you have a torch ...

echo Type 1 to go left!

echo Type 2 to use us torch!

echo type 3 to go right!

set /p choice=

If %choice% EQU 1 goto left

If %choice% EQU 2 goto torch

If %choice% EQU 3 goto right

:left

title you went left

color 0D

cls

echo you went left

echo you walk into a pit and starve

pause

goto menu
	
:torch

title you use your torch

color 0D

cls

echo torch

echo your torch has no batterys and you walk into a wall and go unconscious...

pause

goto menu

:right

title you went right

color 0D

cls

echo you went right

echo you see a light at the end of the tunnel

echo.

echo Type 1 to go outside!

echo Type 2 to go back!

set /p choice=

If %choice% EQU 1 goto outside

If %choice% EQU 2 goto back!

:outside

title you go outside

color 0D

cls

echo outside

echo you go outside and you see a unicorn...

echo.

echo Type 1 kill unicorn

echo Type 2 Admire unicorn

set /p choice=

If %choice% EQU 1 goto Kill unicorn

If %choice% EQU 2 goto Admire unicorn 

:Kill unicorn

title you killed the unicorn

color 0D

cls

echo you killed the unicorn for the sake of survival

echo you have the choice to cook it or not

echo.

echo type 1 to cook it 

echo type 2 to eat it raw

set /p choice=

If %choice% EQU 1 goto cook

If %choice% EQU 2 goto eat raw

:Admire unicorn

title you chose to admire unicorn

color 0D

cls

echo you chose to admire unicorn 

echo it sees you and kills you 

pause

goto menu 

:cook

title you decided to cook the unicorn meat

color 0D

cls

echo you decided to cook the unicorn meat

echo you burnt it and it is not edible 

echo.

pause 

goto menu

:eat raw

title you decided to eat it raw

color 0D

cls

echo you decided to eat the meat raw for the sake of survival

echo you decided to not risk cooking it

echo.

echo type 1 to move on

echo type 2 to stay the the night

set /p choice=

If %choice% EQU 1 goto move on

If %choice% EQU 2 goto stay 

:stay

title you stayed there night

color 0D

cls

echo you decided to stay outside 

echo it rains and breaks your torch and eletricutes you

echo.

pause

goto menu

:move on 

title you chose to move on

color 0D

cls

echo you chose to move on 

echo it gets dark

echo.

echo type 1 to find shelter

echo.

set /p choice=

If %choice% EQU 1 goto find shelter


:find shelter

title go go to find shelter

color 0D

cls

echo you go to find shelter

echo you find a cave to stay in and you go inside to find

echo a dull blade in the wall

echo.
 
echo type 1 to take blade into inventory

echo type 2 to 'give up'

echo.

set /p choice=

If %choice% EQU 1 goto take it

If %choice% EQU 2 goto 'give up'

:sleep out side

title you chose to sleep out side

color 0D

cls

echo you chose to sleep out side

echo your struck by lightning and die

echo.

pause

goto menu

:'give up'

title you give up

color 0D

cls

echo you have decided the journey has lasted too long and 

echo don't feel like its worth it

echo you end your life peacefuly on your own turms

echo.

pause

goto menu

:take it

title you take the dull blade

color 0D

cls

echo your take the knife as you feel it is neccesary

echo you become tired and want to sleep

echo.

echo type 1 to sleep

set /p choice=

If %choice% EQU 1 goto inside

:inside

title you sleep in the cave

color 0D

cls

echo you sleep in the cave on the dampish floor

echo.

echo type 1 to dream

echo type 2 to continue

set /p choice=

If %choice% EQU 1 goto dream

If %choice% EQU 2 goto get up

:dream

title you have a dream

color 0D

cls

echo you dream a dream where you try to remember how you got here and where 'here' is

echo you try to remember your past life as if it was something great 

echo you wonder if was important and if people are looking for you

echo you wonder if it is worth living any more 

echo.

echo your dreams ends on that note

echo.

echo type 1 to get up

set /p choice=

If %choice% EQU 1 goto get up

:get up

title you wake up

color 0D

cls

echo you wake up and the sun rays blind you from the outside world

echo.

echo type 1 to stay inside

echo type 2 to go outside

set /p choice=

If %choice% EQU 1 goto waste

If %choice% EQU 2 goto exsplore

:waste

title you decide to be a boring twat and stay inside 

color 0D

cls 

echo you decide to be a boring twat and stay inside 

echo one would call you a 'massive twat'

echo you waste your exsploration time by staying inside until it gets dark again

echo.

echo type 1 to sleep

set /p choice=

If %choice% EQU 1 goto inside

:exsplore

title you go out 

color 0D

cls

echo you go out into the field you can see clearly now

echo its a beautiful land with places to exsplore

echo.

echo type 1 to go to the lake

echo type 2 to go to the forest

echo type 3 to go to the hilltops

set /p choice=

If %choice% EQU 1 goto lake

If %choice% EQU 1 goto forest

If %choice% EQU 1 goto hilltops
