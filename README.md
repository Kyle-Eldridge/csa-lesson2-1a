# Urban Explorer

Embark on a thrilling urban adventure with Urban Explorer! Your virtual passport to the world's greatest sights, this nifty tool sorts cities alphabetically, making your dream destinations just a click away. Let's turn your wanderlust into a wonder-list!

**Goal:** Implement a method to sort the list of cities.

## Using Copilot as the Navigator

**Step 1:** Enter this prompt in the chat to prime Copilot to act as the navigator:

> Can you act as a pair programmer for me while I work on this project? I'm going to write some code and periodically, I'll ask you to help check that I'm on the right track. You can ask me questions and give suggestions, but don't give me solutions.

**Step 2:** Write your code to complete the program. Every **1-2 minutes**, check in with Copilot like you would if your navigator was one of your peers. For example, you could:

   * Ask what step you should do next

   * Get feedback on your solution so far, such as to see if there is a better way to write the code you've written

   * Check if you have any syntax or logic errors or suggest fixes

   * Make sure that your code will solve the problem

Either as you go or after you are done writing your program, answer the following questions to reflect your experience using Copilot as the navigator.

**What did Copilot do well as the navigator?**

It gave me a way to solve the problem using less code than the way I had before, which was:
   cities.sort((City c1, Cityc2)->{
      return c1.getName().toLowerCase().compareTo(c2.getName().toLowerCase());
   });
It gave me the code for what it is now.

**What did Copilot struggle with as the navigator?**

It gave me solutions, even though I told it not to. Also, it could only see the file I was in, so it couldn't tell me what the whole program did.

**What challenges did you face while working with Copilot as the navigator?**

Installing it.
