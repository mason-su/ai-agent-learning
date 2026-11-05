# AI Agent Learning

A portfolio and learning index for my journey into **AI Engineering** and **AI Agents**.

This repository is intentionally lightweight. It documents goals, roadmap, and progress, and links out to independent project repositories. Each tutorial project lives in its own GitHub repository (no Git Submodules or Subtrees).

## Project Overview

I am learning how to:

- Build software with AI coding assistants and agents
- Design practical AI applications step by step
- Turn tutorials into clean, independently versioned projects
- Maintain a professional portfolio structure as skills grow

## Learning Objectives

- Practice AI-assisted development with clear requirements and verification
- Strengthen frontend fundamentals with small, complete apps
- Progress toward agentic workflows, retrieval-augmented generation (RAG), and domain-specific agents
- Keep each project independently cloneable, runnable, and documented

## Learning Roadmap

1. **AI-Assisted Development Foundations** — build small apps with an AI coding agent, understand file roles, and verify results locally.
2. **Interactive Frontend & Game AI** — board state, UI interaction, heuristics, and search (Gomoku / Five in a Row).
3. **Applied AI Features** — recommendation-style logic and structured data handling (Recipe Recommender).
4. **AI Engineering & Agents** — retrieval, grounding, and a recruitment-focused agent workflow (RAG and Recruitment Agent).

## Projects

| Project | Status | Repository | Description |
|---------|--------|------------|-------------|
| Calculator | Completed | [ai-calculator](https://github.com/mason-su/ai-calculator) | Responsive web calculator built with HTML, CSS, and JavaScript |
| Gomoku (Five in a Row) | Completed | [ai-gomoku](https://github.com/mason-su/ai-gomoku) | Browser Gomoku with PvP and three AI levels (heuristic + Minimax) |
| Recipe Recommender | Planned | — | Recommendation-style app based on user preferences |
| RAG and Recruitment Agent | Planned | — | Retrieval-augmented agent for recruitment-related tasks |

Planned projects will get their own repositories when development starts.

### Gomoku — brief intro

[ai-gomoku](https://github.com/mason-su/ai-gomoku) is a freestyle Five-in-a-Row game that runs entirely in the browser (no backend, no external AI APIs). It grew out of an earlier Tic-Tac-Toe exercise and now includes:

- A responsive 15×15 board with stones on intersections
- Player vs Player and Player vs AI (Easy / Medium / Hard)
- Separated modules for game rules, AI, and UI
- Automated Node tests for win detection, illegal moves, and AI move validity

Open the [ai-gomoku README](https://github.com/mason-su/ai-gomoku#readme) for file layout, rules, AI algorithm notes, local run steps, and GitHub Pages deployment.

## Technologies Covered

**Current**
- HTML5, CSS3, Vanilla JavaScript
- Game-state design, heuristic evaluation, Minimax with Alpha-Beta pruning
- Git and GitHub repository organization
- AI-assisted coding workflow with Cursor Agent

**Upcoming (planned)**
- Structured data / recommendation logic
- RAG concepts, embeddings, and agent tooling

## Learning Progress

- [x] Set up a main learning portfolio repository
- [x] Complete the first AI-assisted calculator project
- [x] Split the calculator into an independent repository
- [x] Build Gomoku as a standalone project (with local AI opponents)
- [ ] Build Recipe Recommender as a standalone project
- [ ] Build RAG and Recruitment Agent as a standalone project

## How to Use This Repository

This repository is documentation-first. Browse the project table above and open each linked repository for source code and run instructions.

## Notes

- Project repositories are independent clones — not submodules or subtrees.
- README content is written in English for portfolio clarity.

## Author

Mason — learning AI Engineering and AI Agents through hands-on projects.
