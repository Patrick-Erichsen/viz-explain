# viz-explain

An editable Excalidraw gallery and agent skill for explaining software systems
with the visual grammar that best fits the question.

- [Live gallery](https://patrick-erichsen.github.io/viz-explain/)
- [Skill discovery index](https://patrick-erichsen.github.io/viz-explain/.well-known/agent-skills/index.json)
- [`SKILL.md`](skill/SKILL.md)

## Local preview

```sh
node scripts/build-site.mjs
python3 -m http.server 4173 --directory .site-dist
```
