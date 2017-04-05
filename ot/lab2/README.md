# Laboratory work nr. 2

### DeadLines (DLs)
Group 1: May 2nd, 01:00 GTM+2

Group 2: May 2nd, 01:00 GTM+2

### Grading system
- just one problem -> all or nothing


## Problem description

You suddenly hear the awesome news that your grand-grand-uncle's cousin, that left to Nigeria a long time ago, has left you with quite a piece of land in the wonderful Telenești area near Budăi (total area is about 1,2 sq. km). You, a huge fan of linear programming, have built this map in order to see things more clearly.

At some point you have decided to grow some crops on this field. Upon consulting the specialists, you arrive to the following options:

- Each 0.1 sq. km of land (not forest) needs 200 lei/month to be taken care of
- Each 0.1 sq. km of the forest costs 100 lei/month for its care
- Keep in mind that you have limited territory for forests! Measure it! Note: Consider that you pay these two at the end of the year out of the profits.
- At least 0.5 sq km of the forest needs to be kept
- You can invite hunters into the forest. The estimated profit there is around 20K lei/sq.km/year
- The potato seeds cost you 100 lei/sq. km
- From each 0.1 sq km of the field you can collect 1 ton of potatoes
- Potatoes can be farmed twice a year.
- A potato tractor costs 500lei/sq. km (It collects your potatoes)
- A ton of potatoes can be sold on the market with 2K lei
- You can also make wine (of course!). Grape seeds cost you 800 lei/sq. km. For simplicity, let’s consider that it’s a yearly investment. (You kill all the grape plants each year)
- Each 0.1 sq. km of land can give you 2 tons of grapes / year
- The people that collect the grapes need to be paid (there’s no wine yet). They ask for 5000lei/sq. km
- You can make 400 litres of wine with 1 ton of grapes
- The wine is sold at 6 lei/litre

Unfortunately, although your kind uncle gave you the land, he didn’t give you the money, so you put together three months worth of student’s scholarships (a total of 1500 lei) and set out to create the greatest farming empire Budăi has ever seen.

Considering that you’re a fan of linear programming, how do you go about organizing this area? What will you farm and how much of the area will you farm?

Using your result, develop a simulation that will show your income over time. Use per-year estimations to develop your method. How will this method change if you consider that you won’t have to put the grapes in again each year? How will this change considering that you will pay the grape collectors 2 times less, but give them 100 liters of wine instead?

## Note

The penalties for passing the DL are as follows: 
- from your mark it will be subtracted ceil(weeks(submission_date) - weeks(dl_date))
