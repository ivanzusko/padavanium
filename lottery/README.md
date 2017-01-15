# Lottery

## Task
You will create lottery random winner detection.

### Markup
On the very top there should be readonly `input` (with **placeholder** "Winner's name is...") and button `New Winner`.

Than Registration form with next fields:
1. First name*
1. Last name*
1. Email*
1. Phone
1. Date of birth
Field marked with `*` are required.
On the bottom of the form there should be `Save` button.

On the very bottom there should be table with created players.

### Logic

After filling data in the form and press `Save` button, newly created player should appear in the table below.
- Form should be cleared after that.
- There is no limits to maximum amount of players.

After clicking the `New Winner` button, you need to get random winner from the players table and place his name into `input`.

If there already exist winner, it should be cleared, the new one should appear in the winner `input`, and the previous one should be shown in the winners list above the winners `input`.

## BONUS LEVEL: Would be great to see
1. Front end validation for all fields;
1. possibility to edit player's information directly in the table
1. some sort of responsiveness (when the browser window get resized);


**P.S.**
*And please... no __jQuery__ :)*
