# My Dotfiles

## Dependencies

### VSCode `settings.json `
My VSCode configuration requires specific fonts and extensions installed to work as intended.

### Font

Icons and editor font:

    Hack Nerd Font Mono (set in editor.fontFamily)

### VS Code Extensions

Needed for Transparency & UI:

    VSCode Custom CSS

        This extension is required for the "custom-ui-style.electron" (transparency) and "custom-ui-style.css" (CSS overrides) settings to function.

        Note: After installing this extension, you must follow its instructions, which usually involve:

            Opening the command palette (Cmd+Shift+P).

            Running Enable Custom CSS and JS.

            Restarting VS Code. You may need to do this as an administrator and re-run it after every VS Code update.

Configured Extensions:

These extensions are required for all settings to be active. If you don't use these extensions, you can safely remove their settings from your settings.json.

    GitHub Copilot (For all github.copilot.* settings)

    Google Gemini Code Assist (For the geminicodeassist.project setting)

    Code Runner (For the code-runner.runInTerminal setting)

    Live Server (For the liveServer.settings.donotShowInfoMsg setting)
