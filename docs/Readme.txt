Hey there!
Ready to be rocked by another awesome entry by Kenji?

Simple drop the class, component and visualforce page into your org. They should work right out of the box.
The code is heavily commented so you can easily tweak it and understand what the hell I was thinking.

One cool feature of my app that is above and beyond the requirments is that you can specify the fields that are searched to find records.
Normally it might only look in the name field of an object to see if it matches what a user has typed, but you can control what
fields are searched (any non numeric field at least). Also, it uses easy jQuery selectors to make fields into lookups, so you
you can easily create a large number of lookups at once. To create an autocomplete field all you need to do is simply assign the 
autocomplete class (the default one) to a lookup field.

In the component you can specify which object to search against (the type of objects that lookup field represents) and the fields
to search for. That is all the config that is required. 