# Understanding Session Status

Every session in Mediyn moves through a series of stages from start to finish.

## Session Lifecycle

Your session moves through these stages:

1. **Scheduled** -- The session is booked and waiting to take place. This is the starting point for every new session.

2. **In Progress** -- The session has started. Mediyn records the actual start time at this point.

3. **Processing** -- The session has ended and Mediyn is processing the recording and generating clinical notes. The actual end time is recorded at this stage.

4. **In Review** -- Clinical notes (transcription, summary, and key insights) are ready for you to review and edit.

5. **Approved** -- You have reviewed and approved the clinical notes. The session is finalized.

6. **Archived** -- The session has been moved to long-term storage.

7. **Cancelled** -- The session was canceled before completion.

## How Sessions Move Between Stages

Sessions move forward through the stages automatically as actions occur. For example, when you start a session, it moves from Scheduled to In Progress. When the session ends and a recording is submitted, it moves to Processing.

You can also advance a session through multiple stages at once. For example, moving directly from In Progress to Approved will pass through Processing and In Review along the way.

Sessions cannot move backward to a previous stage.

## Consent Status

Each session also tracks consent separately:

- **Pending** -- Consent has not yet been requested
- **Confirmed** -- Consent has been requested and confirmed
- **Obtained** -- Consent documentation is on file
- **Revoked** -- The patient has withdrawn consent

## Cancellation Details

When a session is cancelled, Mediyn records:

- The reason for the cancellation (if provided)
- Who canceled and when
- Whether it was a late cancellation
- Whether the patient was a no-show
- Any fee invoice that was created

## Good to Know

- The session status helps you track where each appointment stands in your workflow.
- Sessions that have been rescheduled show a link to the original session for reference.
- You can search for sessions by status to quickly find all sessions at a particular stage.
- The transition from Processing to In Review happens automatically after Mediyn finishes generating clinical notes.
