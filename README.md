# Clustering-Grocery_store

**Goal**
Look at user purchase history and create categories of items that are likely
to be bought together and, therefore, should belong to the same section(basically cluster the items).

Description
Company XYZ is an online grocery store which has a lot of data about user purchase history. Therefore, they would like to put the data into use!


**Challenges:**
• The company founder wants to meet with some of the best customers to go through a focus
group with them. You are asked to send the ID of the following customers to the founder:
o the customer who bought the most items overall in her lifetime,
o for each item, the customer who bought that product the most
• Cluster items based on user co-purchase history. That is, create clusters of products that have
the highest probability of being bought together. The goal of this is to replace the old/manually
created categories with these new ones. Each item can belong to just one cluster.


**Data**
The data contains two tables:
• "item_to_id" - for each item, it gives the corresponding id
• "purchase_history" - for each user purchase, the items bought
