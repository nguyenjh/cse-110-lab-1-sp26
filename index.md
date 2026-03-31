# EXAMPLE

# Welcome to My User Page

> "Any fool can write code that a computer can understand. Good programmers write code that humans can understand." – Martin Fowler

---

## Table of Contents

- [About Me](#about-me)
- [My Programming Journey](#my-programming-journey)
- [Skills & Technologies](#skills--technologies)
- [Favorite Projects](#favorite-projects)
- [Fun Facts](#fun-facts)
- [Goals](#goals)
- [Contact](#contact)

---

## About Me

Hi there! I'm a **passionate programmer** and _lifelong learner_ who loves building things that make life easier and more interesting. Whether I'm debugging a tricky issue or sketching out a new project idea, I bring curiosity and persistence to everything I do.

I grew up fascinated by how things work — from taking apart old electronics to eventually learning how software powers the modern world. Outside of coding, I enjoy hiking, reading sci-fi novels, and experimenting in the kitchen.

![Profile Picture](https://images.unsplash.com/photo-1517694712202-14dd9538aa97?w=400&q=80)

*A programmer at work — because laptops and coffee are a universal language.*

---

## My Programming Journey

I started programming with **Python** in high school after stumbling on a tutorial about building simple games. From there, I fell in love with the logic and creativity that programming demands.

Here's a quick look at my journey:

1. **Year 1** – Learned Python basics; built a text-based adventure game
2. **Year 2** – Explored web development with HTML, CSS, and JavaScript
3. **Year 3** – Dived into data structures, algorithms, and Git/GitHub
4. **Year 4** – Started contributing to open-source projects and building full-stack apps

> "The best error message is the one that never shows up." – Thomas Fuchs

I still remember the first time my code actually *worked* — there's no feeling quite like it.

---

## Skills & Technologies

### Languages

- **Python** – my first love; great for scripting and data work
- **JavaScript** – for all things web
- **Java** – learned in CS courses; solid for OOP concepts
- **Bash** – for automating the boring stuff

### Tools & Frameworks

- Git & GitHub
- React.js
- Node.js
- VS Code
- Linux / Command Line

### Currently Learning

- [ ] TypeScript
- [ ] Docker & containerization
- [x] Markdown & documentation best practices
- [x] GitHub Pages & static site deployment
- [ ] Machine learning fundamentals

---

## Favorite Projects

### 🌐 Personal Portfolio Site

A responsive portfolio built with HTML, CSS, and vanilla JavaScript. Hosted on GitHub Pages.

**Key features:**
- Mobile-first design
- Dark mode toggle
- Animated project cards

Check out the [project README](./README.md) for setup instructions.

### 🐍 Python Automation Scripts

A collection of small scripts that automate repetitive tasks — renaming files, sending scheduled emails, and scraping public data.

Here's a taste of what one looks like:

```python
import os

def rename_files(directory, prefix):
    """Renames all files in a directory with a given prefix."""
    for i, filename in enumerate(os.listdir(directory)):
        new_name = f"{prefix}_{i:03d}{os.path.splitext(filename)[1]}"
        os.rename(
            os.path.join(directory, filename),
            os.path.join(directory, new_name)
        )
        print(f"Renamed: {filename} → {new_name}")

rename_files("./photos", "vacation")
```

### 📊 Data Dashboard

A JavaScript + Chart.js dashboard that visualizes CSV data interactively. Built as a final project for a web dev course.

---

## Fun Facts

Here are some things you might not expect about me:

- 🎸 I taught myself guitar using YouTube tutorials
- 🌮 I make a *mean* homemade salsa
- 📚 I've read the entire *Foundation* series by Isaac Asimov — twice
- 🧩 I love logic puzzles and escape rooms
- 🐱 I have a cat named **Kernel** (yes, like the OS kernel)

![Coding Setup](https://images.unsplash.com/photo-1498050108023-c5249f4df085?w=400&q=80)

*My ideal workspace: clean desk, good light, and a strong cup of coffee.*

---

## Goals

### Short-Term
1. Complete my current algorithms course
2. Land a summer internship at a tech company
3. Build and deploy a full-stack web app

### Long-Term
1. Contribute meaningfully to open-source software
2. Work on projects that have real-world social impact
3. Mentor newer programmers the way I was mentored

---

## Useful Resources

Here are some of my favorite places to learn and grow:

- [MDN Web Docs](https://developer.mozilla.org) – the gold standard for web reference
- [freeCodeCamp](https://www.freecodecamp.org) – free, project-based learning
- [GitHub Docs](https://docs.github.com) – everything you need for version control
- [The Odin Project](https://www.theodinproject.com) – a great full-stack curriculum

---

## Contact

Feel free to reach out! I'm always open to collaborating, chatting about code, or swapping book recommendations.

- 📧 Email: myemail@example.com
- 🐙 GitHub: [github.com/myusername](https://github.com)
- 💼 LinkedIn: [linkedin.com/in/myusername](https://linkedin.com)

---

*Thanks for visiting — scroll back to the [top](#welcome-to-my-user-page)!*