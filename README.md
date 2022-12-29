# Object_Oriented_Programming_1

presenters: 

            elad laster 208968636

            david stern 315556308
            
subject: 
          
            Send updates with Observer(a disin pattern) and track object size in Heap.

## observer

The observer pattern is a software design pattern in which an object, called the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods(by wikipedia).

There are times when users will want to receive information from a certain site (for example: a news site, social networks, promotions and discounts from any site and more ...), for this they will have to go to the site where the information is available and ask him if it has been updated recently again and again until it really happens, in order to streamline the process - since it will cause a load on the site and waste time, We want to find a design pattern that will allow us to do it efficiently and quickly.

The Observer is a design pattern that enables updating all users of the site by adding them to the list of those registered to the site and updates directly in any update that is made on the site.


## classes

GroupAdmin:

In order to unite all users who want to receive updates from the group, we will build the group that will serve as our "update center" and in which the changes in the information will occur, we also want every update we make to automatically reach the registered members of the group.
We will do this with the help of the "Register" function in which we will put the interested user in a list of users. We will then be able by the functions we have built in UndoableStringBuilder to change the information in the "Update Center".
to each function we will attach the command function "Notify" and with its help we will send the updates to all the members in the list of records.

ConcreteMember:

Tests:
