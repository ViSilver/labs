# Laboratory work nr. 5

### Deadlines
Group 1: May 28th, 02:00 GMT+2

Group 2: May 28th, 02:00 GMT+2

### Grading system
For every problem you solve you get a score. At the end you add the score to 5 to get your grade.
- 1.1 - 0.5
- 1.2 - 0.5
- 1.3 - 2
- 1.4 - 0.5
- 1.5 - 0.5
- 1.6 - 1

## 1 There is only one problem
You have a set of 20 people connected via a friendship matrix. The whole list is
given in [list.txt](https://github.com/ViSilver/labs/blob/master/aux/list.txt/?raw=true).

### 1.1 Friends
Find the person with the most friends.

### 1.2 Sort
Sort all the people by the number of friends.

### 1.3 Let's do ratings

How to do that? Well, each person in the graph is connected to everyone
else at some level. Therefore, each person will have a list of connections which
is as long as the total list of people in the graph (in our case, 20). You then
have to compute the *shortest path* from each of the nodes to each of the other
nodes.

For example, let’s say that you found that from node 0 you can reach to
node 3 in 5 steps (that is, the shortest path connecting nodes 0 and 3 has 5
steps). That means that node 3 will be a connection of level 5 to node 0 and
will therefore contribute to 0 with 4 points.

As a procedure, you can take each item *n* and then compute the distances
between *n* and all the other vertices of the graph. You can use these distances
to compute the value that is added by each of the other *n − 1* vertices to *n*.
Sum it and you’ll have the value of vertex *n*.

In order to find the shortest path between two vertices, you’ll have to use the
*Dijkstra’s algorithm*. You can find a plenty of implementations of that algorithm
online.

Compute the points for each person in our network. Let’s call
it ”Rating”

### 1.4 Influential people
Let’s say that each of these people has a certain rate of posting content. Obviously,
people who communicate more are much more influential. Suppose that
you need to promote a new brand using the social media. We found out how
often each of these 20 people writes something on their walls. You can find it in
[influence.txt](https://github.com/ViSilver/labs/blob/master/aux/influence.txt/?raw=true).

Whom of these people will you contact? Why? Be advised that not only
the frequency of posting matters, but also the number of friends!

Use the data from the previous exercise and find the new ”Rating” for each
person by multiplying it with 0.5 of the posting rate.

Please sort the people by the newly computed rating.

### 1.5 Analyze your content
You are publishing a book and would like to promote it through the use of social
media. The book’s title is ”From T-Rex to Justin Bieber: How Internet has
changed the Politics, Art and cute Cats” You have done some research in the
world’s most popular social network and have found that the range of interests
is stored in [interests.txt](https://github.com/ViSilver/labs/blob/master/aux/interests.txt/?raw=true).

Analyze your title and see what specter of interests is your book marketable to.

### 1.6 Promote it
We have provided you with a list of interests of each of these people. You can
find it in [interests.txt](https://github.com/ViSilver/labs/blob/master/aux/interests.txt/?raw=true).

Considering the set of interests you have chosen, who of them would you
market the book to? Let’s say that a person has 5 of her interests coinciding
with your book’s and she has a Rating of 346. Multiply her rating with the 0.2 * coinciding interests to see a final score. Sort the people by this final score.

Provide us with a list of 5 people we should contact to make
your book a bestseller! Please use the names found in [people_interests.txt](https://github.com/ViSilver/labs/blob/master/aux/people_interests.txt/?raw=true)
