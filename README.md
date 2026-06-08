FALSE POSITIVE

Certainty is a bad witness.

FALSE POSITIVE is a one-button signal terminal for checking the alarm before it becomes a verdict.

It gives the user a short diagnostic card: a line that slows down certainty, reopens the evidence, and asks whether the first interpretation is signal, fear, memory, projection, habit, or panic wearing authority.

It does not dismiss suspicion.

It makes suspicion show its work.

WHAT IT IS

FALSE POSITIVE is a self-contained browser app built as a single HTML file.

It contains a curated deck of 999 text cards. Each card is a compact signal-check: a sentence or two that tests a suspicion, fear, first impression, emotional alarm, or premature verdict.

The app is not reassurance.

It is not self-help.

It is not advice in the usual sense.

It is a diagnostic interruption.

The machine asks:

Is the alarm useful?

Is the verdict early?

What else might explain the signal?

CURRENT STATUS

App: FALSE POSITIVE
Deck size: 999 cards
Format: single-file HTML
Mechanism: one-button random card draw
Storage: local browser/session only
Backend: none
Build step: none
Version status: expanded 999-card deck with redesigned sibling-aligned interface

CORE INTERACTION

The app has one primary action:

STRIKE

Each press selects one random card from the internal deck and displays it as a signal-check.

Secondary controls:

COPY copies the current card text.

CLEAR resets the display.

ABOUT opens the app’s information panel.

RETURN closes the ABOUT panel and returns to the main signal view.

Keyboard interaction:

SPACE or ENTER draws a card from the main view.

ESC returns from the ABOUT panel.

INTENDED USE

FALSE POSITIVE is useful for:

slowing down certainty
testing suspicion
checking emotional alarms
interrupting overconfident stories
examining first impressions
writing sharper reflective prompts
building dialogue around ambiguity
developing cognitive friction
creating prompts for journals, essays, scenes, and conversations
separating evidence from interpretation
separating alarm from verdict

The app is especially suited for moments when something feels obvious too quickly.

The point is not to decide that the alarm is false.

The point is to check whether it has earned authority.

CONTENT PRINCIPLE

A good FALSE POSITIVE card should begin near a familiar alarm.

Something looked cold.

Something felt hostile.

Someone went quiet.

A message arrived late.

A plan changed.

A room became tense.

A memory felt certain.

A pattern seemed obvious.

Then the card should widen the interpretation without cancelling the signal.

The best card does three things:

names the alarm
offers a plausible alternative
keeps responsibility for checking the evidence

Example:

The alarm did its job by waking you. Do not let it drive.

That works because it does not mock the alarm. It respects the warning while refusing to let it become the whole government.

STYLE RULES FOR FUTURE CARDS

Keep the card clear.

Keep the situation recognisable.

Do not become vague comfort.

Do not become motivational advice.

Do not become BADVICE.

Do not become SAID IT.

Do not become IDK MACHINE.

Avoid cleverness that weakens practical use.

Avoid cards that merely say “maybe not”.

Avoid cards that dismiss pain.

Avoid cards that excuse bad behaviour too easily.

Avoid overlong aphorisms.

Avoid decorative ambiguity.

The line should slow the user down, not blur the issue.

The card must preserve the central diagnostic movement:

alarm
evidence
verdict

GOOD CARD TEST

Before adding a new card, ask:

Does the card begin from a recognisable alarm?

Does it slow down the verdict?

Does it offer a plausible alternative explanation?

Does it avoid dismissing the original concern?

Does it distinguish evidence from interpretation?

Does it feel useful under pressure?

Can it be read quickly and understood immediately?

Does it still sound like FALSE POSITIVE?

DECK STRUCTURE

The deck lives inside the JavaScript array named CARDS.

Each card is a plain text string.

Example structure:

"The alarm did its job by waking you. Do not let it drive."

The app does not use themes for individual cards.

The deck should remain a clean plain-string array unless the app mechanism is deliberately redesigned later.

VISUAL IDENTITY

FALSE POSITIVE belongs to the SPARK TOOLS sibling family.

The visual language should remain:

dark terminal
retro CRT atmosphere
green/gold signal palette
muted warning red
compact one-button interaction
minimal interface
strong central output card
small diagnostic iconography
clear mobile-first layout

The design should feel like a signal-checking terminal, not a general quote generator.

It should be calmer than BADVICE, less playful than IDK MACHINE, and more diagnostic than SAID IT.

FILES

The app can be used as a standalone file:

index.html

It can also be placed inside a folder on a static site:

false-positive/index.html

No extra files are required.

DEPLOYMENT

FALSE POSITIVE is static.

To publish it, upload the HTML file to any static web host or to a folder inside an existing website.

Recommended structure inside the SPARK TOOLS site:

spark-tools/
false-positive/
index.html

Then the live path should be:

/spark-tools/false-positive/

The app does not require a database, server code, package manager, build tool, or installation step.

UPDATING THE DECK

After adding or editing cards, check that:

The total card count is correct.

There are no duplicate card texts.

Every card is a non-empty string.

The JavaScript still passes syntax checking.

The CARDS counter reflects the current deck size.

The app still loads.

STRIKE draws a card.

COPY copies the current card.

CLEAR resets the card.

ABOUT opens the information panel.

RETURN closes the information panel.

SPACE or ENTER draws a card from the main view.

ESC returns from the ABOUT panel.

FINAL NOTE

FALSE POSITIVE works best when it respects the alarm without obeying it too quickly.

The alarm may be right.

The alarm may be wrong.

The alarm may be about something real but misnamed.

The machine exists for that fragile second before certainty hardens.

Let the alarm speak.

Make the evidence answer.
