# TOEFL Speaking Practice — Android

An Android speaking-practice application designed around the updated TOEFL-style speaking workflow, with timed tasks, test and practice modes, local score history, and on-device AI-assisted analysis.

> This is an independent practice project. It is not produced, endorsed, or audited by ETS.

## Project overview

This project was conceived as a practical speaking-training tool rather than a static study app. The focus is on reproducing the flow and pressure of a timed speaking session while still giving the learner a separate practice environment for repetition, feedback, and progress tracking.

The application currently includes a bank of complete practice tests, a Listen & Repeat section, a Take an Interview section, timed recording, local result storage, score breakdowns, CEFR-oriented feedback, and offline transcription/analysis using an on-device Whisper workflow.

## Screenshots

### Home and format overview

<p align="center">
  <img src="docs/screenshots/home.jpg" width="240" alt="TOEFL Speaking Practice home screen" />
</p>

### Test and Practice modes

<p align="center">
  <img src="docs/screenshots/modes.jpg" width="240" alt="Test and Practice mode selection" />
</p>

## Key features

- Separate **full test simulation** and **practice mode**
- **Listen & Repeat** task flow with timed responses
- **Take an Interview** task flow with real-time speaking prompts
- Automatic recording of spoken responses
- **On-device/offline Whisper transcription** for saved responses
- Local analysis workflow without requiring cloud scoring
- Estimated speaking band display
- CEFR-oriented score reference
- Item-level task breakdown
- Local score history for recent Test and Practice sessions
- Session-oriented progress and attempt tracking
- 100 complete practice tests with original practice prompts/questions

## Why the project is different

The app is designed around an actual interaction loop:

1. The learner selects a complete test or practice session.
2. The application presents timed speaking tasks.
3. The learner records real responses under time pressure.
4. Saved audio is transcribed locally.
5. A rubric-oriented scoring workflow generates an estimated practice result.
6. Results are stored locally so progress can be reviewed later.

This makes the project closer to a functional assessment simulator than a simple question bank.

## Offline AI workflow

A central design decision was to keep the speech-analysis workflow local where possible. The application records the learner's real audio, transcribes saved responses using an on-device Whisper workflow, and combines transcript-related information with timing, pause, and audio-delivery signals to generate a non-official practice estimate.

The scoring system does **not** reproduce ETS's proprietary scoring system and should not be interpreted as an official TOEFL score predictor.

## Development approach

The product concept, feature requirements, user-flow decisions, testing priorities, scoring logic checks, and iterative refinements were directed by **Shima Atabaki**.

AI-assisted development tools were used during implementation, debugging, testing, and refinement. The project therefore represents a combination of:

- Product ideation
- Requirement definition
- UX and workflow design
- Test-case design
- Quality assurance
- Edge-case debugging
- AI-assisted software development

## Technology

- Android
- Android Studio
- Native Android application workflow
- Local audio recording
- On-device Whisper-based transcription
- Local result/history storage
- AI-assisted development and debugging workflow

## Source code

The production source code is intentionally kept private.

This public repository is used as a **portfolio and project showcase** rather than as a source-code distribution repository.

## Project status

Active development and refinement.

Current work focuses on usability, scoring consistency, task-flow accuracy, stability, and preparing the application for broader distribution.

## Author

**Shima Atabaki**

Product concept, requirements, UX direction, testing, validation, and development coordination.

---

### Trademark notice

TOEFL is a trademark of ETS. This independent project is not affiliated with, endorsed by, or sponsored by ETS.
