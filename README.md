# flotE

A sailboat racing and timing web application developed as a **Fall 2024 COMPSCI 320 Software Engineering** team project at the University of Massachusetts Amherst.

**Dila's portfolio copy:** https://github.com/Dila-Ozersen/flotE

**Original team repository (unchanged):** https://github.com/CS320-Group-1/CS320-Group1

## Overview

flotE was designed to help users organize races, manage fleets and boats, and record race timing. It was a shared academic project, with work spanning frontend design, backend functionality, database integration, and timekeeping.

**Status as of October 20, 2026:** This README documents the class project and Dila Ozersen's reported contributions. Dila has not recently checked its workflows and reports that she cannot currently run it. Historical functionality below is not a claim that the application runs today.

## Team functionality

| Area | Reported class-project status |
|---|---|
| Registration and login | Implemented by the team; current operation and service availability are unchecked. |
| Race creation | Implemented by the team; current operation is unchecked. |
| Fleets and boats | Included boat creation and deletion; current operation is unchecked. |
| Race timing | Timing functionality was implemented, but the end-to-end results workflow had limitations. |
| Final race-time display | Remained faulty at the end of the project; no subsequent fix has been confirmed. |

Other small errors remained. The project should not be described as a complete or production-ready race-timing system.

## Team and credits

Dila confirmed the original repository's author list:

- [Ashley Bhandari](https://github.com/ashleybhandari)
- [Jamie Denley](https://github.com/Jamie11111)
- [Macy Graves](https://github.com/megraves)
- [Austin Henlotter](https://github.com/AustinHen)
- [Dila Ozersen](https://github.com/DilaOzersen)
- Anushka Trehan — Manager

The five developers worked collaboratively. Features described in the team section are the team's combined work, not Dila's sole implementation.

## Dila Ozersen's contributions

Dila helped connect frontend and backend functionality. Her reported work included:

- Crafting and connecting frontend API requests for boat and race workflows, including adding and removing boats from fleets and creating races.
- Helping connect timing data with boats and races.
- Checking MongoDB data persistence, including whether boat/race records saved to the appropriate account and could be removed.
- Contributing to page structure and visual design.
- Collaborating with teammates on integration and reviewing database changes when needed.

She was not the main database designer and does not claim sole ownership of the backend, schema, authentication, or timer.

### Debugging example: boat creation

Moving from fixed mock data to real form input produced incorrect stored boat values and delayed display of the new boat. Dila traced individual input connections, revised frontend/backend integration code, and repeatedly created and deleted entries while checking the behavior.

She reports verifying that a newly created boat displayed the entered information without a page refresh. This resolved boat-creation issue is separate from the unresolved final race-time display problem.

The exact root cause, code change, and commit have not been identified. No specific React state mechanism, endpoint fix, or automated regression test is claimed.

## Technologies

Confirmed by Dila's project account:

- JavaScript
- React
- MongoDB
- Tailwind CSS
- HTML and CSS

The backend runtime/framework and authentication tools remain unconfirmed. An earlier tentative Express.js recollection was not verified in her latest answers.

## Source and running status

The original source is linked above. Dila reports that the code structure remains available, but has not checked the current availability of external services or dependencies. She cannot currently run the application.

No verified installation/startup commands, required versions, configuration steps, or local URLs are available in the latest answers. This README intentionally does not present guessed setup instructions as working commands.

## Validation

Dila's reported development checks included:

- Repeated boat creation/deletion and inspection of MongoDB records.
- Checks that entered data saved to the appropriate account.
- Verification that newly created boats displayed without refreshing the page.

These were manual checks during development. No current runtime test, automated test command/result, screenshot, or demo has been supplied.

## Remaining unresolved details

- Backend runtime/framework, authentication tooling, required versions, and external-service availability.
- Reproducible installation, configuration, database, and startup instructions.
- Current behavior of account, boat, race, timing, and results workflows.
- File/commit-level contribution evidence and the exact boat-creation bug mechanism.
- License and any third-party attribution requirements.

Unknown details are retained as limitations rather than inferred from the available technologies.

## Preservation of the shared project

This repository is Dila Ozersen's personal portfolio copy of the shared class project, with the original Git commit history and development branches preserved. The application was built by the team credited above; this copy does not imply sole authorship by Dila. Only this copy's README has been updated to document the team's work and Dila's reported contributions. The original shared repository and README, and Dila's school account, remain unchanged.

Branches named `archive/pull-request-*` preserve three original commits that were reachable only through old pull-request references. They are historical snapshots, not new development. The original pull-request discussions and reviews remain in the shared repository; they were not recreated here.

## Documentation basis

Finalized October 20, 2026, using Dila's completed essential README questionnaire dated October 20, the October 19 career profile, and the prior README review. Functional and contribution descriptions are Dila's reports, not an independent code or runtime audit. All original local files remain unchanged.
