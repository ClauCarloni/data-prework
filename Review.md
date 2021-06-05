# Prework review

Hi Claudia 🙋🏻‍♀️!! I am writing to give you some feedback on your prework! 🚀

### 1. Snail-and-Well

Let's go with the snail!

- *Find the solution to the challenge using the variables defined above.*

    In this exercise you did't consider that the snail can get out of the well during the day, so... 

    ```python
    while snail_position <= well_height: #if the the snail position is less than the well_height
        days += 1 # sum a day in the counter
        snail_position += daily_distance # sum the distance it reaches
        if snail_position <= well_height: # if the snail is in the well, then we have to subtract what falls during the night
            snail_position -= nightly_distance
    ```
- What happened with the bonus??? Although they are not mandatory, it is important that we do them because they will help us to create more complex code and can be a challenge from which we will learn a lot.


### 2. Duel-of-Sorcerers

We go into battle! 

- In the exercise 4 *Who won the battle* the challenge ask us about  who win the battle, therefore we would have to compare the two lists we have created (gandalf_wins, saruman_wins), a possible solution could be:
    ```python
    if gandalf_wins > sarumann_wins:
        print("gandalf wins")
    elif gandalf_wins < saruman_wins:
        print("saruman wins")
    else:
        print("Tie!")

    ```

### 3. Bus

Good job in this challenge Claudiaaaa! 

### 4. Robin-Hood

Go with Robin hood challenge! 

- In the first exercise *Robin Hood is famous for hitting an arrow with another arrow. Find the coordinates of the points where an arrow hits another arrow.*
    ```python
    arrow_convergence_points = [] #create an empty list to strore the not repeted hits
    for coordinates in points: # iterate through list of tuples. Each coordinates will be a tuple with given point
        if coordinates not in arrow_convergence_points: # if the points are not in the empty list created before we add this item in the list
            arrow_convergence_points.append(coordinates)
        else:
            print("this point is in the list")
    ```
The other exercises are perfect Claudia! Very good job on this part!
### 5. Temperature-Processor

Good job using list comprehension Claudia 👏🏽🔥. In the absence of the bonus this challenge is perfect.

### 6. Rock–Paper–Scissors

Do you had any problems with this exercise? If you didn't understand something, let us know and we can look at it together!

In any case Claudia, very good job on the prework, you have achieved the basic objectives of these exercises, familiarize us with the main Python tools and lose the fear of coding. 🚀
