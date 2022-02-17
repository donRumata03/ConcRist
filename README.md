# ConcRist — Concrete Metaheuristics

<p align="center"><i>The word concrete is borrowed from a famous book ConCrete mathematics and is decrypted as «Continuous&amp;Discrete Mathematics»</i></p>

Concrete Metaheuristics building blocks (MHBB) written in Rust

Major design goals:
- Maximize flexibility: Provide multiple layers of abstraction provide both low and high level access to users: they should be able to plug their code to any of the layers
- Minimize the probability that library design will make a metaheuristic algorithm impossible to be implemented from those blocks
- Minimize the probability that users will need to write code, which is common for MH algorithms in general (not only user's specific one), by their hands. Though any custom feature should have an obvious place to plug to the ConccRist system

The design plan is described in file [Plan.md](Plan.md) file ***in russian***.
