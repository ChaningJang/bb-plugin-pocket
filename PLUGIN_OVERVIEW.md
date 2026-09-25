The full bb web app on a phone is the desktop app squeezed onto a small screen. Pocket is a separate, radically simpler page for the three things a phone is actually for: telling your agents what to do, triaging what needs you, and glancing at what they made.

## What you get

**Voice first.** Hold the big mic to talk, slide up to lock for a long note, slide left to cancel. You see the transcript before it sends. It goes to your manager thread (picked automatically, or long press any thread → Make manager) or any thread you choose. An iOS Shortcut adds Siri, the Action Button and the share sheet.

**Triage by swipe.** Home is four lists: Pinned, Needs you, Working, Earlier. Swipe left to mark read, keep going to dismiss until the agent says something new. Swipe right to pin. Opening a thread is only a peek, so marking read is always your call.

**One-tap replies.** Each agent message gets up to four suggested replies as pills, with a short cancel window on every tap. When you leave a message unanswered, a stronger model writes one line on what's at stake and recommends one reply.

**Threads without the noise.** Your messages and each turn's final answer, with no tool-call output. Answer questions and approve steps in one tap. Swipe in from the right edge for the files and links a thread produced. Change a thread's model from a chip above the reply box, rename with an AI-suggested title, and search every thread and artifact from home.

**Walk.** A hands-free live voice session, if the Talk to BB plugin is installed.

## Requirements

bb 0.43 or later, and bb Connect to reach it from your phone. An OpenAI API key (your own, stored as a plugin secret) turns on transcription, reply pills and recommendations. Without one, voice falls back to bb's transcription and pills fall back to yes/no.

## Safety

A pill can never tell an agent to send, post, forward, email, delete or archive anything; that is filtered on the server, not just asked of the model. Pocket has no send button for email or Slack. The only data that leaves your server is voice audio and, for pills, the agent's latest message plus your previous one, sent to OpenAI under your key.
