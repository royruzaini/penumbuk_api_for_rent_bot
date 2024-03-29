# [Penumbuk Api ForRent BOT](https://penumbukapi.net/)

Rental Management Bot for Splinterlands cards.  
Based on [bauloewe post](https://peakd.com/splinterlands/@bauloewe/programming-tutorial-renting-your-splinterlands-card-collection-with-python).

# Feature

* Rent your unused cards automatically.  
* Get median market rent price from Splinterlands API by cards xp/bcx.  
* Median of cards with xp/bcx below 14 calculate with rent price more than 0.2 DEC.  
* Updating rent price minus 20% if still not rented.  
* Setup manual CP/DEC price at last 5 days and last 3 days of season.  
* Cancellation happen if new price is 50% higher than current price and if RC is more than 25%.  
* Best work with task scheduler.

# Installation

1. Download.

    ```sh
    git clone https://github.com/royruzaini/penumbuk_api_for_rent_bot.git
    ```
    
2. Copy all files in config folder to parent directory.

3. Replace the setting in those files with your information.

4. Run the exe file.

# Task Scheduler

1. Follow instruction [here](https://www.windowscentral.com/how-create-automated-task-using-task-scheduler-windows-10)

2. Recommended setting
    1. Main bot: At 12 AM every day - After triggered, repeat every 3 hours for a duration on 1 day

# Card_list

1. This is unique id(uid) of cards.
2. You can get the uid using export csv function in [PeakMonsters](https://peakd.com/hive-126911/@peak-monsters/updates-export-collection-low-price-vs-low-bid-and-more)

# Payment

* 10000 DEC per account, one time payment
* Visit [Penumbuk Api Website](https://penumbukapi.net/) to submit payment details.

# Security

1. Posting key
    1. It will use to login into the game.

2. Active key
    1. It will use for rent the cards.

3. Disclaimer
    1. The BOT will not sent over the posting/active key to me.
    2. Its will be use for above function only.