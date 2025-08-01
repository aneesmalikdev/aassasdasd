## Inspiration
Watching friends absorb harmful "positive" slogans during hard times. We realized AI-generated perfectionism erodes authentic connection – this fights algorithmic invalidation at its source.

## What it does
Detects 20+ toxic positivity phrases (e.g., "Just stay positive!") and replaces them with human-curated empathetic responses (e.g., "Your feelings are valid") in real-time. Includes visual highlighting and toggle.

## How we built it
- **Frontend**: Vanilla JS DOM manipulation with MutationObserver
- **Chrome API**: Manifest V3 for content scripts
- **Phrase Database**: 15 pre-curated replacements
- **Visuals**: CSS glow effects + emoji transformations (💔→❤️‍🩹)

## Challenges we ran into
- Avoiding infinite replacement loops in text nodes
- Handling React/Angular SPAs without breaking functionality
- Performance on heavy sites like Facebook
- Creating non-intrusive visual cues

## Accomplishments we're proud of
- Zero false positives in testing
- 200ms average replacement speed
- Personalizing responses with our team's authentic voice
- Solving a real pain point in <4 hours

## What we learned
- Chrome's content security policy limits
- Text node traversal efficiency
- Linguistic patterns of toxic positivity
- Micro-interventions' mental health impact

## What's next for EmpathEase
1. Crowdsourced phrase database + voting
2. Context-aware replacements (grief vs. frustration)
3. Firefox/Safari ports
4. "Teach Mode" for custom phrases


