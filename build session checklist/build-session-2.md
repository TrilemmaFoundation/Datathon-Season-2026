# Build Session 2 Checklist

[Handbook](../README.md) | [Microproduct Guidelines](../guidelines.md) | [Build Session 1](build-session-1.md) | [Build Session 3](build-session-3.md) | [Demo Video Guidelines](../demo-video-guidelines.md)

The goal of Build Session 2 is to turn your idea and data into a **working app that creates visible value**.

You have completed [Build Session 1](build-session-1.md): you have a real problem, you are the first user, the scope is buildable, and you have access to relevant data.

Bring that evidence and your existing GitHub repository into this session.

Now build one useful path from the problem to a result you can demonstrate.

## 1. Own the Idea

LLMs are very good at aggregating knowledge. They can help you dig deeply into an idea, understand unfamiliar topics, and implement a solution.

With a vague prompt, however, the first suggestion can be generic. Other people asking similarly vague questions may receive similar ideas. Accepting that suggestion immediately can leave you building something you have little reason to care about or use.

Your experience, evidence, and judgment should shape what you build.

### Write your brief before prompting

In your own words, write down:

- The specific problem you are solving and when you experience it
- A real example from your own experience
- The evidence and data that support the idea
- What existing alternatives leave unresolved
- The useful action or result your app should make possible

Use this brief to give an LLM specific context. Ask it to challenge assumptions, explore the idea more deeply, explain tradeoffs, and help implement the choices you make. Check its suggestions against your experience and the data you actually have.

Owning the idea means understanding why it matters and taking responsibility for its choices. A familiar idea can still be worth pursuing when you have a specific problem and a useful way to solve it; originality is not a requirement.

### Ownership checks

- [ ] I have written my brief in my own words before asking an LLM to develop it
- [ ] I can explain why this idea matters to me as the **N of 1** user
- [ ] I can explain what existing alternatives leave unresolved
- [ ] I can explain my key choices and connect them to my experience or evidence
- [ ] I have evaluated the LLM's suggestions rather than automatically accepting its first answer

---

## 2. Make the Demo an Easy Proof of Value

Work backwards from one real situation where you would use the app.

Your demo should follow a simple path:

**Problem → Action in the app → Visible useful result**

The app should speak for itself. Its purpose, the action to take, and the resulting benefit should be easy to understand from what appears on screen.

### No nested if statements in the demo story

“If we get more data, and if we add another feature, then this could help someone” is a chain of conditions for future value.

Show value that your app already creates. This is about the demo story, not a restriction on conditional logic in your code.

Where useful, show a simple before/after comparison: how you handled the problem before, and what the app now makes easier. A clear qualitative improvement is enough; you do not need a dollar figure or a measured time saving.

### Proof-of-value checks

- [ ] I can demonstrate one real situation where I would use the app
- [ ] The interface makes the app's purpose and useful result understandable
- [ ] The demo shows an action in the app and a result it actually produces
- [ ] I can explain how that result helps me solve the problem
- [ ] My claims are supported by visible behavior and the data used
- [ ] The value is clear without relying on hypothetical features or future users

---

## 3. Go from Data + Idea to a Static Frontend

A static frontend can be a working app. It can load prepared data and support browser interactions such as filtering, comparing, or exploring results without a live backend.

Start with the smallest real data slice that supports the useful path you want to demonstrate.

### Build one complete path

1. **Select the data.** Use a manageable slice of the relevant data you identified in Session 1. Confirm that you have permission to use it in the app, including any data made available to the browser.
2. **Prepare useful outputs.** Clean, summarize, or transform the data as needed for your idea. Save the relevant data or results in a form the frontend can load, such as a JSON file. These steps can happen before the app runs.
3. **Connect the interface.** Give the user a clear action and show the useful result using that data. Keep labels, units, and explanations clear enough to understand the output.
4. **Check the complete path.** Run the app locally, perform the action, and compare the displayed result with the underlying data. Confirm that the result helps with your original problem.

Use tools you can work with confidently. Keep the implementation focused on demonstrating the value you identified.

### Working-app checks

- [ ] My app uses real, permitted data relevant to my problem
- [ ] The displayed results are supported by that data
- [ ] The browser interactions needed for my demo work
- [ ] The output is clearly presented and useful to me as the first user
- [ ] I have checked one complete path from data through the app to a useful result
- [ ] My repository contains the files and instructions needed to reproduce the app locally

Deployment and broader user feedback are the focus of **Build Session 3**. For this session, a working local app is enough.

---

## Build Session 2 Exit Condition

By the end of the session, you should be able to say:

> **I own the idea and can explain my choices. I have a working local app that uses real data, and I can demonstrate a useful result for myself as the first user without relying on hypothetical future features.**

That is what you should take into Build Session 3, where the focus shifts to putting your product in front of other people.

---

## Submission

Continue using the **same GitHub repository** you submitted for Build Session 1.

Update your `README.md` with concise documentation covering:

- Your idea and the choices you made
- The data you used and how it supports the useful result
- How to run the app locally, including any data preparation steps
- The demo path: the situation, the action to take, and the expected result
- What works now and what remains before Build Session 3

Keep your current code, required data or permitted access instructions, and documentation in the repository so mentors can follow your progress.

We will check back in roughly **24 hours after the session** to see how your build has progressed and provide feedback through GitHub Issues.
