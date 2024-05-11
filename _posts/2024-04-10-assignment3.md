---
title: "Assignment 3"
---

In approaching the Spatial Data Assignment, I was initially overwhelmed by the variety of sources available for selection. Having worked primarily with directories where the data is neatly classified and easy to access, it was a significant shift to tackle sources that weren't structured in the same way. I switched my source multiple times, trying to find one that would align with my interests and make sense for the assignment. Ultimately, I settled on *Fielding's Travel Guide to Europe*. I was drawn to the idea of studying a travel guide from a time long before digital travel apps like Booking.com or TripAdvisor existed. This historical perspective intrigued me, as I imagined how travelers of earlier decades relied on such guides for their adventures across Europe.


However, working with the guide wasn't straightforward. Unlike directories, it didn’t have a clear layout, so finding relevant data was tricky. Instead of being organized, all the information was in long paragraphs of text. To make it easier, I decided to focus on one country: France. This way, I could narrow down the data without being overwhelmed.

Even within France, the guide covered a wide range of travel needs, from restaurant recommendations to car rentals and shops. To further streamline my work, I opted to focus exclusively on hotels. The travel guide offered rich descriptions of various accommodations throughout France, providing details on specific cities and their notable hotels. Some hotels even had additional information, such as reviews, features, and the quality of service. This data was particularly useful because it provided clear and consistent geographic information, forming a good foundation for my dataset.

In the second step of the process, I needed to model the data into a usable format. At first, I attempted to collect and classify the information manually, assuming the dataset would be manageable given the limited number of hotels. However, by the time I reached the eleventh hotel, it became clear that the scope was much larger than anticipated, and a manual approach would be too time-consuming. I turned to ChatGPT for assistance in extracting the information more efficiently. By crafting specific prompts for classification, I could extract the spatial data, such as hotel names and their respective cities, much faster and with fewer errors. It was fascinating to see just how many hotels were reviewed by the author, giving me a deeper appreciation of the meticulous travel research conducted during that era.

![Alt Text](/assets/images/tableimage.jpg)

With the data extracted, I moved on to enrich it by adding relevant metadata.  The table presents accommodations across various French cities and regions, offering a snapshot of their distinctive features and quality. Some accommodations are classified as "excellent" or "good" for their superior amenities and prime locations, while others are deemed "fair" or "poor" due to limited facilities or declining standards. The table provides a structured overview for travelers seeking guidance in choosing suitable places to stay, catering to diverse preferences and budgets. These additional attributes gave a clearer picture of the distribution and quality of accommodations across different regions of France.

![Alt Text](/assets/images/mapimage.jpg)

To visualize the data, I used kepler.gl and batchgeo.com , a versatile tool that allowed me to map the hotel locations and categorize them by city, using different colors to represent each area. This visualization revealed interesting patterns, showing clusters of highly-reviewed hotels in popular tourist destinations like Lyon and the French Riviera. Additionally, smaller but high-quality hotels appeared in less-traveled regions, hinting at hidden gems for travelers willing to stray off the beaten path.


Overall, this assignment provided valuable insights into travel trends and the ways in which historical data can reveal patterns that might still be relevant today. For future, I would expand my scope to cover additional pages and explore other countries to create a more comprehensive map of European travel recommendations from that era. This would reveal larger trends and perhaps highlight changes in travel patterns over time. Fielding's Travel Guide proved to be a good source, offering a view into a past where travel guides were the authoritative resource for explorers of the world.

