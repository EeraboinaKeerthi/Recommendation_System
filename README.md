# Recommendation_System

User Preferences ---> Recommender System ----> Recommendations(We can know user's future predictions)

User preferences:
1. Explicit feedback: example: giving ratings
2. Implicit feedback: example: how long you are listening to music or how many times did you buy something etc.

3. Two most important approaches to recommendation systems are:
   
   **Collaborative Filtering:**
    Collaborative filtering is based on the premise that "similar people like similar things".
    Recommends items based on the preferences and behavior of other users.
    Types:

   User-based: Finds users similar to you and recommends items they liked.

   Item-based: Finds items similar to what you liked and recommends those.

   Example:
If Alice and Bob both liked the same movies, and Bob liked a new movie that Alice hasn’t seen, the system might recommend that movie to Alice.

   Pros:

   No need to understand item content.
   
   Learns from user behavior patterns.

    Cons:

    Cold start problem (new users or new items).
   
    Sparsity in data (not enough user-item interactions).

**Context based filtering**
It tackles the cold start problem.

Recommends items based on the features of the items and the user’s past preferences.

"If you liked item A with features X, Y, Z, then you might also like item B with similar features."

Example:
If you watched action movies with Tom Cruise, it recommends other action movies or movies with Tom Cruise.

Pros:

Works well with fewer users.

Personalized to the individual user.

Cons:

Limited diversity (stuck in a “filter bubble”).

Requires detailed item metadata.

Collaborative filtering struggles with sparse data.

Content-based filtering works better with sparse ratings.
