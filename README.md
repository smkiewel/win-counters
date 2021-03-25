# win-counters
This is a simple HTML and Javascript applet to track my win/loss record over a gaming session of Magic the Gathering: Arena. 

The deck you are playing with is selected by a the slideout panel. This decklist is a permanent list, as each time a deck is added or removed, I use localStorage to save a JSON representation of the decklist. Adding a deck is as easy as just typing in its name and hitting either the button or just hitting enter, whereupon it will be added to the list and a counter for that deck automatically created. 

There are three always present counters: and All-day counter, an All-day All-ranked, and an All-day All-play. The All-day counter will keep track of all games, regardless of the mode you chose in the game. The All-ranked shows total in ranked games for the day, while the All-play shows the total in games played just for fun. 

Once you have selected your deck from the decklist and added the counter, you're ready to go. Just hit the Win or Loss button to record the result of the game, and all relevant counters will update. If you mistakenly hit the wrong button, that is easily remedied by using the undo feature, which is right below the plus icon to get to the decklist. All actions are stored, so you can undo all of your wins and losses, if you so feel like.

Do note that the styling on this page is not responsive and has static heights for certain divs. This is to ensure that it fits in my stream window correctly.
