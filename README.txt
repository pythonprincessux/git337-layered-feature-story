START HERE: This folder is the required scaffold for the Module 4 Assessment, not a finished composition.

1. Rename the folder for your project and place it in a new repository or approved workspace.
2. Choose one focused editorial story and replace every placeholder in index.html.
3. Complete composition-plan.html before finalizing each positioned, layered, or shaped element.
4. Keep the L1–L6 labels visible so assessment evidence is easy to locate.
5. Merge your Module 1 reset, tokens, typography, and components into styles.css. Replace starter demonstrations with your own justified design; do not submit the starter styling unchanged.
6. Preserve logical source order. Use Grid/Flexbox for primary layout and positioning only for bounded spatial relationships.
7. Use native HTML and CSS only—no JavaScript. Test all enhancements and their fallbacks according to the Canvas instructions.

SUPPORT AND FALLBACK RECORD

Checked: September 20, 2026

clip-path
MDN: https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/clip-path
Support: MDN lists clip-path as widely available.
Fallback: If clip-path is unsupported or disabled, the feature image remains visible as a normal rectangular image with rounded corners.

shape-outside
MDN: https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/shape-outside
Support: MDN lists shape-outside as widely available, although some parts may have varying levels of support.
Fallback: If shape-outside is unsupported or disabled, the portrait remains visible and the text continues in normal readable flow.

shape-margin
MDN: https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/shape-margin
Support: MDN lists shape-margin as widely available.
Fallback: If shape-margin is unsupported, the portrait remains visible and the text remains readable without the extra spacing around the shape.

position: sticky
MDN: https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/position
Support: MDN lists position: sticky as widely available.
Fallback: On smaller screens, the story guide remains in normal document flow instead of using sticky positioning.

z-index and stacking context
MDN: https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Positioned_layout/Stacking_context
Support: MDN documents stacking contexts as the system browsers use to control how overlapping elements are layered.
Fallback: The page remains readable in normal source order without the enhanced layer relationships, and the project uses a small tokenized z-index scale instead of arbitrary large values.
border-radius
MDN: https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/border-radius
Support: MDN lists border-radius as widely available.
Fallback: If border-radius is unsupported, the feature figure and portrait display with square corners while all content remains visible and readable.

TEST RECORD

HTML validation
Result: Passed. The HTML was checked with the W3C validator.
Evidence: evidence/html-validator-evidence.png

CSS validation
Result: Passed. The stylesheet was checked with the W3C CSS validator.
Evidence: evidence/w3c-validator-evidence.png

CSS-disabled reading order
Result: Passed. With CSS disabled, the story remained complete and readable in source order.
Evidence: evidence/css-disabled-reading-order.png

Responsive viewport testing
Result: Tested at 320px, 768px, and 1280px. Content stayed readable and the layout adapted without fixed height content boxes.
Evidence: evidence/320px-viewport.png
Evidence: evidence/768px-viewport.png
Evidence: evidence/1280px-viewport.png

200% zoom
Result: Passed. The story remained readable and usable at 200% browser zoom without essential content being obscured.
Evidence: evidence/200-percent-zoom.png

Keyboard focus
Result: Passed. Story guide links remained keyboard accessible and displayed a gold visible focus indicator using only the tab key and space bar.
Evidence: evidence/200-percent-keyboard-focus.png

Long-title content growth
Result: Passed. The extended story title wrapped without clipping, overlap, or losing readability.
Evidence: evidence/long-title-test.png

Doubled-paragraph content growth
Result: Passed. Additional paragraph content expanded in the document flow without breaking the layout.
Evidence: evidence/doubled-paragraph-test.png

clip-path fallback
Result: Passed. With clip-path disabled, the complete feature image remained visible and readable as a rectangular image.
Evidence: evidence/clip-path-disabled.png

shape-outside fallback
Result: Passed. With shape outside disabled, unchecked using devtools. the portrait remained visible and the surrounding story content remained readable.
Evidence: evidence/shape-outside-disabled.png

Sticky behavior
Result: Tested at the page and section boundaries. The story guide stayed readable in its normal layout, but sticky behavior was not consistently observed during boundary testing.
Evidence: evidence/stacking-boundary-test.png

Layer and stacking inspection
Result: I inspected the positioned and layered elements in the browser developer tools. The issue badge uses the raised layer token, the story guide uses the sticky layer token, and the pull quote uses the raised layer token on wider screens. No content or controls were hidden by the layered elements.
Evidence: evidence/stacking-check.png
Evidence: evidence/stacking-issue-badge.png
Evidence: evidence/stacking-boundary-test.png

Pointer activation
Result: Passed. Both story guide links were tested with pointer activation. “First section” navigated to “The Listing vs. The Reality,” and “Second section” navigated to “Principles for Clearer Information.” Both controls remained clickable and unobscured by layered elements.

ASSET AND CONTENT CREDITS

Story content
The rental housing feature story was written by Kiara McRae for this assessment.

Visual assets
feature.svg — Provided with the GIT 337 Layered Feature Story starter files.
portrait.svg — Provided with the GIT 337 Layered Feature Story starter files.