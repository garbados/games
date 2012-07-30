CAPTAINS OF INDUSTRY: Everything Has Its Price
This document uses a variable X, which is considered to be the maximum number of players, to determine the game's size and the effects of various cards.

	Deck Contents
	X Labor
		Yield $X minus the number of Labor in play.
	X Tools
		Your Labor yields $1+
	X Land
		Yields $Y, where Y is the number of players, minus the number of players with Land in play.
	X Cultivation
		Your Land yields $1+
	X Bank (Finance)
		Yields $ for every $2 you have.
	X Rarities (Finance)
		Yields $X/2.
	X Politics
		Propose a rule. Other players bid on whether it becomes law or not. You receive the winning bid.
	X Events
		[NOTE: the number of types of events must equal X]
		Strike
			Play for free, without taking an action, in response to someone taking the Work action. 
			Labor yields nothing this turn.
		Disaster
			Play for free, without taking an action, in response to someone taking the Rent action. 
			Land yields nothing this turn.
		War
			Play for free, without taking an action, in response to someone taking the Trade action. 
			Finance yields nothing this turn.
		Sabotage
			Play for free, without taking an action, after a player plays a card.
			Discard the card just played.
		Ruin
			Target player shuffles half of their Land back into the deck.
		Plague
			Target player shuffles half of their Labor back into the deck.
	
	Deck size
		Number of Cards = 8X
		Due to the use of X/2 values, X must be even.
		X	Total
		6	42
		8	64
		10	80
		
	Tokens
		Tokens represent capital, or money, also written as $ in CoI.
		X(X-1) $ tokens
		X xX tokens (as in, if X=6, there would be 6 x6 tokens)
		Total Tokens: X**2
		Max Capital: X**3 - X**2
		Capital to Win: X(X-1)
		X	Total	Max $	Win $
		6	36		180		30
		8	64		448		56
		10	100		900		90
			
	Actions
	V1
		On each player's turn, they choose an action by placing $1 on it, and putting $Y into the general stockpile, where Y is the amount of capital already on the action. If, for example, Draw has $2 on it, taking Draw would cost $3. Once they've taken their action, the player passes the turn. A player cannot pass the turn without taking an action.
		Note: When a player runs out of capital under these rules, they lose. To prevent such a fate, capital-strapped players may consider selling their assets to avoid defeat. When a player loses, any assets they still possess are shuffled back into the deck.
		5 Actions
			Invent
				Draw three, pick one, place the others back on top of the deck. Other players may buy from you the right to draw a card.
			Invest
				Play a card from your hand. Others may then buy the right to also play a card.
			Work
				Labor yields capital. Others may buy the right for their Labor to also yield capital.
			Rent
				Land yields capital. Others may buy the right for their Land to also yield capital.
			Trade
				Finance yields capital. Others may buy the right for their Finance to also yield capital.
	V2
		During each players turn, they...
		Invent: Look at the top card of the deck. You may then put it into your hand, or auction it off.
		Invest: Play a card. Others may bribe you to play one of their cards instead.
		Profit: Pick a type of asset: Land, Labor, or Finance. Your assets of that type yield capital. Others may pay you for a "partnership" where their assets of that type also yield.
	V3
		As V1, but actions cost nothing.
	
	Terminology
		Assets: cards
		Capital: $
		General stockpile: wherever unpossessed capital hangs out
		Yield: generate capital from the general stockpile
		Active player: whoever's turn it is at the moment (Consider renaming to Captain?)
		
	Rules
		Win/Loss Conditions
			Win: Accumulate $X**2
		Starting resources
			Players begin the game with $X and X/2 cards.
		Who Goes First
			Players bid on who goes first, with the winning bid going to the player who goes last. Turn order proceeds clockwise by default, so the last player would be to the first player's right. If no one bids to go first, pick a player at random.
		Taking Actions
			See Actions, above.
		Bidding
			Everything in the game can be bought, sold, and traded, whether that means assets, turn order, who rules affect, etc.
			Rules can be generated or altered through Politics cards, and can be nullified by consensus (with certain consenting votes possibly having been purchased) at any time, whether forever or on a one-time basis.
			Effects from events can be nullified by bribing the player who played the event.
			Each player controls who goes after them, and can thus buy and sell that position -- but not to themselves.
		Discarding Events
			Rather than hold a discard pile, events are shuffled back into the deck after they're used.
		Rarities and Banks
			When finance assets yield capital, Banks yield first, thus ignoring the yield of Rarities in calculating their own yield.
