# THE PLAN

## Goal
Build Pokemon Top Trumps!

## How would it work
- Player picks a pokemon
- Computer picks a pokemon
- Compares selected stat and outputs a winner

### Planning stages

TICKET: Build basic HTML page
- Input box for player name ✅
- Input box for player choice ✅
- Button to set the whole thing running ✅
- Area to output results ✅

- STRETCH GOAL: Put a button by inputs to accept
- STRETCH GOAL: Show the stats of the two pokemon
- STRETCH GOAL: Prevent player from picking same pokemon repeatedly

TICKET: Capture player input
- Get the player name ✅
    - Input box ✅
    - Store it in a variable! ✅
- Get the player's choice
    - Input box ✅
    - Store it in a variable! ✅
    - Take in a player's choice ✅
        - VALID NAME: needs to be in lower case ✅
        - Handle API "not found" if player player picks non-existent pokemon 

    - STRETCH GOAL: check against pokemon list to make sure is a valid pokemon? 
    - STRETCH GOAL: Drop down lists for other stats?

TICKET: Fetch API & Match pokemon name to the one in the API data ✅
- Fetch request with URL and the function ✅
- Match pokemon name to the one inthe API data base ✅
- Get data back ✅
- Pull Attack stat out of json object ✅

TICKET: Generate computer input
- Find out how many pokemon are in the API to know max random number range ✅ 898 !!!
- Create (borrow!) randomiser for computer choice ✅ 

TICKET: Create comparison between two
- Compare strength between two pokemon (as an async function??) ✅
    - Boolean logic 
        - if greater than  win ✅
        - if equal is a draw ✅
        - else lose ✅

- STRETCH GOALS: Compare more stats!

TICKET: Output
- Store match total number games/wins/losses/draws in an object ✅
- Output this to webpage using querySelectors ✅
- Inform player of win/loss/draw
    - Pop-up alert box
    
    - STRETCH GOALS: js style the page (change colour etc?)
- Display totals on webpage

STRETCH GOAL: TICKET CSS GORGEOUSNESS
- Style the page 
- Show pretty pictures of the chosen pokemon! 
    - sprites:front_shiny