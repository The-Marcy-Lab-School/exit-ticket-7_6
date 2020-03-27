# Lesson 7.6 Exit Ticket
### Entity Relationship Modeling

## Directions
* Read the following article on [Entity Relationship Diagrams - Crow's Foot Notation](http://www2.cs.uregina.ca/~bernatja/crowsfoot.html).

* Follow the subsequent steps to create a ERD using Crow's Foot Notation. We will be building a hypothetical model of [Yelp](https://yelp.com).
   1. Yelp is a system. As we've learned, systems are comprised of _entities_. List as many entities of Yelp as you can think of.
   2. Choose any **four** connected entities. First, in shorthand notes, describe the relationship between these interconnected entities.
   3. Use [draw.io](https://draw.io) to construct an ERD using Crow's Foot Notation for the four entities you selected.
   4. In `erd.md`, describe your ERD in clear, concise sentences. Be sure to explain the reasoning behind each set of relationships in your diagram. Strong responses will use the phrases _has one_, _belongs to_, _has many_, and _belongs to many_. Be sure to export your diagram as a PNG file and include the photo in your markdown file.

## Yelp Hypothetical Model

**1. Possible Entities:**
- Businesses
- Users
- Reviews
- Photos

**2. Quick Relationship Notes**
- Users can own businesses (1 user, 1 business)
- Users can post photos (1 user, many posts)
- Businesses have many reviews (1 business, many reviews)
- Users have one or no review for any number of businesses

**3. EDR**

![Image]('./ticket-7-edr.png', 'Diagram')

**4. EDR Description**
- A user has a `1 to Many` relationship with a business where to own a business there must be at least 1 user, but a user can have no businesses.
- Similarly, a user has a `1 to Many` relationship with a review, of which they can have none or many, but each review only has one user.
- One review can also have one or no photos, but photos need a single review in which they live
- Businesses have this same relationship with reviews, as they can review other businesses (see above for review) but can also hold any number of pictures, where all pictures just have one business in this context.
