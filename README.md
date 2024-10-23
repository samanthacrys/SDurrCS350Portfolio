# SDurrCS350Portfolio

1. "Summarize the project and what problem it was solving."

The two artifacts I chose were Milestone Two and the final project.

Milestone 2: This project was about solving the problem of reading a message, in this case on or off, using a buffer. The challenges was ensuring that it only read the message as a single byte and not using multiple bytes. When the message it received from this was either ON or OFF, it would turn the light on the board on or off.

Final Project/Project 1: the problem this was solving was using more than one peripheral from the board to read the temperature. When the temperature hit a certain point, the light would either turn on or off due to the information it received. This was being controlled by the I2C temperature sensor on the board, but also on the buttons that would either increase or decrease the temperature. This had the additional problem of creating a task scheduler that would check on the temperature in order to know what tasks are being looked for and what states are being changed.

2. "What did you do particularly well?"

When it comes to what I feel I did particularly well, I feel that I did well in breaking down the problems and projects into smaller pieces so that I could see what components were necessary. This was apparent in the second milestone where I used a switch to create the state machine. In the final project, I felt that I did well in organizing the project in a logical manner. I read through the code, broke it down and figured out what components were where. By doing it this way, I was able to move some code from the main method into its own.

3. "Where could you improve?"

Creating State Machine documents and a little more understanding in how certain areas of the code work. While I was able to accomplish these later, I felt that I was missing information and wasn’t as clear as necessary. Since I could do the research and ask questions of people I know in the field, I had an advantage, but I still felt like I struggling or missing elements that I knew should have been there. The state machine document was the biggest, while I semi-figured it out later, I still feel as if I’m not doing well in those.

4. "What tools and/or resources are you adding to your support network?"

When it comes to tools/resources, I do find that I have some trouble answering this. This is mainly due to access to veteran computer engineers that I can speak to when my own searches haven’t helped. But I can say that a tool I am adding is more of a physical hardware view. Since this class uses the actual TI microcontroller, I can see the interaction of my work in real time and what is happening. Since most of what I’ve done in the past is on the computer fully, sometimes we don’t see the hardware interactions and that can be difficult. So being able to watch the hardware interaction is a tool that I intend to use to improve my own skills.

5. "What skills from this project will be particularly transferable to other projects and/or course work?"

A skill that I can take from these projects is the flow of the project. I can say that I have already applied that in a current side project that I am working on, which has increased the quality of my work. I am more easily able to see the smaller areas that may have been noticed only after bugs started appearing in my code. Having a larger awareness of how the program flows and the inner workings can help me in the future and that skill is one I will take with me.

6. "How did you make this project maintainable, readable, and adaptable?"

To make these projects easily adaptable, readable, and maintainable, I formatted the code in ways that would be understandable. I broke areas down into smaller components, such as moving al of the GPIO elements into its own method that is called in the main thread. I used comments that would make it easier to read the code and see where everything is located. I kept it simple enough that making changes would be easier. I also used appropriate labelling on my variables and method names. This allows for an easier time reading and figuring out what something does in case the comments are not read.
