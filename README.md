# ACR106 Chapter 6 Escape Room

Skills Trades Lab · Controls and Accessories

30 original chapter-based challenges across six rooms. Students play individually. Multiple choice, numeric calculations, matching, sequencing, and troubleshooting are included.

## GitHub setup

1. Create a repository named `acr106-chapter6-escape-room` under `SkillsTradesLab`.
2. Upload `index.html`, `.nojekyll`, and this README to the repository root. Upload the extracted files, not the ZIP itself.
3. Open Settings > Pages. Choose Deploy from a branch, then `main` and `/ (root)`, and save.
4. Use the live URL displayed by GitHub Pages. It may take a few minutes to become available.

## Shared progress connection

GitHub Pages serves the game interface. A separate hosted progress service stores class sessions and student progress. Its address is already included in `index.html`.

**Student access to the progress service must be enabled before classroom use.** The review service starts private; uploading the files to GitHub alone does not enable cross-student access. Ask the builder to enable student access when ready. If that service is private or unavailable, the game shows a connection error rather than pretending progress was saved.

No passwords, API keys, answer keys, or private teacher keys are in this GitHub package. Teacher and student keys are generated separately for each session. The instructor's source PDF is not distributed in the repository.

## Teacher instructions

- Open the game and choose Teacher desk.
- Select No time limit (default), or Custom minutes, then Create class session.
- Download your private teacher key. It opens the same dashboard on another browser with the class code.
- Share Copy student link and the 8-character class code. Never share the teacher key.
- Each student joins once using a name or teacher-assigned nickname. Eight or more students can play independently; no class-size limit is imposed in the game.
- The dashboard updates every four seconds and shows solved questions, current room, incorrect attempts, hints, elapsed time, completion status, and attempt history.
- Use Apply settings to change minutes or select No time limit. Timers run individually from each student's original join time. Increasing or removing a limit lets timed-out students continue; lowering it may immediately expire a student's timer.
- Close this session stops new joins and further answers. Uncheck it and apply to reopen.
- Export progress CSV to save a local record.

## Student instructions

- Open the student link, enter your name/nickname and class code, and solve the challenges.
- Solve all five challenges in a room to recover its key and enter the next room.
- Incorrect answers do not erase progress. Hints are available and counted once per question.
- The timer starts when you join, if your teacher selected one. It continues while your browser is closed.
- Progress is stored online. Use Resume saved student progress on the same browser, or save the student key to continue elsewhere.
- Keep student keys private; they grant access to that student's progress.

## Chapter coverage

1. The Frozen Box — thermostats, differentials, off-cycle defrost, sensing bulbs.
2. Valve Vault — valve positions, dust caps, discharge safety, pump-down sequence, solenoid flow direction.
3. Pressure Chamber — hot gas bypass, CPR, EPR, LP controls, high-pressure diagnosis.
4. Oil Lock — separators, oil return, net oil pressure, time delays, current-sensing relays.
5. Liquid Store — receivers, fill percentage, king/queen valves, expansion safety, accumulators.
6. The Final Circuit — desiccants, drier restrictions, sight-glass interpretation, heat exchangers, vibration eliminators.

Questions are adaptations based on the supplied Chapter 6 Controls and Accessories PDF. The game is a classroom simulation, not a substitute for equipment-specific service instructions. Chapter numeric rules of thumb are identified as such.

## Validation

The local shared-service test exercised eight independent students completing all 30 questions, hidden answer keys, incorrect attempts, hint counting, student-key resume, teacher-key protection, setting changes, session closure, and requests from the GitHub Pages origin. The build and TypeScript checks passed. Classroom student access and the GitHub Pages deployment still require their setup steps above.
