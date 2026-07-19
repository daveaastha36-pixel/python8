1.
Create a Python list called order_amounts with the values [120, 250, 90, 310, 150]. Use a for loop to calculate and print the total order value.

***answer***
# List of order amounts
order_amounts = [120, 250, 90, 310, 150]

# Calculate total
total = 0

for amount in order_amounts:
    total += amount

print("Total Order Value:", total)

2.
Given a list of cricket scores [45, 78, 102, 34, 67, 89], use a while loop to print each score until you reach a score above 100, then stop printing.

***answer***
# List of cricket scores
scores = [45, 78, 102, 34, 67, 89]

# Initialize index
i = 0

while i < len(scores):
    if scores[i] > 100:
        break
    print(scores[i])
    i += 1

3.
Simulate a Flipkart cart with a list of item prices [299, 499, 199, 999, 149]. Use a for loop and the continue statement to skip any item priced below 200, and print the total of the remaining items.

***answer***
# Flipkart cart item prices
item_prices = [299, 499, 199, 999, 149]

total = 0

for price in item_prices:
    if price < 200:
        continue
    total += price

print("Total of items priced ₹200 or more:", total)

4.
You have a list of favorite song names: ['Kesariya', 'Believer', 'Shape of You', 'Blinding Lights', 'Excuses']. Use the enumerate() function in a for loop to print each song with its playlist position (starting from 1).

***answer***
# List of favorite songs
songs = ["Kesariya", "sun raha hain na tu", "barbadiyaa", "ghum hain kisikey pyaar mein", "ishaqzaade"]

for position, song in enumerate(songs, start=1):
    print(position, "-", song)

5.
Write a for loop that goes through a list of Instagram follower counts [120, 1500, 23000, 800, 45000] and prints 'Micro', 'Influencer', or 'Celebrity' for each, based on the following: Micro (<1000), Influencer (1000-10000), Celebrity (>10000).<br><br><em><strong>Hint:</strong> Use if-elif-else inside the loop to check the follower count range.</em>

***answer***
# List of follower counts
followers = [120, 1500, 23000, 800, 45000]

for count in followers:
    if count < 1000:
        print(count, "- Micro")
    elif count <= 10000:
        print(count, "- Influencer")
    else:
        print(count, "- Celebrity")

