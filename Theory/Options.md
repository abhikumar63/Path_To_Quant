Disclaimer: These notes are based on USA options.
Definition: The right (but not the obligation) to buy or sell stock, at an agreed upon price, on or before a particular date.
Basically it is a contract.
You can also sell an option contract, where you sell the right to someone at a premium.

### Two Types:
**Call option:** Gives the holder the right (but not the obligation) to ==buy== shares of stock, at an *agreed upon price* on or before *a particular date*.
**Put Option:** Gives the holder the right (but not the obligation) to ==sell== shares of stock, at an *agreed upon price* on or before *a particular date*.

Strike Price: The agreed upon price.
Expiration: A particular date

Layman Term:
Suppose you bought an call option.
Strike Price = 120
Expiration = 30 days from now

Owning this option will allow you to purchase the stock at 120 per share (strike price) anytime within the next 30 days (expiration date). No matter where the stock price is at.
So, if stock goes to 135 in the next 30 days, fortunately for you, you own a call option that allow you to buy stock at 120 even though the stock is currently trading at 135.

Instead of call, lets say you bought a put option. This will allow you to sell the stock at 120 anytime in the next 30 days, no matter where the price is at.
If the stock tanks to 100 per share, you own a put option that lets you sell at 120 even though the stock is at 100.

### Why to buy options?
**For Puts**
For a car, you purchase an insurance which protects your car financially in case of crash.
Same concept is for option.

Instead of car owner, you are an investor, you bought 100 shares of xyz company at $125/share.
Total = $12,500
Stocks can fall and even go to 0.
Therefore, Total risk = $12,500

Like insurance for car, we can purchase insurance for investment, by purchasing an option contract. Specifically, in this case a **PUT** option.
Insurance <-> Put Option
For buying an option, someone had to sell it to you. But who?
Any other trader who is willing to be paid to take on your risk.
So for example,
Bought 100 shares @125 = 12,500
Bought Put option = 500
(Prices of option depends on various factors, we will see that later)

Two cases might happen,
 1. Price goes from 125 to 132
	 7x100  Profit = $700
	 Option Contract(now has no value) = $500
	 Net Profit = $200
	 What a ripoff! Person who sold the option gets easy money.

 2. Price goes from 125 to 113
	12 x 100  Loss = $1200
	Now we have the contract, we go to the seller of the contract. Even though the option is at 113, you are able to exercise the option to sell shares at $125/share.
	So, Loss = 0
	Option Contract = $500
	Net Loss = $500
	Better than 1200, if didn't bought the option.

The person who sold the option, is obligated to purchase your shares at $125 per share.
They got $500 and also 100 shares @ 125, where the CMP (Current Market Price) is 113. They can sell or hold. If they sell, their net loss would be $1200 - $500 = $700.

Therefore, Options = Insurance

You can also trade options without even owning the particular share. They can be traded just like shares from the brokerage account based on the price fluctuation.

Buy Put option = Buy Insurance
Sell Put option  = Sell Insurance

**For Calls**
Let's say you don't own any share of stock yet. But you have eyes on a particular stock, only problem is its expensive. To invest it would require a lot of capital.
So, Instead of buying stock, you could buy a call option. This will allow you to buy a small premium for the right to buy the shares at a later date. If perhaps you are correct and the price goes higher:
e.g. XYZ 
CMP = $125
To buy 100 shares = $12,500
Instead,
Buy 125 call option with 30 days to expiration -> Price will depend on several factors, for now lets consider $500
This gives the right to buy 100 shares at $125/share anytime during the next 30 days.

Two cases might happen:
1. Stock goes from 125 to 135, you own 125 call.
	Exercise the call option.
	You now own 100 shares @ 125/share
	12x100 profit = $1200
	Call option = $500
	Net Profit = $700
	For less investment, you get somewhat less profit.

2. Stock goes from 125 to 100
	You had 125 call option -> right to buy @ 125.
	But why would anyone do that if CMP is 100.
	You wouldn't, and you don't have to if exercised you would be down 25x100 = 2500 + the option at 500
	Total Loss = $3000
	But, you don't have to exercise, you simply lost the option premium = $500
	If you only bought the stock @ 125, you would be down $2500.
	Benefit of buying an option vs buying stock
	Less capital <=> Less Risk

You can also trade Put option in the same way without owning the stock.
Buy a put option => betting the stock will go down.
If you exercise you right to sell stock that you don't own then you end up with a short position.

Therefore,
Buy Call -> Betting the stock will go UP
Buy Put -> Betting the stock will go DOWN

We do not always have to exercise options when you trade them. you can simply buy and sell them at higher price.

## Option Chain
List of options with prices for different expiration
Buy on Ask price
Sell on Bid price

Stock trade in share, Options trade in Contracts.
1 Contract = 100 shares ( for US )

To purchase 1 contract, how much would it cost.
If Ask price = 2.81
Cost will be $281 (2.81 x 100)

Prices fluctuate, Suppose it goes to 4.00 and we decide to sell, so total sell price is 400
Total Profit = $119

But how does an option's price changes??

## Option's Price


3 factors that affect the option's price
1. Price of the underlying stock
2. Time to expiration
3. Volatility