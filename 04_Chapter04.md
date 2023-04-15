# Chapter 4: Negotiating Prices with Vendors 

Welcome back to our Flea Market Follies book series where we explore the chaotic and exciting world of flea markets. In the previous chapter, we uncovered some of the most common items found at these markets. We hope that you had the opportunity to put what you learned into practice and discover some unique treasures of your own.

Today we are thrilled to introduce our special guest, the queen of negotiating deals, Barbara Corcoran! Barbara is a successful entrepreneur and investor who knows a thing or two about closing a deal.  Her expertise in the world of business has made her a trailblazer for many women in male-dominated fields. In this chapter, we'll delve into some of the techniques that Barbara has used in negotiation situations and how you can utilize them when bargaining with vendors at flea markets.

One of the most alluring aspects of flea markets is the thrill of discovering hidden gems for a great price. However, you may find that some vendors have higher prices for their items than others. Don't let this deter you from making an offer. Negotiation is an essential aspect of flea market shopping, and vendors expect it.

Our first technique is to start with a lower offer than the asking price. In order for this technique to be successful, you must be willing to walk away from the deal. This creates a sense of urgency for the vendor and may cause them to reduce their initial price.

```python
def negotiate_price(initial_price, lower_offer_amount):
    offer = initial_price - initial_price * lower_offer_amount
    if offer < initial_price:
        print("Making an offer of $" + str(offer) + ".")
        return offer
    else:
        print("Sorry, that offer doesn't work for me.")
        return initial_price
```
    
Our second technique is to use charm and humor to establish rapport with the vendor. According to a study published in the Journal of Personality and Social Psychology, people are more likely to agree to a request from someone they like. So, make small talk, compliment their items, and joke around a bit. This creates a friendly atmosphere and may make the vendor more willing to negotiate on price.

Lastly, if you happen to be buying multiple items from a vendor, don't be afraid to ask for a package deal. Many vendors are willing to give you a better price if you are purchasing more than one item.

```python
def calculate_package_price(item_prices):
    return sum(item_prices) - sum(item_prices) * 0.1

item_prices = [10, 15, 20, 25]
package_price = calculate_package_price(item_prices)
print("The total package price is $" + str(package_price) + ".")
```

In conclusion, negotiating prices with vendors is an essential skill in the world of flea market shopping. With Barbara Corcoran's techniques and our code snippets, we believe that you are well equipped to close the deal on your next unique find. Happy shopping!
# Chapter 4: Negotiating Prices with Vendors - The Bargaining Monster

Deep in the heart of a bustling flea market, a monster was born. It was no ordinary monster, however. This creature was made of their most ruthless bargaining tactics whipped up in a laboratory in the dead of the night.

The Bargaining Monster was as tall as a man, with a head full of curly hair and a mouth as silver as the stars in the night sky. He roamed the flea markets, haggling prices with vendors until he won.

People spoke about his tactics; the way he made jokes and compliments to break the ice, how he'd start with a ridiculously low price, and they watched as he walked away from deals that didn't meet his expectations.

One day, Barbara Corcoran arrived at the flea market. The Bargaining Monster was nervous, she was known for her negotiation skills, and he worried she might put him out of business. 

Barbara quickly caught wind of The Bargaining Monster and beckoned him over. "Let's make a deal," she said, "I heard you're a fierce negotiator. Let's have a little competition, you verses me."

The Bargaining Monster was hesitant; he had never challenged anyone before, let alone Barbara Corcoran, but he accepted the challenge.

It was a fierce battle, but Barbara Corcoran's charm and wit proved too much for the monster to bear. She called him out on his lowball offers, raised counter-offers and used her sharp tongue to close the deal.

In defeat, The Bargaining Monster thanked Barbara for teaching him new techniques, and the two parted ways, but the lessons didn't go to waste. The monster improved his negotiation skills and became more successful than ever.

Today, you too, can learn from Barbara and the Bargaining Monster's story. Remember to start with a low offer, but be prepared to walk away, use charm and humor as rapport builders, and always ask for a package deal when buying multiple items. With these skills, you'll be a powerful bargaining monster, just like the one who roamed the flea markets.
## Code to Resolve the Frankenstein's Monster Story

In the Frankenstein's Monster story, we described how The Bargaining Monster used various tactics to negotiate prices with vendors at the flea market. In this chapter, we also highlighted some famous negotiation techniques used by Barbara Corcoran, which could assist you in becoming a better negotiator. Let's break down the code snippets we used to illustrate these techniques. 

### Technique 1: Starting with a Low Offer

The first technique utilized by The Bargaining Monster is starting with a low offer. It is an effective strategy for opening negotiations, but it is important to be prepared to walk away from the deal if things don't go according to plan. Here is the Python code we used to demonstrate this tactic:

```python
def negotiate_price(initial_price, lower_offer_amount):
    offer = initial_price - initial_price * lower_offer_amount
    if offer < initial_price:
        print("Making an offer of $" + str(offer) + ".")
        return offer
    else:
        print("Sorry, that offer doesn't work for me.")
        return initial_price
```
In this function, the initial price of an item and how much you want to reduce the price by, called the *lower_offer_amount*, are passed as parameters. The function then calculates the offered price by subtracting the initial price by the lower offer amount percentage of the initial price. If the offer is less than the initial price, the function returns the offer; otherwise, the initial price is returned, and the vendor has the choice to accept or refuse the offer.

### Technique 2: Building Rapport with Humor and Charm

The second negotiation technique is creating a friendly and comfortable atmosphere with the vendor by using humor, small talk and compliments. Here's some Python code that potentially identifies how to create a discounted price based on vendor friendliness:

```python
def calculate_package_price(item_prices):
    return sum(item_prices) - sum(item_prices) * 0.1

item_prices = [10, 15, 20, 25]
package_price = calculate_package_price(item_prices)
print("The total package price is $" + str(package_price) + ".")
```
Let's say you want to purchase a few different items from a vendor, using small talk and humor can help create rapport with the vendor. By establishing a friendly tone, you're more likely to receive a satisfactory deal. Utilizing a package pricing model is another great way to help build camaraderie with your vendor. The above Python code returns the total package price of a list of items, reduced by 10 per cent. The package price is an excellent way to incentivize the vendor to sell you multiple items at a better price.

In conclusion, with the code samples above and the background context provided in the previous sections, we hope that you take these lessons and employ them next time you embark on a flea marketing adventure to ensure you get the best deals possible. By following the negotiating strategies laid out by The Bargaining Monster, Barbara Corcoran and our contents above, you'll soon become a bargaining master.


[Next Chapter](05_Chapter05.md)