# Release notes · Word Field v0.42.0

## Windows x64 portable preview

This is an unsigned, self-contained .NET 10 x64 desktop host that loads the bundled game assets. It does not require Node.js or a local web server. Microsoft Edge WebView2 Evergreen Runtime is required and is not installed automatically.

### Learning and saved data

- One IELTS-preparation wordbook with 6,550 entries and 12,840 example records.
- The vocabulary is not an official IELTS list. All entries remain pending independent human linguistic review.
- Desktop save data is stored separately from browser saves at `%LOCALAPPDATA%\WordField\WebView2`. Use the app's JSON export/import controls to migrate a browser save.

### Validation

- Automated tests: 249 passed, 0 failed.
- JavaScript syntax checks: passed.
- Isolated WebView2 smoke test: camp rendered; save remained readable after reload.
- This does not establish compatibility across physical Windows devices. The app is unsigned, is not an installer, and has not been submitted to Microsoft Store.

### Third-party content and permissions

The archive retains ECDICT, Tatoeba and OpenCC-derived notices and license files. Keep `app/wwwroot/THIRD_PARTY_NOTICES.md` and the accompanying license texts with the program. The project's own code and original assets do not yet have a declared open-source license; no redistribution, modification, or commercial-use permission is granted by this release note.

### Known limits

- No code-signing certificate or installer.
- No cross-device sync or cloud backup; users must export their own save backup.
- Vocabulary meanings, pronunciations, examples and translations still need independent review.
- TTS uses the local operating system/browser voice and has not been individually audited as recorded audio.

