# Website Uplift — Guided Mock

A self-contained, clickable prototype of the **Semrush → AEM PLG experience** from the end-customer's point of view. Open `index.html` in any browser (no build, no server).

## The flow it visualises

The demo customer is **knack.com** (matching the real Stardust redesign at
`paolomoz.github.io/semrush-stardust/knack/`), shown with an AI Visibility of 18/100.

1. **Discover** — Inside the Semrush AI Visibility dashboard, a known customer sees an *"Uplift your website — see how"* hook: brand already extracted, 5 design tensions found, 3 redesign directions ready.
2. **Direct** — "Here's what we found": extracted brand + tensions, and the **3 directions** (Refined / Vivid / Dynamic). Optional short **questionnaire** (goals, audience, mood tiles) that recommends a direction.
3. **Preview** — A **live, browsable** redesign (iframes the real generated site) with a device toggle and a "what changed" summary. Switch directions on the fly.
4. **Deploy** — Animated, hands-off deploy to **AEM Edge Delivery** (convert → Document Authoring → provision Workspace → publish), ending in a live site with 100/100 Lighthouse.
5. **Manage** — **AEM Experience Workspace**: WYSIWYG canvas (in-place editable hero, selectable blocks) + **Workspace AI** chat that performs real edits — rewrite hero, add an FAQ block, restyle to premium, run an SEO/AI-visibility pass.

The "feel the management first" path (prototypes already live in AEM, editable before choosing a direction) is wired from the Preview side panel → opens Experience Workspace in a sandbox banner state.

## Navigation
- Click the real CTAs to move forward, or use the **Guided mock** bar (bottom-left): Restart / Prev / Next.
- The left Semrush nav item **"Website Uplift ✦ NEW"** re-enters the flow.

## Notes
- Pure HTML/CSS/JS, single file. The redesign preview loads `paolomoz.github.io/semrush-stardust/knack/index.html`; if blocked, a graceful fallback offers an "open in new tab" link.
- Visual style mirrors current Semrush UI (icon rail, AI Visibility subnav, gauge/charts); the AEM portion mirrors Adobe Experience Manager chrome.
- This is a **fidelity mock for stakeholder visualisation**, not production code.
