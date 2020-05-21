# 100 Days Of Code - Log

### Day 13: May 20, 2020

**Today's Progress**: Had a couple of interviews and didn't feel great.  Clearly dynamic programming is a weak spot for me, and I was being too clever (again).  Need to spend more time practicing on HackerRank and the like while I've got interviews in the pipeline.

**Thoughts**: Some days are just bad days.

### Day 12: May 19, 2020

**Today's Progress**: Cleaned up the Wishlists controller a lot.  Decided to allow multiple wishlists per user, but each user will have a default wishlist.  Learned about double-rendering and the dangers of being too clever.  Tomorrow I will have to figure out how to handle the Wishlist Items controller now that the resource is within the Wishlists resource.

**Thoughts**: I definitely have to keep the walking skeleton metaphor in mind, and I have to avoid cleverness for now.  Just get the thing working in the first place, then add in elegance and cleverness.  

### Day 11: May 18, 2020

**Today's Progress**: Learned about nested resources and understood more about the example controllers I've seen.

**Thoughts**: Definitely need to think more about the Wishlist vs User relationship.  Do I want to have multiple Wishlists per User?  Do I want to screw around with visibility and which Users can see which Wishlists?  Or just one Wishlist per User, and in that case, why have a Wishlist model at all?  Need to think more.

### Day 10: May 13, 2020

**Today's Progress**: Today was very busy, so I didn't get much coding done.  I did get started on being able to view friends' wishlists, and returning different details on wishlists depending on who's viewing.

**Thoughts**: Starting to get away from JBuilder, which was used in the tutorial I followed most closely.  I want more centralized control over what's being rendered.

### Day 9: May 12, 2020

**Today's Progress**: All my coding was spent on a coding exercise for a job I want.  Code does what I want, but it could have used more tests.  (It can always use more tests.)

**Thoughts**: Wow am I rusty on plain Ruby.  Rails is a rather different beast!  Didn't realize how much of a difference frameworks, and how ubiquitous that difference is.

### Day 8: May 11, 2020

**Today's Progress**: Made a user relationships table and added the ability to add and destory (ha!) user relationships.

**Thoughts**: The stuff I followed from the tutorial makes a _lot_ more sense now.  Nothing like breaking something to learn how it works!

### Day 7: May 10, 2020

**Today's Progress**: I think I understand react routing a bit better now.  Maybe.

**Thoughts**: Need to actually decide on UX before I make any more frontend changes.  In the meanwhile I'm going to work on adding friends and associated visibility on the backend.

### Day 5: May 9, 2020

**Today's Progress**: More typing, think I've mostly got it.  More Material UI work.

**Thoughts**: I friggin love types.  This exercise of converting my Redux/Saga code to TS has definitely helped my understanding of Redux too.

### Day 4: May 7, 2020

**Today's Progress**: Converted Redux/Sagas bits to Typescript, as well as some components.  WishlistDisplay isn't ready yet though because I need to get better typing in ReduxHooks.

**Thoughts**:  I am really glad I'm doing this now and not later.  Converting to TS is a pain.

### Day 3: May 6, 2020

**Today's Progress**: Got Redux sagas working for deleting an item from a wishlist.  Pulled that custom hook into its own file and I suspect I'll be making more.  Wishlist entry form now renders a loading spinner after you click the button, and then re-renders the form once the action has been completed.

**Thoughts:** Consistency in naming is important, I spent way more time than I needed to tracking down a problem that boiled down to `remove` vs `delete` in method and object names.  D'oh!

### Day 2: May 5, 2020

**Today's Progress**: Got Redux Sagas working for adding a new item to a wishlist, and wrote my own hook (using react-use) to refresh the wishlist when an item is added.

**Thoughts:** Redux is making more and more sense to me the more I work with it.  Go figure!
