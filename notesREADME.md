Game Logic - When the user clicks on the clicker, the total count of clicks goes up by 1. - When the user clicks on the "buy" button in an upgrade within the shop, the total count of clicks goes down by the cost of the upgrade and the CPS value goes up.
!!We will get the shop upgrades from the API!!
We will need actions to contain te game logic - each function will need a task, to create the logic for the shop upgrades; Option 1 - you could have a function to handle each upgrade or Option 2 - you could have a reusable function that works for all upgrades.
Tip - make sure the local storage values are updated after the user buys an upgrade when the user clicks for the clicker.

===============================================================================================================

let totalCookieCount = 0;
let cps = 0;

let stats ={
CookieCount: 0,
cps: 0,
};

If there is data already in the local storage, update stats with this data so the user picks it up where they left off.
shop upgrades - Fetch the shop upgrades from the API, Create multiple DOM elements to contain the upgrades (loop/s)

Creating DOM elements for the shop upgrades
Create Element - Assign the value to it's property - append it to the DOM - After you complete this task, you should see the upgrades in your shop container.

creat functions to handle the purchase action - The user needs a button to buy the item, When the user clicks the button - subtract the cost of the upgrade from the totalClickerCount and ass the increase value to the CPS, Save new values in local storage.

setInterval(function)({
totalClickerCount += cps; //totalclickercount = totalClickerCount + cps
//Update the DOM to refelct the changes in the vlaues - Save the values in local storage.
})
