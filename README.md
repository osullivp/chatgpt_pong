# chatgpt_pong
A version of Pong created using ChatGPT

The aim of this project is to create an HTML/Javascript version of Atari's Pong using just ChatGPT (as far as possible). ChatGPT 3.5 was used which is the free version available via https://chat.openai.com/ at the time of writing (early May 2023).

The prompt used was as follows:

> Give me the code for an HTML5/javascript version of the Atari videogame 'Pong'. The game should include a bouncing ball and two vertically orientated 'paddles' which are positioned on the left and right sides of the screen.

Key findings:

- ChatGPT generated the entire code for an initial simple version of Pong with a single prompt. However this implementation needed amendments as for instance the collision detection routine was quite naive and failed to handle a number of edge cases.

- Also, without quite a deep knowledge of collision detection it was hard to eliminate all of the bugs. For instance, a user would need to know about 'Axis Aligned Bounding Boxes' and also to be able to properly describe the issues encountered.

- However, ChatGPT was very helpful when it came to adding features i.e. displaying scores and FPS as well as improving the keyboard handling code

In summary, ChatGPT saved time with the setup of the initial project and adding new features. However, the bulk of development time (larger than 80%) was taken up resolving bugs and in this case ChatGPT proved less helpful. In some ways it hindered bug fixing as the focus was on describing the issue to ChatGPT and trying multiple incorrect suggested 'fixes'. It may have been more productive to have reverted to first principles in these cases and building a solution from scratch.


