# Speak Up — English Reading, Vocabulary & Comprehension Studio

A minimalist, high-performance web application designed to help English learners practice reading out loud with a moving teleprompter, master 1,200 advanced B2 vocabulary items, and test their reading comprehension across 50 topics with interactive quizzes.

## ✨ Features

- **Three Integrated Learning Modes**:
  - 📖 **Practice Mode**: Fluid, auto-scrolling teleprompter with focus line, speed pacing cues, and adjustable WPM (40–260) across 50 diverse topics.
  - 📚 **Vocabulary Mode**: Curated **B2 Upper-Intermediate** vocabulary cards across all 50 topics (**1,200 words total**) featuring:
    - Target word with part of speech
    - Accurate Uzbek translations
    - Audio pronunciation button (Web Speech API)
    - Contextual example sentences with highlighted keywords
    - Uzbek example translations
    - Real-time live search & quick part-of-speech filters (All, Nouns, Verbs, Adjectives, Phrases/Idioms).
  - 📝 **Reading & Comprehension Mode**:
    - **50 Enriched Reading Passages** (~150–200 words each) formatted in clean, readable typography.
    - Pure, focused reading and thinking experience (distraction-free without audio buttons).
    - Estimated reading time badges (e.g. `⏱️ 1.5 min read`).
    - **170 Comprehension Questions** across 50 topics (Multiple Choice + True / False).
    - **Instant Interactive Feedback**: Selected options turn green/red immediately with clear contextual explanations citing the passage.
    - **Final Score Card & Retry**: Shows accuracy score, motivational feedback, and allows one-click quiz retrying.
- **Responsive Design**: Flawlessly adapts to any screen:
  - 🖥️ Large Monitors & Ultrawide displays (centered, distraction-free reading studio)
  - 💻 Laptops (comfortable viewing distance, keyboard shortcuts)
  - 📱 Tablets & Mobile phones (dynamic text chunking, generous breathing room, touch-friendly 44px+ controls)
- **Zero-backend / Serverless**: 100% client-side HTML5, CSS3, and modern vanilla JavaScript.

## ⌨️ Keyboard Shortcuts

| Key | Action |
| --- | --- |
| `Space` | Start / Pause scrolling (Practice mode) |
| `R` | Restart teleprompter from beginning |
| `P` | Switch to **Practice** tab |
| `V` | Switch to **Vocabulary** tab |
| `D` | Switch to **Reading** tab |
| `Esc` | Return to topics list |
| `↑` / `→` | Increase speed by 5 WPM |
| `↓` / `←` | Decrease speed by 5 WPM |

## 🚀 Getting Started

Simply open `index.html` or `Speak Up.html` in any modern web browser or run via local server:
```bash
python -m http.server 8080
```
and navigate to `http://localhost:8080`.
