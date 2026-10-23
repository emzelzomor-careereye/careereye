# Healthcare Team Rescue Mission

A facilitator-led game for the *Silent Burnout in Healthcare Teams* training of trainers (TOT) workshop. Project `index.html` on the room screen. The facilitator runs the game and records each team's answers. Participants use green, amber and red cards (or tokens).

It's a single file with no build step. Open `index.html` in a browser, or host the folder on any static host (for example, GitHub Pages). Game state is saved in the browser, so a page refresh doesn't lose scores. Use **Reset game** to start over.

## Mission structure

| Stage | Goal | Challenge | Scoring |
|---|---|---|---|
| 1. Detect | Find the hidden signals | **Spot the Silent Burnout**: 7 cases, each judged green, amber or red | +1 correct call, +1 hidden sign, +2 good response, +1 for spotting what other teams missed |
| 2. Connect | Understand the team impact | **The Burnout Detective**: 5 clues about Sam; after each one, teams choose Investigate, Ignore or Intervene. Then the **Ripple effect**: teams name the impacts on the team | +1 per clue that matches the facilitator's read, +1 per impact named |
| 3. Respond | Handle the conversation | **Say This, Not That**: 9 statements to classify as Helpful, Unhelpful or Potentially harmful, then rewrite | +1 correct classification, +2 strong rewrite |
| 4. Restore | Build the team's sustainability plan | Each team picks actions at the Me, Us and System levels and writes a commitment of its own | +1 per level covered, +2 for naming an owner and a date |

Completing each stage awards one **Sustainability Key**. The debrief screen shows the final standings and the closing message: *"You weren't looking for a diagnosis. You were looking for a signal."*

## Facilitator tips

- Answers stay hidden until you press **Reveal**, so the screen is safe to project.
- Use the round timer on the right for the race elements. The default is 90 seconds; you can change it on the briefing screen.
- Use the scoreboard's **+/−** buttons for discretionary bonuses.
- **Ripple effect impacts.** Impacts stay hidden on screen until a team names one, so award points against this list:
  1. Colleagues quietly absorb extra work
  2. Handovers get thinner and less safe
  3. Junior staff stop asking questions
  4. Cynicism spreads through the team
  5. Patients and families feel less cared for
  6. Risk of errors and near-misses rises
  7. More sick leave and last-minute gaps in the rota
  8. A good clinician leaves the profession
- **Restore:** at the end, **Copy all plans** copies every team's plan as text for the workshop handout.

## Safety note

The game builds recognition and peer-response skills. It isn't a diagnostic tool. If anyone mentions hopelessness or harming themselves, treat it as urgent: ask directly, stay with them, and use your organisation's urgent support pathway.

## Editing content

All cases, clues, statements and plan options are plain data at the top of the `<script>` block in `index.html` (`SCENARIOS`, `CASE`, `IMPACTS`, `STATEMENTS`, `LEVELS`). Edit the text there to adapt the game to your audience or local terminology.
