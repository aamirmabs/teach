---
marp: true
header: "**Open Day Workshop** | Computer Science, Software Engineering, Cybersecurity, AI & Networking"
footer: "**From Idea to Small System:** Python for Software Engineers"
paginate: true
theme: ugm
size: 16:9
---

<!-- _class: title -->

# From Idea to Small System

## Python for Software Engineers

**Live coding session – let's build something together!**

---

## Quick Poll 🎯

Question: _Where do you see code running in your daily life?_

A) Just on my laptop
B) Phones and apps
C) Websites and social media
D) Everywhere (cars, games, smart devices, etc.)

---

<div class="cols cols-2-eq">

<!-- column 1 -->
<div>

![](../shared/gifs/Coding-Software-Developer.gif)

</div>

<!-- column 2 -->
<div>

## What Do Software Engineers Actually Do?

</div>

</div>

---

<div class="cols cols-2-eq">

<!-- column 1 -->
<div>

![](../shared/gifs/Coding-Software-Developer.gif)

</div>

<!-- column 2 -->
<div>

## What Do Software Engineers Actually Do?

**Turns ideas into working systems that people use every day**

**Requirements** – What problem are we solving?
**Design** – How should it work?
**Code** – Build it with programming languages
**Test** – Make sure it actually works
**Maintain** – Fix bugs, add features, keep it running

</div>

</div>

---

## Let's Talk Money 💰

<div class="cols cols-2-eq">

<!-- wide column (2) -->
<div>

**UK Software Engineer Salaries (2026):**

| Experience                      | Annual Salary        |
| ------------------------------- | -------------------- |
| **Junior** (0-2 years)          | £28,000 - £38,000    |
| **Mid-Level** (2-5 years)       | £38,000 - £55,000    |
| **Senior** (5-8 years)          | £55,000 - £75,000    |
| **Lead/Principal** (8+ years)   | £75,000 - £100,000+  |
| **Staff/Architect** (10+ years) | £100,000 - £150,000+ |

</div>

<!-- narrow column (1) -->
<div>

**Manchester & Birmingham:**
10-20% above national average

**London: 30-40% higher**
(up to £150k+ senior roles)

</div>

</div>

---

## Why Should You Care?

| Benefit                    | Description                                            |
| -------------------------- | ------------------------------------------------------ |
| High starting salary       | Graduate roles £28k–£38k (above UK average)checkawage​ |
| Work from anywhere         | Remote/hybrid is standard                              |
| Job security               | Every company needs software engineers                 |
| Create real things         | Apps, games, websites people actually use              |
| Solve interesting problems | Not just sitting at a desk typing                      |
| Career flexibility         | Finance, healthcare, gaming, AI, cybersecurity...      |

**You're literally building the future.**

---

## Who Uses Python?

![center medium](../shared/gifs/python-snake-animation.gif)

---

## Who Uses Python? 🐍

| Company            | What They Use Python For                     |
| ------------------ | -------------------------------------------- |
| **Google**         | YouTube, Google Search, AI/ML                |
| **Netflix**        | Recommendation algorithms, data analysis     |
| **Spotify**        | Music recommendations, backend systems       |
| **Instagram**      | Entire backend (handles billions of photos)  |
| **Uber**           | Pricing, route optimization, fraud detection |
| **NASA**           | Data analysis, spacecraft control systems    |
| **PayPal**         | Payment processing, fraud detection          |
| **JPMorgan Chase** | Trading systems, risk management             |

---

## Python = Your Superpower Across All Degrees

| Degree                      | How Python Helps                                    |
| --------------------------- | --------------------------------------------------- |
| **Computer Science**        | Algorithms, data structures, theory → working code  |
| **Software Engineering**    | Building systems, testing, version control          |
| **Cybersecurity**           | Security scripts, log analysis, penetration testing |
| **Artificial Intelligence** | ML models, data analysis, neural networks           |
| **Networking**              | Network automation, traffic analysis, monitoring    |

**One language. Five careers. Infinite possibilities.**

---

## Poll Time 🎯

Question: _Which degree interests you most?_

A) Computer Science
B) Software Engineering
C) Cybersecurity
D) Artificial Intelligence
E) Networking

---

<!-- _class: lead -->

# Let's Build Something Real

## The Challenge: Simple Task Tracker

**Students need a console app to manage deadlines**

---

## Your Turn: What Features?

![center medium](../shared/gifs/ChooseArrowPudgyPenguins.gif)

---

## Your Turn: What Features?

_Vote for features you want (select all that apply):_

☐ Add a new task
☐ List all tasks
☐ Mark task as done
☐ Delete a task
☐ Set priorities (high/medium/low)
☐ Exit the program

**We'll code the top votes live!**

---

## Software Engineering Thinking: Break It Down

<div class="inline-images">

![left h:450](../shared/gifs/Architecture-Build.gif)

![right h:450](../shared/gifs/animation-art-city.gif)

</div>

---

## Software Engineering Thinking: Break It Down

**Before we write any code, let's design:**

```

┌─────────────────┐
│ main_menu()     │ ← The loop that keeps running
└────────┬────────┘
         │
    ┌────┴──────┬────────────────┬──────────┐
    │           │                │          │
┌───▼──────┐ ┌──▼────────┐ ┌─────▼─────┐ ┌──▼───┐
│ add task │ │list tasks │ │ mark_done │ │ exit │
└──────────┘ └───────────┘ └───────────┘ └──────┘

```

**Each box = one function** (does one job well)

---

<div class="cols cols-21">

<!-- column 1 -->
<div>

## SE Principle: Plan First

**Real software engineers don't just start typing!**

1. **Sketch** – Draw boxes and arrows (what we just did)
2. **Pseudocode** – Write logic in plain English
3. **Code** – Turn it into Python

**Good planning = less debugging later!**

</div>

<!-- column 2 -->
<div>

![](../shared/gifs/ObamaMakePlan.gif)

</div>

</div>

---

<div class="cols cols-12">

<!-- narrow column (1) -->
<div>

## Data Structure Thinking 🤔

</div>

<!-- wide column (2) -->
<div>

![center medium](../shared/gifs/Search-Engine-Ugh.gif)

</div>

</div>

---

## Data Structure Thinking 🤔

<div class="cols cols-2-eq">

<!-- column 1 -->
<div>

**Option A:** List of strings

```python
tasks = ["Finish coursework", "Study for exam"]
```

</div>

<!-- column 2 -->
<div>

**Option B:** List of dictionaries (more detail)

```python
tasks = [
    {"name": "Finish coursework", "done": False},
    {"name": "Study for exam", "done": False}
]
```

</div>

</div>

**How should we store tasks? Which is better? Why?**

---

<!-- _class: lead -->

<div class="cols cols-12">

<!-- column 1 -->
<div>

![](../shared/gifs/Nft-Coding.gif)

</div>

<!-- column 2 -->
<div>

# Live Coding Time! 💻

## Let's build this from scratch

</div>

</div>

---

## Starting Point: The Menu Loop

```python
# task_tracker.py

def main_menu():
    """Main loop - keeps program running until user quits"""
    tasks = []  # Empty list to store our tasks

    while True:
        print("\n=== Task Tracker ===")
        print("1. Add task")
        print("2. List tasks")
        print("3. Mark task done")
        print("0. Exit")

        choice = input("\nChoose an option: ")

        # We'll add the function calls here
```

---

## Function 1: Add a Task

**Let's code this together!**

```python
def add_task(tasks):
    """Add a new task to the list"""
    task_name = input("Enter task name: ")

    # Create a dictionary with task details
    new_task = {
        "name": task_name,
        "done": False
    }

    tasks.append(new_task)
    print(f"✅ Added: {task_name}")
```

**Notice:** Function takes `tasks` as input, modifies it

---

## Poll: Variable Naming 🎯

Which variable name is best for a task's completion status?

A) `d`
B) `done`
C) `is_completed`
D) `taskCompletionStatus`

**Hint:** Software engineers value _readability_

---

## Function 2: List All Tasks

```python
def list_tasks(tasks):
    """Display all tasks with their status"""
    if len(tasks) == 0:
        print("📭 No tasks yet!")
        return

    print("\n📋 Your Tasks:")
    for i, task in enumerate(tasks):
        status = "✅" if task["done"] else "⬜"
        print(f"{i+1}. {status} {task['name']}")
```

**Edge case:** What if list is empty? Handle it!

---

## Function 3: Mark Task Done

**Your turn to help design this!**

**Question:** How do we identify _which_ task to mark done?

A) By task name (user types the name)
B) By number (user types 1, 2, 3...)
C) Mark all tasks done at once

**Let's code the winner:**

---

## Function 3: Mark Task Done (Solution)

```python
def mark_done(tasks):
    """Mark a task as completed"""
    if len(tasks) == 0:
        print("📭 No tasks to mark!")
        return

    list_tasks(tasks)  # Show tasks first

    try:
        choice = int(input("\nWhich task number? ")) - 1
        if 0 <= choice < len(tasks):
            tasks[choice]["done"] = True
            print(f"✅ Marked done: {tasks[choice]['name']}")
        else:
            print("❌ Invalid task number!")
    except ValueError:
        print("❌ Please enter a number!")
```

---

## Connecting It All: Main Menu

```python
def main_menu():
    tasks = []

    while True:
        ...

        choice = input("\nChoose an option: ")

        if choice == "1":
            add_task(tasks)
        elif choice == "2":
            list_tasks(tasks)
        elif choice == "3":
            mark_done(tasks)
        elif choice == "0":
            print("👋 Goodbye!")
            break
        else:
            print("❌ Invalid choice!")

main_menu()
```

---

<!-- _class: lead -->

# Let's Run It! 🚀

## Live Demo Time

**Try adding tasks, listing them, marking them done**

---

## What Could Go Wrong? 🐛

**Poll: Spot the bugs!**

_What happens if..._

A) User types "abc" when asked for task number?
B) User tries to mark done when list is empty?
C) User enters blank task name?
D) All of the above could break it!

**Good news: We already handled A and B! 🎉**

---

## Software Engineering Magic: Refactoring

**Notice we print the menu in multiple places?**

**Before (duplicated code):**

```python
print("\n=== Task Tracker ===")
print("1. Add task")
# ... repeated everywhere
```

**After (DRY = Don't Repeat Yourself):**

```python
def show_menu():
    print("\n=== Task Tracker ===")
    print("1. Add task")
    print("2. List tasks")
    print("3. Mark task done")
    print("0. Exit")
```

**Now we just call `show_menu()` wherever needed!**

---

## SE Concepts We Just Used 💡

| Concept           | What It Means                        | Why It Matters            |
| ----------------- | ------------------------------------ | ------------------------- |
| **Functions**     | Break code into reusable pieces      | Easier to test and fix    |
| **Modularity**    | Each function does ONE thing         | Clear, organized code     |
| **Naming**        | Variables/functions have clear names | Anyone can read your code |
| **Edge cases**    | Handling empty lists, bad input      | Prevents crashes          |
| **DRY principle** | Don't Repeat Yourself                | Less code = fewer bugs    |

**These principles scale from 50-line scripts to 50,000-line systems!**

---

## This Tiny Example Scales Up 📈

**Our task tracker → Real industry tools:**

| Our Code           | Industry Equivalent              |
| ------------------ | -------------------------------- |
| List of task dicts | Database (PostgreSQL, MongoDB)   |
| Console menu       | Web interface (React, Flask)     |
| Functions          | Microservices, APIs              |
| Input validation   | Form validation, security checks |
| if/elif menu       | RESTful routing                  |

**Jira, Trello, Asana = fancy task trackers built on these ideas!**

---

## In Your Software Engineering Degree...

**Year 1:** Programming (Python, Java), data structures, algorithms, databases
**Year 2:** Software design patterns, web development, testing, team projects
**Year 3:** DevOps, CI/CD, cloud deployment, real client projects

**Tools you'll master:**

- **Version control:** Git, GitHub (track every change, work in teams)
- **Testing:** pytest, unit tests, integration tests (automate quality checks)
- **CI/CD:** Automated deployment pipelines (push code → tests run → deploy)
- **Cloud:** AWS, Azure, Docker (run your code anywhere)

---

## Tools You'll Use Here 🛠️

**Same tools the industry uses:**

| Tool                         | Purpose           | Industry Use              |
| ---------------------------- | ----------------- | ------------------------- |
| **PyCharm / VSCode**         | Code editor       | Google, Microsoft, Meta   |
| **Git & GitHub**             | Version control   | Every software company    |
| **pytest**                   | Automated testing | Netflix, Spotify, Dropbox |
| **Docker**                   | Containerization  | Uber, PayPal, Twitter     |
| **Jenkins / GitHub Actions** | CI/CD             | Amazon, NASA, Spotify     |

**You'll have industry-ready skills from day one.**

---

## Poll: What Surprised You? 🎯

_What's one thing you didn't expect about software engineering?_

A) How much planning happens before coding
B) That code is designed to be _read_, not just run
C) How quickly you can build something useful
D) That even simple programs need edge-case handling
E) Something else (type in comments!)

---

## Challenge: Add One New Feature at Home 🏠

**Ideas to extend this task tracker:**

1. **Priority levels** – High, Medium, Low for each task
2. **Due dates** – Add deadlines and sort by date
3. **Save to file** – Store tasks in a text file so they persist
4. **Categories** – Group tasks (School, Personal, Work)
5. **Search** – Find tasks by keyword

**Pick one and try coding it yourself!**

**Hint:** Start by sketching the design (what data do you need? which function changes?)

---

## Why Choose Software Engineering Here?

✅ **Industry partnerships** – Placement years at real companies
✅ **Modern curriculum** – Python, cloud, AI, DevOps (not just old Java)
✅ **Team projects** – Build real systems with other students
✅ **Career support** – 95%+ graduate employment rate
✅ **Flexible pathways** – SE, CS, Cyber, AI, Networking degrees all available

**Plus:** Manchester/Northwest tech scene is booming (10-20% above UK salary average)

---

## Real Graduate Outcomes 🎓

**Our recent graduates now work at:**

- Google (London) – Junior SE, £45k starting
- BBC (MediaCity) – Software Developer, £32k
- AO.com (Bolton) – Full Stack Developer, £38k
- Auto Trader (Manchester) – Python Developer, £40k
- Freelance/Startup – Building their own products

**Within 3-5 years:** £50k-£70k is typical
**Within 10 years:** £100k+ for senior/lead roles

---

<!-- _class: lead -->

# Questions? 🙋

**Ask us anything:**

- About the degrees (CS, SE, Cyber, AI, Networking)
- About careers and placements
- About the code we just wrote
- About Python, programming, tech industry

---

## Next Steps 🚀

**Want to learn more?**

1. **Visit our booth** – Pick up a course guide, talk to current students
2. **Apply:** [Your university UCAS/application link]
3. **Try Python at home:** python.org/downloads (it's free!)
4. **Challenge yourself:** Finish the task tracker and add one feature

**Contact:**

- Email: [computing@youruni.ac.uk]
- Website: [youruni.ac.uk/computing]
- Instagram/TikTok: @yourunicomputing

---

<!-- _class: lead -->

# Thank You! 🎉

## Keep Building. Keep Learning.

**Remember:** Every expert started exactly where you are now – curious but unsure.

**The difference?** They just kept building things.

**See you in September! 👋**
