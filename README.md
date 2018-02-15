```
  /$$$$$$            /$$       /$$        /$$$$$$            /$$          
 /$$__  $$          | $$      | $$       /$$__  $$          |__/          
| $$  \__/  /$$$$$$ | $$$$$$$ | $$$$$$$ | $$  \__/  /$$$$$$  /$$ /$$$$$$$ 
| $$       /$$__  $$| $$__  $$| $$__  $$| $$       /$$__  $$| $$| $$__  $$
| $$      | $$$$$$$$| $$  \ $$| $$  \ $$| $$      | $$  \ $$| $$| $$  \ $$
| $$    $$| $$_____/| $$  | $$| $$  | $$| $$    $$| $$  | $$| $$| $$  | $$
|  $$$$$$/|  $$$$$$$| $$  | $$| $$  | $$|  $$$$$$/|  $$$$$$/| $$| $$  | $$
 \______/  \_______/|__/  |__/|__/  |__/ \______/  \______/ |__/|__/  |__/


                === PROOF OF WORK ERC20 EXTENSION ===
 
                         Mk 1 aka CehhCoin
   
    Intro:
   All addresses have CehhCoin assigned to them from the moment this
   contract is mined. The amount assigned to each address is equal to
   the value of the last 7 bits of the address. Anyone who finds an 
   address with CEHH can transfer it to a personal wallet.
   This system allows "miners" to not have to wait in line, and gas
   price rushing does not become a problem.
   
    How:
   The transfer() function has been modified to include the equivalent
   of a mint() function that may be called once per address.
   
    Why:
   Instead of premining everything, the supply goes up until the 
   transaction fee required to "mine" CehhCoins matches the price of 
   255 CehhCoins. After that point CehhCoins will follow a price 
   theoretically proportional to gas prices. This gives the community
   a way to see gas prices as a number. Added to this, I hope to
   use CehhCoin as a starting point for a new paradigm of keeping
   PoW as an open possibility without having to launch a standalone
   blockchain.
