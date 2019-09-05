# Console Team Clean Code Principles (Draft)
> Here are some coding principles referenced from a book called Clean Code.

### Meaningful Names
* use intension-revealing names, such as appendNewGroupsToDefaultCustomerDimension(...)
* distinguish names in such a way that the reader knows what is the difference
* class name should be noun or noun phrase, methods should have verb or verb phrase, ex) deleteAccount
* avoid mental mapping, for example, instead of writing _.each(users, u => u.balance + 3), leaving _.each(users, user => user.balance + 3) in the codebase
* pick one word for one abstract concept and stick with it, for instance, if you always use the word `get` for GET request, just use getXXX, instead of fetchXXX

### Functions
* functions should be very very small, no more than 10 lines
* functions should do one thing and they should do it well

