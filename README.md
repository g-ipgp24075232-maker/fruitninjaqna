# Fruit Ninja: Quiz Challenge 🍉⚔️

A responsive browser-based multiple-choice learning game inspired by Fruit Ninja. Learners answer questions by slicing the fruit that displays the correct answer while avoiding bombs.

## Play the game

After enabling GitHub Pages, open:

`https://g-ipgp24075232-maker.github.io/fruitninjaqna/`

## Run locally

1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. No installation, login, API key, or build process is required.

## How to play

- Read the question.
- Swipe/drag across the fruit showing the correct answer, or tap/click it.
- Correct answer: **+10 points**.
- Incorrect answer: **−5 points**.
- Bomb: **−10 points**.
- Each round uses a shuffled set of questions and shuffled answer positions.

## Edit the questions

Open `questions.js` and edit the `QUESTION_BANK` array. Each question uses this format:

```js
{
  question: "Your question here?",
  options: ["Option A", "Option B", "Option C", "Option D"],
  answer: "Option B",
  explanation: "A short explanation shown after the answer."
}
```

Make sure the answer exactly matches one of the four options. The game randomly selects up to 10 questions for each session.

## Publish with GitHub Pages

1. Open the repository **Settings**.
2. Select **Pages** in the sidebar.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch **main** and folder **/(root)**, then click **Save**.
5. Wait for GitHub Pages to publish the site. The URL is shown on the Pages settings screen.

The repository must be public for GitHub Pages on plans that do not support private-repository Pages hosting.

## Files

- `index.html` — game screens and layout
- `style.css` — responsive visual design
- `script.js` — canvas, slicing, scoring, sounds, and game flow
- `questions.js` — editable question bank
