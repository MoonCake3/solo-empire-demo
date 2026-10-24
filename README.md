# Solo Empire — friends demo

This repository contains a browser-only preview of the Solo Empire interface for usability testing. It is an early prototype, not the finished desktop application.

## Try it

After GitHub Pages is enabled, open the deployed site URL shown in the repository's **Settings → Pages**. The demo build starts in sample mode automatically.

## What the preview demonstrates

- Fat Albert's guided task brief and department suggestion.
- The Solo Empire workspace and camera-room layout.
- Example task and approval flows using fixed sample data.

## What it does not do

- It does not run real agents or connect to Claude, Codex, other model providers, local files, email, or a business account.
- Task activity, approval prompts, and camera-room events are simulated. Nothing is sent, executed, or changed outside this browser demo.
- Do not enter customer, financial, credential, or other private business data.
- Only language and theme preferences are saved in this browser's local storage; sample task state is temporary.

## License status

The Solo Empire application source has not yet been released under an open-source license. This demo repository contains only the compiled browser build, not the Rust core or full application source. The bundled fonts are licensed under the SIL Open Font License 1.1; their license texts are included in `site/licenses/`.
