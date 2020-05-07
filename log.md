# 100 Days Of Code - Log

### Day 2: May 5, 2020

**Today's Progress**: Got Redux Sagas working for adding a new item to a wishlist, and wrote my own hook (using react-use) to refresh the wishlist when an item is added.

**Thoughts:** Redux is making more and more sense to me the more I work with it.  Go figure!

### Day 3: May 6, 2020

**Today's Progress**: Got Redux sagas working for deleting an item from a wishlist.  Pulled that custom hook into its own file and I suspect I'll be making more.  Wishlist entry form now renders a loading spinner after you click the button, and then re-renders the form once the action has been completed.

**Thoughts:** Consistency in naming is important, I spent way more time than I needed to tracking down a problem that boiled down to `remove` vs `delete` in method and object names.  D'oh!
