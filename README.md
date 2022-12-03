# Tintin-nuggets
Things I've written for tintin++ to make life easier


Files:
speedwalk.tin
 Needed some more flexibility for the built-in tintin++ speedwalking capabilities. This alias will detect your command if it's in the format of: 
  {number}{command}{number}{command}..
 Where there are at least 2 instances of {number}{command} and no spaces
 
 Example: 12n25nw will execute n 12 times and nw 25 times. tintin++ can do this but it doesn't behave to my liking by default since it often times defaults to the speedwalking 'v1' style - which would execute n 12 times, n 25 times, and w once.
 
 The {command} is limited to words with no special characters. You could do 2smile3grin for example.
