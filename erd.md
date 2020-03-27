
The ERD ccreated is on "Yelp" using crowsfoot. This shows the relationships between a user, a review, a business, and a category.

The relationship between a user and a business is displayed by using a zero or one and a zero or many crowsfoot. I decided to use this because on yelp a business page belongs to either no user or one user. While a user can have either one or many business pages on yelp.

The relationship between a user and a review is displayed by using a mandatory one and a zero or many crowsfoot. I decided to use this because a review belongs to one user, while a user can have zero or many reviews.

The relationship between a review and a business is displayed by a zero or many and a mandatory one crowsfoot. It's displayed like this because zero or many reviews can belong to one business. While one business can have zero or many reviews.

The relationship between a category and business is represented by a many to many crowsfoot. This is displayed like this because a business can belong to many categories. Like wise a category can have many categories.