# 16/10/2-18

I had a problem were I cannot convert a transform to a variable I created. It turns out I declared the variable to `vector 3`, then I made the mistake again by declaring it as `GameObject`. The code ran after I declared it as `Transform`.

# 23/10/2-18

I had a problem again with converting `GameObject` to `Rigidbody`, I got confused of when to convert and from which way to convert to. In the end I figured it out. My second problem was the object spawn really fast, I fixed it by making the script wait half a second befor spawning again. My third problem was that is spawn the object forward, my intention was to make the object launch upward. I fixed i by adding velocity on the correct axis. 
