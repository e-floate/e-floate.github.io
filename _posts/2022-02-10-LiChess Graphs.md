---

---
A selection of graphs from a LiChess data study:

## White Rating (Normalized) by Opening Type

![White Rating (Normalized) by Opening Type](/assets/images/Opening_Type_v_Rating.png "White Rating (Normalized) by Opening Type")

- It appears the higher rated players tend to play E openings (Indian Defences such as King's Indian or Nimzo-Indian)
### If you are facing a higher level player, try playing an opening they are less likely to be familiar with, like a C type opening (open games and the french defence)
- (For more about opening types see: <https://en.wikipedia.org/wiki/Encyclopaedia_of_Chess_Openings>)

## Number of turns taken by match result

![Number of turns taken by match result](/assets/images/Turns_Dist_by_Result.png "Number of turns taken by match result")

- This suggests that when a game moves past (approximately) the 75 move mark it is likely that game will end in a draw
- It also shows that games where Black wins tend to last slightly longer than games where White wins, perhaps due to the fact that White moves first 
- Very few games reach the 150 move mark, and those that do almost always draw
### If you are avoiding a draw, try to keep the game to around the 50 move mark, if you want a draw, drag out the game as much as you can

## White rating (normalised) by number of turns in the opening phase

![White rating (normalised) by number of turns in the opening phase](/assets/images/Opening_Moves_v_Rating.png "White rating (normalised) by number of turns in the opening phase")

It should be noted that the way the LiChess analysis engine determines the end of the opening and the beginning of the middle game is not precisely known, but some contributing factors seem to be:
- Whether either player is castled.
- Whether there are 10 or fewer pieces on the board.
- The development of pieces in general.