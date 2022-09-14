# hayile-json
Help us uploading new shortcuts. 
You only must create a Json file, such as the example, and fill with your favourites commands. Please use english language.

And then then create a pull request.

# Shortcuts structure .JSON example:
```json
"name": "Insert a name for example vsc for visual studio code",
  "program": [
    {
      "operativeSystem": "Insert operative system",
      "environment": "Insert environment's name",
      "shortcuts": [
        {
          "title": "Insert a title for section",
          "values": [
            {
              "description": "Show Command Palette",
              "command": "Ctrl + Shift + P or F1"
            }
            ]
      }
    ]
   }
]
```            
            
// If you want agree more commands or sections you can add it.
                 
# Real example:
```json
{
  "name": "vsc",
  "program": [
    {
      "operativeSystem": "Windows",
      "environment": "Visual Studio Code",
      "shortcuts": [
        {
          "title": "General",
          "values": [
            {
              "description": "Show Command Palette",
              "command": "Ctrl + Shift + P or F1"
            },
            {
              "description": "Quick Open, Go to File...",
              "command": "Ctrl + P"
            },
            {
              "description": "New window/instance",
              "command": "Ctrl + Shift + N"
            },
            {
              "description": "Close window/instance",
              "command": "Ctrl + Shift + W"
            },
            {
              "description": "User Settings",
              "command": "Ctrl + ,"
            },
            {
              "description": "Keyboard Shortcuts",
              "command": "Ctrl + K Ctrl + S"
            }
          ]
        },
        {
          "title": "Basic editing",
          "values": [
            {
              "description": "Cut line (empty selection)",
              "command": "Ctrl + X"
            },
            {
              "description": "Copy line (empty selection)",
              "command": "Ctrl + C"
            },
            {
              "description": "Move line up/down",
              "command": "Alt + ↑ / ↓"
            },
            {
              "description": "Copy line up/down",
              "command": "Shift + Alt + ↓ / ↑"
            },
            {
              "description": "Delete line",
              "command": "Ctrl + Shift + K"
            },
            {
              "description": "Insert line below",
              "command": "Ctrl + Enter"
            },
            {
              "description": "Insert line above",
              "command": "Ctrl + Shift + Enter"
            },
            {
              "description": "Jump to matching bracket",
              "command": "Ctrl + Shift + \\ "
            },
            {
              "description": " Indent / outdent line",
              "command": "Ctrl + ] / ["
            },
            {
              "description": "Go to beginning/end of line",
              "command": "Home / End"
            },
            {
              "description": "Go to beginning of file",
              "command": "Ctrl + Home"
            },
            {
              "description": "Go to end of file",
              "command": "Ctrl + End"
            },
            {
              "description": "Scroll line up/down",
              "command": "Ctrl + ↑ / ↓"
            },
            {
              "description": "Scroll page up/down",
              "command": "Alt + PgUp / PgDn"
            },
            {
              "description": "Fold (collapse) region",
              "command": "Ctrl + Shift + ["
            },
            {
              "description": "Unfold (uncollapse) region",
              "command": "Ctrl + Shift + ]"
            },
            {
              "description": "Fold (collapse) all subregions",
              "command": "Ctrl + K Ctrl + ["
            },
            {
              "description": "Unfold (uncollapse) all subregions",
              "command": "Ctrl + K Ctrl + ]"
            },
            {
              "description": "Fold (collapse) all regions",
              "command": "Ctrl + K Ctrl + 0"
            },
            {
              "description": "Unfold (uncollapse) all regions",
              "command": "Ctrl + K Ctrl + J"
            },
            {
              "description": "Add line comment",
              "command": "Ctrl + K Ctrl + C"
            },
            {
              "description": "Remove line comment",
              "command": "Ctrl + K Ctrl + U"
            },
            {
              "description": "Toggle line comment",
              "command": "Ctrl + /"
            },
            {
              "description": "Toggle block comment",
              "command": "Shift + Alt + A"
            },
            {
              "description": "Toggle word wrap",
              "command": "Alt + Z"
            }
          ]
        },
        {
          "title": "Navigation",
          "values": [
            {
              "description": "Show all Symbols",
              "command": "Ctrl + T"
            },
            {
              "description": "Go to Line...",
              "command": "Ctrl + G"
            },
            {
              "description": "Go to File...",
              "command": "Ctrl + P"
            },
            {
              "description": "Go to Symbol...",
              "command": "Ctrl + Shift + O"
            },
            {
              "description": "Show Problems panel",
              "command": "Ctrl + Shift + M"
            },
            {
              "description": "Go to next error or warning",
              "command": "F8"
            },
            {
              "description": "Go to previous error or warning",
              "command": "Shift + F8"
            },
            {
              "description": "Navigate editor group history",
              "command": "Ctrl + Shift + Tab"
            },
            {
              "description": "Go back / forward",
              "command": "Alt + ← / →"
            },
            {
              "description": "Toggle Tab moves focus",
              "command": "Ctrl+M"
            }
          ]
        },
        {
          "title": "Search and replace",
          "values": [
            {
              "description": "Find",
              "command": "Ctrl + F"
            },
            {
              "description": "Replace",
              "command": "Ctrl + H"
            },
            {
              "description": "Find next/previous",
              "command": "F3 / Shift + F3"
            },
            {
              "description": "Select all occurences of Find match",
              "command": "Alt + Enter"
            },
            {
              "description": "Add selection to next Find match",
              "command": "Ctrl + D"
            },
            {
              "description": "Move last selection to next Find match",
              "command": "Ctrl + K Ctrl + D"
            },
            {
              "description": "Toggle case-sensitive / regex / whole word",
              "command": "Alt + C / R / W"
            }
          ]
        },
        {
          "title": "Multi-cursor and selection",
          "values": [
            {
              "description": "Insert cursor",
              "command": "Alt + Click"
            },
            {
              "description": "Insert cursor above / below",
              "command": "Ctrl + Alt + ↑ / ↓"
            },
            {
              "description": "Undo last cursor operation",
              "command": "Ctrl + U"
            },
            {
              "description": "Insert cursor at end of each line selected",
              "command": "Shift + Alt + I"
            },
            {
              "description": "Select current line",
              "command": "Ctrl + L"
            },
            {
              "description": "Select all occurrences of current selection",
              "command": "Ctrl + Shift + L"
            },
            {
              "description": "Select all occurrences of current word",
              "command": "Ctrl + F2"
            },
            {
              "description": "Expand selection",
              "command": "Shift + Alt + →"
            },
            {
              "description": "Shrink selection",
              "command": "Shift + Alt + ←"
            },
            {
              "description": "Column (page) selection",
              "command": "Ctrl+Shift+Alt + (arrow key)"
            },
            {
              "description": "Column (page) selection page up/down",
              "command": "Ctrl+Shift+Alt + PgUp/PgDn"
            }
          ]
        },
        {
          "title": "Rich languages editing",
          "values": [
            {
              "description": "Trigger suggestion",
              "command": "Ctrl + Space, Ctrl + I"
            },
            {
              "description": "Trigger parameter hints",
              "command": "Ctrl + Shift + Space"
            },
            {
              "description": "Format document",
              "command": "Shift + Alt + F"
            },
            {
              "description": "Format selection",
              "command": "Ctrl + K Ctrl + F"
            },
            {
              "description": "Go to Definition",
              "command": "F12"
            },
            {
              "description": "Peek Definition",
              "command": "Alt + F12"
            },
            {
              "description": "Open Definition to the side",
              "command": "Ctrl + K or F12"
            },
            {
              "description": "Quick Fix",
              "command": "Ctrl + ."
            },
            {
              "description": "Show References",
              "command": "Shift + F12"
            },
            {
              "description": "Rename Symbol",
              "command": "F2"
            },
            {
              "description": "Trim trailing whitespace",
              "command": "Ctrl + K or Ctrl + X"
            },
            {
              "description": "Change file language",
              "command": "Ctrl + K M"
            }
          ]
        },
        {
          "title": "Editor management",
          "values": [
            {
              "description": "Close editor",
              "command": "Ctrl + F4, Ctrl + W"
            },
            {
              "description": "Close folder",
              "command": "Ctrl + K F"
            },
            {
              "description": "Split editor",
              "command": "Ctrl + \\ "
            },
            {
              "description": "Focus into 1st, 2nd or 3rd editor group",
              "command": "Ctrl + 1 / 2 / 3"
            },
            {
              "description": "Focus into previous/next editor group",
              "command": "Ctrl + K Ctrl + ←/→"
            },
            {
              "description": "Move editor left/right",
              "command": "Ctrl + Shift+PgUp / PgDn"
            },
            {
              "description": "Move active editor group",
              "command": "Ctrl + K ← / →"
            }
          ]
        },
        {
          "title": "File management",
          "values": [
            {
              "description": "New File",
              "command": "Ctrl + N"
            },
            {
              "description": "Open File...",
              "command": "Ctrl + O"
            },
            {
              "description": "Save",
              "command": "Ctrl + S"
            },
            {
              "description": "Save As...",
              "command": "Ctrl + Shift + S"
            },
            {
              "description": "Save All",
              "command": "Ctrl + K S"
            },
            {
              "description": "Close",
              "command": "Ctrl + F4"
            },
            {
              "description": "Close All",
              "command": "Ctrl + K Ctrl + W"
            },
            {
              "description": "Reopen closed editor",
              "command": "Ctrl + Shift + T"
            },
            {
              "description": "Keep preview mode editor open",
              "command": "Ctrl + K Enter"
            },
            {
              "description": "Open next",
              "command": "Ctrl + Tab"
            },
            {
              "description": "Open previous",
              "command": "Ctrl + Shift + Tab"
            },
            {
              "description": "Copy path of active file",
              "command": "Ctrl + K P"
            },
            {
              "description": "Reveal active file in Explorer",
              "command": "Ctrl + K R"
            },
            {
              "description": "Show active file in new window/instance",
              "command": "Ctrl + K O"
            }
          ]
        },
        {
          "title": "Display",
          "values": [
            {
              "description": "Toggle full screen",
              "command": "F11"
            },
            {
              "description": "Toggle editor layout (horizontal/vertical)",
              "command": "Shift + Alt + 0"
            },
            {
              "description": "Zoom in/out",
              "command": "Ctrl+ = / -"
            },
            {
              "description": "Toggle Sidebar visibility",
              "command": "Ctrl + B"
            },
            {
              "description": "Show Explorer / Toggle focus",
              "command": "Ctrl + Shift + E"
            },
            {
              "description": "Show Search",
              "command": "Ctrl + Shift + F"
            },
            {
              "description": "Show Source Control",
              "command": "Ctrl + Shift + G"
            },
            {
              "description": "Show Debug",
              "command": "Ctrl + Shift + D"
            },
            {
              "description": "Show Extensions",
              "command": "Ctrl + Shift + X"
            },
            {
              "description": "Replace in files",
              "command": "Ctrl + Shift + H"
            },
            {
              "description": "Toggle Search details",
              "command": "Ctrl + Shift + J"
            },
            {
              "description": "Show Output panel",
              "command": "Ctrl + Shift + U"
            },
            {
              "description": "Open Markdown preview",
              "command": "Ctrl + Shift + V"
            },
            {
              "description": "Open Markdown preview to the side",
              "command": "Ctrl + K V"
            },
            {
              "description": "Zen Mode (Esc Esc to exit)",
              "command": "Ctrl + K Z"
            }
          ]
        },
        {
          "title": "Debug",
          "values": [
            {
              "description": "Toggle breakpoint",
              "command": "F9"
            },
            {
              "description": "Start/Continue",
              "command": "F5"
            },
            {
              "description": "Stop",
              "command": "Shift + F5"
            },
            {
              "description": "Step into/out",
              "command": "F11 / Shift + F11"
            },
            {
              "description": "Step over",
              "command": "F10"
            },
            {
              "description": "Show hover",
              "command": "Ctrl + K Ctrl + I"
            }
          ]
        },
        {
          "title": "Integrated terminal",
          "values": [
            {
              "description": "Show integrated terminal",
              "command": "Ctrl + `"
            },
            {
              "description": "Create new terminal",
              "command": "Ctrl + Shift + `"
            },
            {
              "description": "Copy selection",
              "command": "Ctrl + C"
            },
            {
              "description": "Paste into active terminal",
              "command": "Ctrl + V"
            },
            {
              "description": "Scroll up/down",
              "command": "Ctrl + ↑ / ↓"
            },
            {
              "description": "Scroll page up/down",
              "command": "Shift + PgUp / PgDn"
            },
            {
              "description": "Scroll to top/bottom",
              "command": "Ctrl + Home / End"
            }
          ]
        }
      ]
    },
    {
      "operativeSystem": "Mac",
      "environment": "Visual Studio Code",
      "shortcuts": [
        {
          "title": "General",
          "values": [
            {
              "description": "Show Command Palette",
              "command": "⇧ ⌘ P, F1"
            },
            {
              "description": "Quick Open, Go to File...",
              "command": "⌘ P"
            },
            {
              "description": "New window/instance",
              "command": "⇧ ⌘ N"
            },
            {
              "description": "Close window/instance",
              "command": "⌘ W"
            },
            {
              "description": "User Settings",
              "command": "⌘ ,"
            },
            {
              "description": "Keyboard Shortcuts",
              "command": "⌘ K ⌘ S"
            }
          ]
        },
        {
          "title": "Basic editing",
          "values": [
            {
              "description": "Cut line (empty selection)",
              "command": "⌘ X"
            },
            {
              "description": "Copy line (empty selection)",
              "command": "⌘ C"
            },
            {
              "description": "Move line up/down",
              "command": "⌥ ↓ / ⌥ ↑"
            },
            {
              "description": "Copy line up/down",
              "command": "⇧ ⌥ ↓ / ⇧ ⌥ ↑"
            },
            {
              "description": "Delete line",
              "command": "⇧ ⌘ K"
            },
            {
              "description": "Insert line below / above",
              "command": "⌘ ↩️ / ⇧ ⌘ ↩️"
            },
            {
              "description": "Jump to matching bracket",
              "command": "⇧ ⌘ \\ "
            },
            {
              "description": " Indent / outdent line",
              "command": "⌘ ] / ⌘ ["
            },
            {
              "description": "Go to beginning/end of line",
              "command": "Home / End"
            },
            {
              "description": "Go to beginning/end of file",
              "command": "⌘ ↑ / ⌘ ↓"
            },
            {
              "description": "Scroll line up/down",
              "command": "⌃ PgUp / ⌃ PgDn"
            },
            {
              "description": "Scroll page up/down",
              "command": "⌘ PgUp /⌘ PgDn"
            },
            {
              "description": "Fold/unfold region",
              "command": "⌥ ⌘ [ / ⌥ ⌘ ]"
            },
            {
              "description": "Fold/unfold all subregions",
              "command": "⌘ K ⌘ [ / ⌘ K ⌘ ]"
            },
            {
              "description": "Fold/unfold all regions",
              "command": "⌘ K ⌘ 0 / ⌘ K ⌘ J"
            },
            {
              "description": "Add line comment",
              "command": "⌘ K ⌘ C"
            },
            {
              "description": "Remove line comment",
              "command": "⌘ K ⌘ U"
            },
            {
              "description": "Toggle line comment",
              "command": "⌘ /"
            },
            {
              "description": "Toggle block comment",
              "command": "⇧ ⌥ A"
            },
            {
              "description": "Toggle word wrap",
              "command": "⌥ Z"
            }
          ]
        },
        {
          "title": "Navigation",
          "values": [
            {
              "description": "Show all Symbols",
              "command": "⌘ T"
            },
            {
              "description": "Go to Line...",
              "command": "⌃ G"
            },
            {
              "description": "Go to File...",
              "command": "⌘ P"
            },
            {
              "description": "Go to Symbol...",
              "command": "⇧ ⌘ O"
            },
            {
              "description": "Show Problems panel",
              "command": "⇧ ⌘ M"
            },
            {
              "description": "Go to next/previous error or warning",
              "command": "F8 / ⇧ F8"
            },
            {
              "description": "Navigate editor group history",
              "command": "⌃ ⇧ Tab"
            },
            {
              "description": "Go back / forward",
              "command": "⌃ - / ⌃ ⇧"
            },
            {
              "description": "Toggle Tab moves focus",
              "command": "⌃ ⇧ M"
            }
          ]
        },
        {
          "title": "Search and replace",
          "values": [
            {
              "description": "Find",
              "command": "⌘ F"
            },
            {
              "description": "Replace",
              "command": "⌥ ⌘ F"
            },
            {
              "description": "Find next/previous",
              "command": "⌘ G / ⇧ ⌘ G"
            },
            {
              "description": "Select all occurences of Find match",
              "command": "⌥ ↩️"
            },
            {
              "description": "Add selection to next Find match",
              "command": "⌘ D"
            },
            {
              "description": "Move last selection to next Find match",
              "command": "⌘ K ⌘ D"
            }
          ]
        },
        {
          "title": "Multi-cursor and selection",
          "values": [
            {
              "description": "Insert cursor",
              "command": "⌥ + click "
            },
            {
              "description": "Insert cursor below",
              "command": "⌥ ⌘ ↓"
            },
            {
              "description": "Undo last cursor operation",
              "command": "⌘ U"
            },
            {
              "description": "Insert cursor at end of each line selected",
              "command": "⇧ ⌥ I"
            },
            {
              "description": "Select current line",
              "command": "⌘ I"
            },
            {
              "description": "Select all occurrences of current selection",
              "command": "⇧ ⌘ L"
            },
            {
              "description": "Select all occurrences of current word",
              "command": "⌘ F2"
            },
            {
              "description": "Expand / Shrink selection",
              "command": "⌃ ⇧ ⌘ → / ←"
            },
            {
              "description": "Column (box) selection",
              "command": "⇧ ⌥ + drag mouse"
            },
            {
              "description": "Column (box) selection up/down",
              "command": "⇧ ⌥ ⌘ ↑ / ↓"
            },
            {
              "description": "Column (box) selection left/right",
              "command": "⇧ ⌥ ⌘ ← / →"
            },
            {
              "description": "Column (box) selection page up",
              "command": "⇧ ⌥ ⌘ PgUp"
            },
            {
              "description": "Column (box) selection page down",
              "command": "⇧ ⌥ ⌘ PgDn"
            }
          ]
        },
        {
          "title": "Rich languages editing",
          "values": [
            {
              "description": "Trigger suggestion",
              "command": "⌃ Space"
            },
            {
              "description": "Trigger parameter hints",
              "command": "⇧ ⌘ Space"
            },
            {
              "description": "Format document",
              "command": "⇧ ⌥ F"
            },
            {
              "description": "Format selection",
              "command": "⌘ K ⌘ F"
            },
            {
              "description": "Go to Definition",
              "command": "F12"
            },
            {
              "description": "Peek Definition",
              "command": "⌥ F12"
            },
            {
              "description": "Open Definition to the side",
              "command": "⌘ K F12"
            },
            {
              "description": "Quick Fix",
              "command": "⌘ ."
            },
            {
              "description": "Show References",
              "command": "⇧ F12"
            },
            {
              "description": "Rename Symbol",
              "command": "F2"
            },
            {
              "description": "Trim trailing whitespace",
              "command": "⌘ K ⌘ X"
            },
            {
              "description": "Change file language",
              "command": "⌘ K M"
            }
          ]
        },
        {
          "title": "Editor management",
          "values": [
            {
              "description": "Close editor",
              "command": "⌘ W"
            },
            {
              "description": "Close folder",
              "command": " ⌘ K F"
            },
            {
              "description": "Split editor",
              "command": "⌘ \\ "
            },
            {
              "description": "Focus into 1st, 2nd or 3rd editor group",
              "command": "⌘ 1 / ⌘ 2 / ⌘ 3"
            },
            {
              "description": "Focus into previous/next editor group",
              "command": "⌘ K ⌘ ← / ⌘ K ⌘ →"
            },
            {
              "description": "Move editor left/right",
              "command": "⌘ K ⇧ ⌘ ← / ⌘ K ⇧ ⌘ → "
            },
            {
              "description": "Move active editor group",
              "command": "⌘ K ← / ⌘ K →"
            }
          ]
        },
        {
          "title": "File management",
          "values": [
            {
              "description": "New File",
              "command": "⌘ N"
            },
            {
              "description": "Open File...",
              "command": "⌘ O"
            },
            {
              "description": "Save",
              "command": "⌘ S"
            },
            {
              "description": "Save As...",
              "command": "⇧ ⌘ S"
            },
            {
              "description": "Save All",
              "command": "⌥ ⌘ S"
            },
            {
              "description": "Close",
              "command": "⌘ W"
            },
            {
              "description": "Close All",
              "command": "⌘ K ⌘ W"
            },
            {
              "description": "Reopen closed editor",
              "command": "⇧ ⌘ T"
            },
            {
              "description": "Keep preview mode editor open",
              "command": "⌘ K ↩️"
            },
            {
              "description": "Open next",
              "command": "Ctrl + Tab"
            },
            {
              "description": "Open previous",
              "command": "⌃ Tab / ⌃ ⇧ Tab"
            },
            {
              "description": "Copy path of active file",
              "command": "⌘ K P"
            },
            {
              "description": "Reveal active file in Explorer",
              "command": "⌘ K R"
            },
            {
              "description": "Show active file in new window/instance",
              "command": "⌘ K O"
            }
          ]
        },
        {
          "title": "Display",
          "values": [
            {
              "description": "Toggle full screen",
              "command": "⌃ ⌘ F"
            },
            {
              "description": "Toggle editor layout (horizontal/vertical)",
              "command": "⌥ ⌘ 0"
            },
            {
              "description": "Zoom in/out",
              "command": "⌘ = / ⇧ ⌘ -"
            },
            {
              "description": "Toggle Sidebar visibility",
              "command": "⌘ B"
            },
            {
              "description": "Show Explorer / Toggle focus",
              "command": "⇧ ⌘ E"
            },
            {
              "description": "Show Search",
              "command": "⇧ ⌘ F"
            },
            {
              "description": "Show Source Control",
              "command": "⌃ ⇧ G"
            },
            {
              "description": "Show Debug",
              "command": "⇧ ⌘ D"
            },
            {
              "description": "Show Extensions",
              "command": "⇧ ⌘ X"
            },
            {
              "description": "Replace in files",
              "command": "⇧ ⌘ H"
            },
            {
              "description": "Toggle Search details",
              "command": "⇧ ⌘ J"
            },
            {
              "description": "Show Output panel",
              "command": "⇧ ⌘ U"
            },
            {
              "description": "Open Markdown preview",
              "command": "⇧ ⌘ V"
            },
            {
              "description": "Open Markdown preview to the side",
              "command": "⌘ K V"
            },
            {
              "description": "Zen Mode (Esc Esc to exit)",
              "command": "⌘ K Z"
            }
          ]
        },
        {
          "title": "Debug",
          "values": [
            {
              "description": "Toggle breakpoint",
              "command": "F9"
            },
            {
              "description": "Start/Continue",
              "command": "F5"
            },
            {
              "description": "Stop",
              "command": "⇧ F5"
            },
            {
              "description": "Step into/out",
              "command": "F11 / ⇧ F11"
            },
            {
              "description": "Step over",
              "command": "F10"
            },
            {
              "description": "Show hover",
              "command": "⌘ K ⌘ I"
            }
          ]
        },
        {
          "title": "Integrated terminal",
          "values": [
            {
              "description": "Show integrated terminal",
              "command": "⌃ `"
            },
            {
              "description": "Create new terminal",
              "command": "⌃ ⇧ `"
            },
            {
              "description": "Copy selection",
              "command": "⌘ C"
            },
            {
              "description": "Paste into active terminal",
              "command": "⌘ V"
            },
            {
              "description": "Scroll up/down",
              "command": "⌘ ↑ / ↓"
            },
            {
              "description": "Scroll page up/down",
              "command": "PgUp / PgDn "
            },
            {
              "description": "Scroll to top/bottom",
              "command": "⌘ Home / End"
            }
          ]
        }
      ]
    },
    {
      "operativeSystem": "Linux",
      "environment": "Visual Studio Code",
      "shortcuts": [
        {
          "title": "General",
          "values": [
            {
              "description": "Show Command Palette",
              "command": "Ctrl + Shift + P, F1 "
            },
            {
              "description": "Quick Open, Go to File...",
              "command": "Ctrl + P"
            },
            {
              "description": "New window/instance",
              "command": "Ctrl + Shift + N"
            },
            {
              "description": "Close window/instance",
              "command": "Ctrl + W"
            },
            {
              "description": "User Settings",
              "command": "Ctrl + ,"
            },
            {
              "description": "Keyboard Shortcuts",
              "command": "Ctrl + K Ctrl + S"
            }
          ]
        },
        {
          "title": "Basic editing",
          "values": [
            {
              "description": "Cut line (empty selection)",
              "command": "Ctrl + X"
            },
            {
              "description": "Copy line (empty selection)",
              "command": "Ctrl + C"
            },
            {
              "description": "Move line up/down",
              "command": "Alt + ↓ / ↑"
            },
            {
              "description": "Delete line",
              "command": "Ctrl + Shift + K"
            },
            {
              "description": "Insert line below / above",
              "command": "Ctrl+Enter / Ctrl+Shift+Enter"
            },
            {
              "description": "Jump to matching bracket",
              "command": "Ctrl + Shift + \\ "
            },
            {
              "description": " Indent / outdent line",
              "command": "Ctrl + ] / Ctrl + ["
            },
            {
              "description": "Go to beginning/end of line",
              "command": "Home / End"
            },
            {
              "description": "Go to beginning/end of file",
              "command": "Ctrl + Home / End"
            },
            {
              "description": "Scroll line up/down",
              "command": "Ctrl + ↑ / ↓"
            },
            {
              "description": "Scroll page up/down",
              "command": "Alt + PgUp / PgDn"
            },
            {
              "description": "Fold/unfold region",
              "command": "Ctrl + Shift + [ / ]"
            },
            {
              "description": "Fold/unfold all subregions",
              "command": "Ctrl + K Ctrl + [ / ]"
            },
            {
              "description": "Fold/unfold all regions",
              "command": "Ctrl + K Ctrl + 0 / Ctrl + K Ctrl + J"
            },
            {
              "description": "Add line comment",
              "command": "Ctrl + K Ctrl + C"
            },
            {
              "description": "Remove line comment",
              "command": "Ctrl + K Ctrl + U"
            },
            {
              "description": "Toggle line comment",
              "command": "Ctrl + /"
            },
            {
              "description": "Toggle block comment",
              "command": "Ctrl + Shift + A"
            },
            {
              "description": "Toggle word wrap",
              "command": "Alt + Z"
            }
          ]
        },
        {
          "title": "Rich languages editing",
          "values": [
            {
              "description": "Trigger suggestion",
              "command": "Ctrl + Space, Ctrl + I"
            },
            {
              "description": "Trigger parameter hints",
              "command": "Ctrl + Shift + Space"
            },
            {
              "description": "Format document",
              "command": "Ctrl + Shift + I"
            },
            {
              "description": "Format selection",
              "command": "Ctrl + K Ctrl +F "
            },
            {
              "description": "Go to Definition",
              "command": "F12"
            },
            {
              "description": "Peek Definition",
              "command": "Ctrl + Shift + F10"
            },
            {
              "description": "Open Definition to the side",
              "command": "Ctrl + K F12"
            },
            {
              "description": "Quick Fix",
              "command": "Ctrl + ."
            },
            {
              "description": "Show References",
              "command": "Shift + F12"
            },
            {
              "description": "Rename Symbol",
              "command": "F2"
            },
            {
              "description": "Trim trailing whitespace",
              "command": "Ctrl + K Ctrl + X"
            },
            {
              "description": "Change file language",
              "command": "Ctrl + K M"
            }
          ]
        },
        {
          "title": "Multi-cursor and selection",
          "values": [
            {
              "description": "Insert cursor",
              "command": "Alt + Click "
            },
            {
              "description": "Insert cursor above/below",
              "command": "Shift + Alt + ↑ / ↓"
            },
            {
              "description": "Undo last cursor operation",
              "command": "Ctrl + U"
            },
            {
              "description": "Insert cursor at end of each line selected",
              "command": "Shift + Alt + I"
            },
            {
              "description": "Select current line",
              "command": "Ctrl + L"
            },
            {
              "description": "Select all occurrences of current selection",
              "command": "Ctrl + Shift + L"
            },
            {
              "description": "Select all occurrences of current word",
              "command": "Ctrl + F2"
            },
            {
              "description": "Expand / Shrink selection",
              "command": "Shift + Alt + → / Shift+Alt + ←"
            },
            {
              "description": "Column (box) selection",
              "command": "Shift+Alt + drag mouse"
            }
          ]
        },
        {
          "title": "Display",
          "values": [
            {
              "description": "Toggle full screen",
              "command": "F11"
            },
            {
              "description": "Toggle editor layout (horizontal/vertical)",
              "command": "Shift + Alt + 0"
            },
            {
              "description": "Zoom in/out",
              "command": "Ctrl + = / -"
            },
            {
              "description": "Toggle Sidebar visibility",
              "command": "Ctrl + B "
            },
            {
              "description": "Show Explorer / Toggle focus",
              "command": "Ctrl + Shift+E"
            },
            {
              "description": "Show Search",
              "command": "Ctrl + Shift + F"
            },
            {
              "description": "Show Source Control",
              "command": "Ctrl + Shift+G "
            },
            {
              "description": "Show Debug",
              "command": "Ctrl + Shift + G "
            },
            {
              "description": "Show Extensions",
              "command": "Ctrl + Shift + X "
            },
            {
              "description": "Replace in files",
              "command": "Ctrl + Shift + H "
            },
            {
              "description": "Toggle Search details",
              "command": "Ctrl + Shift + J"
            },
            {
              "description": "Open new command prompt/terminal",
              "command": "Ctrl + Shift + C"
            },
            {
              "description": "Show Output panel",
              "command": "Ctrl + K Ctrl + H"
            },
            {
              "description": "Open Markdown preview",
              "command": "Ctrl + Shift + V"
            },
            {
              "description": "Open Markdown preview to the side",
              "command": "Ctrl + K V"
            },
            {
              "description": "Zen Mode (Esc Esc to exit)",
              "command": "Ctrl + K Z "
            }
          ]
        },
        {
          "title": "Search and replace",
          "values": [
            {
              "description": "Find",
              "command": "Ctrl + F"
            },
            {
              "description": "Replace",
              "command": "Ctrl + H"
            },
            {
              "description": "Find next/previous",
              "command": "F3 / Shift+F3"
            },
            {
              "description": "Select all occurences of Find match",
              "command": "Alt + Enter"
            },
            {
              "description": "Add selection to next Find match",
              "command": "Ctrl + D"
            },
            {
              "description": "Move last selection to next Find match",
              "command": "Ctrl + K Ctrl + D"
            }
          ]
        },
        {
          "title": "Navigation",
          "values": [
            {
              "description": "Show all Symbols",
              "command": "Ctrl + T"
            },
            {
              "description": "Go to Line...",
              "command": "Ctrl + G"
            },
            {
              "description": "Go to File...",
              "command": "Ctrl + P"
            },
            {
              "description": "Go to Symbol...",
              "command": "Ctrl + Shift + O"
            },
            {
              "description": "Show Problems panel",
              "command": "Ctrl + Shift + M"
            },
            {
              "description": "Go to next/previous error or warning",
              "command": "F8 / Shift + F8"
            },
            {
              "description": "Navigate editor group history",
              "command": "Ctrl + Shift + Tab"
            },
            {
              "description": "Go back / forward",
              "command": "Ctrl + Alt + - / Ctrl + Shift  + -"
            },
            {
              "description": "Toggle Tab moves focus",
              "command": "Ctrl + M"
            }
          ]
        },
        {
          "title": "Editor management",
          "values": [
            {
              "description": "Close editor",
              "command": "Ctrl + W"
            },
            {
              "description": "Close folder",
              "command": " Ctrl + K F"
            },
            {
              "description": "Split editor",
              "command": "Ctrl + \\"
            },
            {
              "description": "Focus into 1st, 2nd or 3rd editor group",
              "command": "Ctrl + 1 / 2 / 3"
            },
            {
              "description": "Focus into previous/next editor group",
              "command": "Ctrl + K Ctrl + ← / Ctrl + K Ctrl + →"
            },
            {
              "description": "Move editor left/right",
              "command": "Ctrl + Shift+PgUp / Ctrl + Shift + PgDn → "
            },
            {
              "description": "Move active editor group",
              "command": "Ctrl + K ← / Ctrl+K →"
            }
          ]
        },
        {
          "title": "File management",
          "values": [
            {
              "description": "New File",
              "command": "Ctrl + N "
            },
            {
              "description": "Open File...",
              "command": "Ctrl + O "
            },
            {
              "description": "Save",
              "command": "Ctrl + S"
            },
            {
              "description": "Save As...",
              "command": "Ctrl + Shift + S"
            },
            {
              "description": "Close",
              "command": "Ctrl + W "
            },
            {
              "description": "Close All",
              "command": "Ctrl + K Ctrl + W "
            },
            {
              "description": "Reopen closed editor",
              "command": "Ctrl + Shift + T"
            },
            {
              "description": "Keep preview mode editor open",
              "command": "Ctrl + K Enter "
            },
            {
              "description": "Open next",
              "command": "Ctrl + Tab "
            },
            {
              "description": "Open previous",
              "command": "Ctrl + Shift + Tab"
            },
            {
              "description": "Copy path of active file",
              "command": "Ctrl + K P"
            },
            {
              "description": "Reveal active file in Explorer",
              "command": "Ctrl + K R"
            },
            {
              "description": "Show active file in new window/instance",
              "command": "Ctrl + K O "
            }
          ]
        },
        {
          "title": "Debug",
          "values": [
            {
              "description": "Toggle breakpoint",
              "command": "F9"
            },
            {
              "description": "Start/Continue",
              "command": "F5"
            },
            {
              "description": "Step into/out",
              "command": "F11 / Shift+F11"
            },
            {
              "description": "Step over",
              "command": "F10"
            },
            {
              "description": "Stop",
              "command": "Shift + F5"
            },
            {
              "description": "Show hover",
              "command": "Ctrl + K Ctrl + I"
            }
          ]
        },
        {
          "title": "Integrated terminal",
          "values": [
            {
              "description": "Show integrated terminal",
              "command": "Ctrl + `"
            },
            {
              "description": "Create new terminal",
              "command": "Ctrl + Shift + `"
            },
            {
              "description": "Copy selection",
              "command": "Ctrl + Shift + C"
            },
            {
              "description": "Paste into active terminal",
              "command": "Ctrl + Shift + V"
            },
            {
              "description": "Scroll up/down",
              "command": "Ctrl + Shift + ↑ / ↓ "
            },
            {
              "description": "Scroll page up/down",
              "command": "Shift + PgUp / PgDn  "
            },
            {
              "description": "Scroll to top/bottom",
              "command": "Shift + Home / End "
            }
          ]
        }
      ]
    }
  ]
}

```
