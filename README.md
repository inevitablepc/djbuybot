# djbuybot
For Radio NIgel's DjBuyBot, a telegram (for now) bot to track crypto buys and report whenever there is a purchase. Should you have any questions or like to get in touch with the team to get your Token/Nigelcast potentially featured, hop on over to https://t.me/NigelsforNigels.

**How to use**

You can first add it on your telegram group by finding @djbuybot on telegram and additing it as an administrator so it has access to your messages (This will be useful).

It only works for PancakeSwap and BSC tokens for now. If you like to include more tokens/Dexes/Chains, please submit a request at our telegram group above.

**Commands** (Ignore <> chracters when typing out the commands)

intro - Say hi to the Nigel's Dj Bot!  
/intro


add_token - Add the token {token} you want to track.  
/add_token <token_address>


remove_token - Remove the token {token} you want to track  
/remove_token <token_address>


set_min - Set minimum amount to track in BNB  
/set_min <token_address> <min_amt>


set_step - Set emoji count per step. Default is 0.1  
/set_step <token_address> <min_amt>


set_emoji - Choose which emoji you like  
/set_emoji <token_address> <min_amt>


set_gif - Set token, min_buy and reply to a gif. You can possibly have multiple gifs and it will select the one cloest to the amount.  
/set_gif <token_address> <0.5>


show_marketcap - Send token to show marketcap. Either turn it on or off. Need to set supply first before showing marketcap.  
/show_marketcap

set_supply - Set total circulating supply for marketcap. Make sure to consider decimals.  
/set_supply <token_address> <supply>


remove_gif - Remove gif for set min_buy amount  
/remove_gif <token_address> <min_amt>


spin_a_nigelcast - Choose a random NigelCast to play for your guests.  
/spin_a_nigelcast
