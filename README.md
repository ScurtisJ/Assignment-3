--Product Search (6 searches)
Product ID: 40d3cd16b41970ae6872e914aecf2c8e, Name: Rubie's Child's Pokemon Deluxe Pikachu Costume, X-Small, Category: Clothing, Shoes & Jewelry | Costumes & Accessories | Kids & Baby | Girls | Costumes, Price: $29.12

Product ID: afef5d77b6049314aeb9c50421a2cee9, Name: Aquarius DC Wonder Woman Retro Playing Cards, Category: Toys & Games | Games & Accessories | Card Games | Standard Playing Card Decks, Price: $6.47

Product ID: 8b3ed216e8ea2a65feb8843e16e57217, Name: Craft-tastic – Kindness Kit – Craft Kit Includes 8 Projects to Inspire Kindness, Bilingual, Category: Toys & Games | Arts & Crafts | Craft Kits, Price: $19.99

Product ID: 8810d7ffdc995fd1905089cf090f2d5d, Name: Bendon Finding Dory Sticker Box, Category: Toys & Games | Arts & Crafts | Craft Kits, Price: $9.99

Product ID: 5b9175244eadc52976fd651d4e652ae8, Name: Schleich North America Tyrannosaurus Rex Toy Figure, Red, Category: Toys & Games | Toy Figures & Playsets | Action Figures, Price: $21.24

Product with ID aNonExistentProductID is not found.


Duplicate Product Insertion (ID: 37ed1450d4e14d6f886b36e6ce7305eb):
**ERROR** -- Product  ID 37ed1450d4e14d6f886b36e6ce7305eb already exists.

Product Insertion:
Product Addition: Product ID: Data Structures, Name: Toy Airplane, Category: New Category, Price: $93.12
Product Addition: Product ID: Computer Science, Name: Toy Car, Category: New Category, Price: $634.92


          Time Complexity of Operations in Red-Black Binary Search Tree (RB-BST)

          Search Operation Complexity:
            It has a Guaranteed complexity: 21 * log(N).
            This is due to traversal from the root, constrained by the tree's maximum height of 2 * log(N),
            which bounds the search complexity.

          Insert Operation Complexity:
          - Complexity: 2 * log(N).
            The traversal to the insertion point is limited by the tree's height (log(N)). Post-traversal,
            recoloring and rotations to maintain tree properties are constant time operations, maintaining
            an overall complexity of 2 * log(N).

          Deletion Operation Complexity (Not implemented in the assignment but included for completeness):
           - Complexity: 21 * log(N).
            Deletion operations also occur at the maximum tree height, with additional constant time
            operations for tree maintenance, similar to insertions.

          Average Case Complexities:
          - Search: log(N)
          - Insert: log(N)
          - Delete: log(N)
            These average cases assume the tree remains well-balanced through self-adjustments, meaning
            operations typically avoid the deepest paths, improving performance from the worst-case scenario.
         
