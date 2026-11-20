# System Design Quest

A free browser game for learning system design for interviews, by understanding it instead of memorizing it.

**▶ Play:** https://martetileart.github.io/system-design-quest/

## How it works

28 units, one per chapter of *System Design Interview* Vol 1 & 2 (Alex Xu), following the chapter order of [liquidslr/system-design-notes](https://github.com/liquidslr/system-design-notes).

Each unit:

1. **Learn**: short slides, one idea at a time, starting with a plain-words "big idea".
2. **Quiz**: scenario questions. After each answer you get the *why*, plus an animated diagram that shows it happening.
3. **Explain it**: write the idea in your own words, then compare it with the key points.
4. **Review**: questions you miss come back later (after 1, 3, 7, 16 and 35 days), so you don't forget them.

Each unit has 3 stars to earn: ⭐ 60%+ of the quiz right, ⭐ the whole quiz right, ⭐ 60%+ of the key points explained.

Progress is saved in your browser (localStorage). Nothing is sent anywhere.

## Run it locally

It's a single file, so just open `index.html` in a browser.

## Contributing

Spotted a wrong answer or a confusing diagram? Open an issue or a PR. The questions and diagrams live in the `U` and `D` arrays in `index.html`; the self-check logs any broken diagram to the browser console.

The questions, explanations and diagrams are original material, written as a study aid. For the full content, read the books.
