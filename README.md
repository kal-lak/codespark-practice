# CodeSpark Club — Practice Quiz

A browser-based practice quiz built for the CodeSpark Club, a coding club I founded at **Yihune Woldu Dessie Special Boarding School** to teach the fundamentals of programming to 25 students.

**Live demo:** [Try it here](https://claude.ai/artifact/2379BRCc3Pn1FfwoKjBXig)

## About

After teaching my club members the basics of coding — variables, loops, conditionals, functions — I noticed they needed a way to keep practicing between sessions. So I built this quiz app to reinforce what we covered in class and let students test themselves anytime, on any device.

## What it does

- 12 multiple-choice questions covering core programming fundamentals:
  - Variables & data types
  - Conditionals (`if` / `else`)
  - Loops (`for` / `while`)
  - Functions & return values
  - Arrays
  - Operators
  - Booleans & logic
  - Comments
- Tracks score and a live answer streak
- Explains *why* each answer is correct or incorrect, right after you answer
- Shuffles question order on every run, so it stays useful for repeat practice
- Fully responsive — works on phones, which is how most of my students access it

## Why I built it

Many of my students had never written a line of code before joining the club. Teaching them was only half the job — I wanted to leave them with something that kept the learning going even when I wasn't there to explain it in person. This project is that: a small, focused tool built specifically for the 25 students I taught, based on exactly what we covered together.

## Tech stack

- Vanilla HTML, CSS, and JavaScript — no frameworks or build tools
- Single self-contained file — easy to host anywhere or run offline
- Google Fonts (Space Grotesk, JetBrains Mono)

Kept intentionally framework-free so the code itself is also readable by beginner students who want to peek under the hood and see how it works.

## Running it locally

No installation needed:

```bash
git clone https://github.com/[your-username]/codespark-practice.git
cd codespark-practice
open index.html
```

Or just open `index.html` directly in any browser.

## What I learned

- Structuring a small JavaScript app around state (current question, score, streak) without a framework
- Writing UI that gives clear, immediate feedback — important when your users are beginners who need encouragement, not just a right/wrong stamp
- Designing for an audience with limited or shared device access, which meant keeping the whole app in one lightweight file

## About the club

CodeSpark Club started with a simple goal: give students at our school a first real introduction to computer science. Over two years, I led weekly sessions, mentored 25 students through their first programs, and watched several of them go from "I've never touched a computer for this" to writing their own small scripts.

This project is one small part of that effort — built to outlast my own time leading the club.

---

*Built by [Your Name], founder and lead instructor, CodeSpark Club.*
