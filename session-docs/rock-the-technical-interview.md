# Sync: How to rock the technical interview

> **Presenter: @Scott Reu** > **Homework:** Find a partner and practice a mock-interview

## Resources

- [Slides from presentation](https://docs.google.com/presentation/d/14qR6zen010IKlQA7QeZCqp7f282KvmVge1xHq0xWQ4w/edit?usp=sharing)

## Rocking the behavioral aspect of your technical interview

**Have a clear or organized background:** Having clutter in the background behind you can reduce the attention of the interviewer and already create a negative impression of you in their minds. We don't want this. All attention should be on you during the interview.

**Have good lighting:** It is important to sit next to a window with good lighting or to have good lighting in your room.

**Look smart**: Even though it is a technical interview, it is important to look smart. You don't need to wear a suit and tie, but you don't want to come underdressed as well. Dress smart.

**Share your screen:** When the interviewer gives you a live challenge to do, remember to share your screen so that they can see what you are doing.

**Share your camera positioning:** If you have two screens and are looking away from your interviewer, make sure to let them know the reason why. This will definitely be beneficial to both of you.

**Mute your phone:** This is essential in any interview.

If you would like to learn more tips, here are a few links to help you:

[18 tips to help ace a Zoom interview](https://www.indeed.com/career-advice/interviewing/zoom-interview)

[10 tips to crush your Zoom interview](https://careerprotocol.com/zoom-interview-tips/)

## Rocking the technical aspect of your technical interview

**Building contextual awareness of the main focus of the interview via your recruiter** In most cases, your recruiter will prepare you with a list of people and general overview of what you will be covering. This is helpful and can allow you to do a couple of things:

1. Build out your plan of attack for studying
   There's so much to study! Algorithms, data structures, computational complexity! Do **_not_** focus on cramming **all** the things. One strategy is to brush up on the foundations of things you're really strong at, and study the items that you need to pick up on in order to speak to their purposes, use cases, and how you may have used them in the past (or how they may be used with something you know well).
2. Build out your strengths and areas for growth
   This will be useful in one of the next tips we cover (how do you admit you don't know something?), but also allow you to optimize for types of questions you ask as you go along.
3. Develop the questions you'll have for each member
   Since you have a general idea of what each person does by which interview session you have with them, you'll be able to have a good sense to prep some general topics for conversing with your interviewer. Have one question that's important to you in your back pocket for each interviewer you will be meeting with.

**How will I know I can build this awareness?** Recruiters will provide the information on your interview panels in a couple of ways. The most direct way is by giving you a schedule and resources, like an org chart or an overview of engineering at the company, to understand the engineering organization better. If you find that this isn't proactively offered, you can ask if they can provide you the names of the people you'll be interviewing with and the focus for each interviewer.

**The actual interview session** Remember that interviewing is a two-way street! You are there to ask questions as well. Your job is not to be perfect, it's to _be you and display your communication, collaboration **and** technical skills!_

1. **Comments/Notes are your friend!** If you are using a platform where you have an online coding environment, use it like a whiteboard! Detail your notes and thoughts as you work on the challenge in code comments - this is like a blue book in math class, as it allows you to "show your work". Many interviewers are not looking for just the speed of a solution, but _how_ you get to the solution.
2. **Comment before you code!** Use your comments to pseudocode before you start writing hard code! This is the first step to understanding exactly what you're building here. And it allows you to ensure you understand what's being asked of you so you can then...
3. **Ask clarifying questions!** Make sure that you understand the question, ask the interviewer for an example, and if they provide one before you ask, make sure to add one example of your own to verify that you have a good understanding of the problem you need to solve. You may be expected to discuss and discover any edge cases as well.
4. **Gut check your solution!** Talk through your solution before you write any code, you can write pseudo code / comments to make sure you don't forget anything Once the interviewer agrees that you are onto a good path, start coding in your choice of programming language.
5. **If you're writing code, write it like code!** If you're using a coding environment, _use proper coding standards!_ Use your Collab Lab and other experiences to fuel how you name your variables, functions and other parts of the code. You don't have to start with a perfectly architected, multiple file approach, but code your solution with a rough idea of improved code structure as you go.
6. **Tests - how many of us have them!** Even if they don't bring it up explicitly, discuss acceptance criteria and testing! You may not have to write unit tests, but you should be able to form a general opinion on how to test the code you write. You should make sure you have a clear definition of done, as well as steps to ensure your code meets that mark.

Andrew's off-the-cuff thoughts:

- There's so much to study! Algorithms, data structures, computational complexity! How do I know where to focus?
- Should I admit when I don't know something?
- What questions should I ask the people interviewing me?
- What are things I should look/listen for to gauge whether the company will provide me the support and resources I need to succeed?

Indira's notes:
Some steps of things to do while you are doing the interview:

1. Make sure that you understand the question, ask the interviewer for an example, if they provide one before you ask, make sure to add one example of your own to verify that you have a good understanding of the problem you need to solve.
2. Ask clarifying questions, sometimes the interviewer provides intentionally incomplete content to make sure that you are asking the right questions, think about edge cases, and confirm the expected behaviors for those (think empty string, null values, same values ... )

3. Talk through your solution before you write any code, you can write pseudo code / comments to make sure you don't forget anything

4. Once the interviewer agrees that you are onto a good path, start coding in your choice of programming language.

5. Make sure to talk while you are writing your code why you are doing what you are doing while you write the code, which requirement the code you are writing satisfies.

6. Look at your code again and see if there is any area for improvement, maybe you added variables that you ended up not using, think of it as your self-review of a pull request you did in the collab lab.

7. Walk through an example of the ones you established in step 1, either provided by the interviewer or you and walk line by line, and add how each of the variables are changing on each iteration. Some people suggest using a table with all your variables and listing what each of them are. You may need to make some updates while you are doing this (think of off by one type of errors)

8. If you are able to run the code (CoderPad) then this is the point where you think about running the code after you went line by line on what everything was supposed to be.

## Rocking the situational aspect of your technical interview

**When's the last time you were faced with \*\***\_\_\_\_\***\*?** Hypotheticals can be scary, but always stick to the "spirit" of the question, and not the literal. Think of how situations you've been in, technical AND non-technical, in your career that illustrative dealing with this challenge

**[Whiteboard] System Design and Resilience** You may get asked to describe how you would solve a certain challenge, and diagram it out on a whiteboard or in chat. Say you're discussing building a set of react components that also are used to fetch data across a front-end app. What are some typical challenges you may face? What have you faced? How would you solve them?

Example: API returns 503s to one of your data fetching components - how would you design your component to handle that error and still result in a useable interface?

Example: You're building APIs in nodejs, and the scenario presents that a server has gone down. Think of all the possible ways that could happen, and based on your experience, you could solve it.

## Rocking the "Manager Sell" of the Technical Interview

So you've talked your way through various scenarios, you've coded up a code challenge or two, and you've rocked having a clear environment. Now comes the session where you talk to your manager or other leader.

Now, this conversation will be partially technical, but this is where you get to really understand how the team operates, straight from the leader/hiring manager who's accountable for your future team's success.

**They're here to sell you** This is the manager's opportunity to present their best case as to why you might want to join their team. Use this to your advantage to get some key questions answered.

**Understanding what success looks like for the role** You can ask some pointed questions to understand what would be expected of you, and what would be considered a successful joining of the company. For instance, you might want to ask if they have a clear 30/60/90 day plan for new hires, or what's their philosophy on onboarding buddies.

**Understanding what growth looks like for the role** In addition, you can get an idea of the resources you might be provided while talking with the hiring manager. You can ask about the career ladder, the rubric for engineering titles/levels, and what does growth look like on their team or in their division.

**What's challenging about the environment** Asking questions about things the manager would change, or improvements they wish they could implement, to get a fuller understanding of what challenges you might be walking into.

**Show them who you are** Here's where you really get to let your personality shine.
