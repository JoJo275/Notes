# 📝 Process Questions

This document outlines a series of questions that can be relevant while working through a program (e.g., software development, project management, reviewing code). These questions help **clarify objectives**, **identify challenges**, and **ensure team alignment**.

## ❓ General Questions

1. What is the **primary goal** of this program?
2. Who are the **key stakeholders** involved?
3. What are the major **milestones and deadlines**?
4. What **resources** (time, budget, personnel) are available?
5. How will **success be measured**?

## 🧩 Planning and Design

1. What are the **key features and functionalities** required?
2. How will the **user experience** be designed?
3. What **technologies and tools** will be used?
4. Are there any potential **risks or challenges** identified?
5. How will **changes to the plan** be managed?

## 🛠️ Development and Implementation

1. What is the **development methodology** (e.g., *Agile, Waterfall*)?
2. How will tasks be **assigned and tracked**?
3. What is the process for **code reviews** and **quality assurance**?
4. How will **communication** be maintained among team members?
5. What is the plan for **deployment and release**?

## 📊 Evaluation and Feedback

1. How will **user feedback** be collected and analyzed?
2. What **metrics** will be used to evaluate success?
3. How will **lessons learned** be documented and shared?
4. What is the process for **ongoing maintenance** and support?
5. How will the program be **adapted** based on feedback and changing needs?

## 🔍 Before Writing Any Code — Understanding the Problem

**This is where real programming begins.** Code is just the final step.

- Do I **fully understand** what the program needs to do — *inputs, outputs, and constraints*?
- What problem am I **actually solving** — and what would **success look like**?
- Have I defined **edge cases** (*empty inputs, large data, unexpected user behavior*)?
- Can I explain the problem clearly in **plain English** or **pseudocode** before touching the keyboard?
- Am I **reinventing the wheel**, or does a reliable library/framework already exist for this?
- What's the **simplest way** to achieve this result? (*Simplicity beats cleverness.*)
- What is the input, and what is the exact expected output?
- Can I describe the problem in plain English (or pseudocode) before coding it?
- Have I broken the problem into smaller, manageable parts?
- What’s the simplest possible version I could build first (MVP / prototype)?
- Have I checked if a built-in function or library already solves this?

💡 “If you can’t explain what the code should do in words, you can’t write it correctly.”

## 🧠 While Designing the Solution

Think about **how** to structure your logic.

- What **data structures** make this problem easier (*lists, dicts, trees, etc.*)?
- What **algorithms** fit best, and what's their **time and space complexity**?
- How will this code **scale** with more data or users?
- Could I break this down into **small, reusable functions** or modules?
- What are the **assumptions** I'm making, and are they safe?
- If someone else reads this code, would they **understand the logic quickly**?

## 💻 While Writing Code

Here you focus on **clarity**, **maintainability**, and **correctness**.

- Am I writing code that is **readable first**, *fast second*?
- Do my variable and function names **describe what they do** clearly?
- Is there any **repeated code** that could be refactored into a function?
- Am I using **meaningful comments** or letting the code be **self-explanatory**?
- Is this the **simplest working solution**, or am I *overengineering*?
- Will **future me** (or a teammate) understand this without context?
- What **errors might occur** — and how will my program **handle them**?
- Am I **validating user input** and preventing crashes?
- Is this code modular, or is everything tangled together?
- If I change one part, will it break something else?
- Am I coding for correctness first or cleverness first (and why)?

💡 Readable beats clever — especially when debugging your own work later.

## 🧪 While Testing & Debugging

**Great programmers constantly test assumptions.**

- Does this code handle **edge cases** correctly (e.g., *0, null, empty lists*)?
- Have I written **unit tests** for critical logic?
- Am I testing both **valid and invalid** inputs?
- What happens if the environment or file system behaves **unexpectedly**?
- When I find a bug, do I **understand why** it happened, or just patch it?
- Can I **reproduce the issue** consistently before fixing it?
- Does the fix introduce **new side effects**?
- What exactly is happening versus what I expected to happen?
- Where’s the first place the program’s behavior diverges from my expectation?
- Have I tested the smallest possible piece of the program that fails?
- Can I reproduce the bug consistently?
- What are the assumptions I’m making — and have I verified them?
- Have I read the error message carefully (and Googled only after understanding it)?
- Did I recently change something that could affect this area?

💡 Debugging is not fixing mistakes — it’s investigating assumptions.

## ⚙️ While Optimizing or Refactoring

Once it works, make it ***beautifully efficient.***

- Which parts of the code are **slowest** or most **memory-heavy**?
- Is this optimization **worth the added complexity**?
- Can I replace manual loops with **built-in methods** or libraries?
- Have I **profiled the program**, or am I *guessing* performance bottlenecks?
- Can I **simplify logic** without losing clarity?
- Does the new version **pass all previous tests**?
- Is my solution efficient enough for real-world input sizes?
- Are there unnecessary computations or nested loops I can simplify?
- Can this code handle invalid or unexpected input gracefully?
- Have I written at least minimal tests to verify it works over time?
- Is my code secure and free from obvious vulnerabilities?
- Have I cleaned up temporary print statements or debug code?
- Would this code still make sense to me in three months?

💡 “It works” is step one — “It’s solid” is the real goal.

## 🔍 Before Committing / Submitting — Communication

- These help ensure professionalism and maintainability.
- Have I left helpful comments explaining why, not what?
- Did I write a clear commit message describing the purpose of the change?
- Have I followed consistent indentation and style guidelines (PEP 8, etc.)?
- Would I be proud to show this code in an interview or portfolio?
- If someone else reads this, could they use or modify it confidently?

## 🤝 While Integrating or Collaborating

Programming isn't just solo — think **team and environment**.

- Does my code **fit into the larger system** cleanly?
- Have I followed the team's **style guides** and **naming conventions**?
- Did I **document** new functions or APIs I created?
- Did I write **clear commit messages** describing *what changed and why*?
- Am I handling **dependencies and environments** safely (e.g., *virtualenv, package.json, requirements.txt*)?
- Could someone else **run my project easily** from a fresh setup?

## 🔎 When Reviewing or Reflecting

This is how you ***level up*** as a programmer.

- What did I learn from this project or bug?
- What did I struggle with, and why?
- Was my plan efficient, or did I waste time on the wrong parts?
- What part of this code would I refactor if I revisited it later?
- Did I document my learnings so future projects are smoother?
- What new concepts or tools could make this easier next time?
- What **habits or shortcuts** slowed me down?
- What **patterns** worked really well here?

💡 Every project is a lab experiment in making yourself a better engineer.

## 🧘 Mindset & Habits

These keep you **sharp**, **patient**, and **evolving**.

- Am I **curious** about *why* something works, not just *that* it works?
- Do I **read other people's code** regularly to learn new styles?
- Am I **balancing** learning new tech with mastering fundamentals?
- Am I writing code I'm **proud of**, not just *"code that runs"*?
- Do I **stop to refactor** when I see messy code — or keep piling on?

## 🧭 Bonus: Meta-Questions for Deep Thinking

For when you want to think like an **architect**, not just a coder:

- What **trade-offs** am I making between *simplicity and flexibility*?
- Am I solving the problem **today**, or trying to predict tomorrow's problems **too soon**?
- How would this design **scale** if *100× more data or users* existed?
- What **assumptions** about the environment or users does my code make?
- Could my approach be **generalized or reused** elsewhere?
