# [name]

An agent security framework for people who build agents. Work in progress.

The core is already taught in lectures:

- Assume the model's output is already maximally harmful, whatever the source of the text: an attacker, the user, or a plain model error.
- For every capability you give an agent, ask three questions: what to protect, what the worst output can reach, and what stops it outside the model.
- Hold five principles outside the model: least privilege, isolation, data flow and access control, output handling, recoverability.
- Test the system, not the model: replace the model with a stub that returns the worst possible output, and check that the system still refuses.

## Lectures

- [Security of AI agents for those who build them](lectures/2026-09-ysda/), Yandex School of Data Analysis, 29 September 2026. Slides and notes.

More material by topic is in [Awesome Agent Hardening](https://github.com/roselis-lab/awesome-agent-hardening).

Aleksandr Goncharov · [LinkedIn](https://www.linkedin.com/in/goncharov-aleksandr/)
