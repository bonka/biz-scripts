# biz-scripts
Short scripts for mundane tasks. Non-programmer. So please help me God.

# Export selected Keynote items to Markdown
This AppleScript converts Keynote slide items to text with Markdown formatting. It lets you export any combination of Title, Body and Presenter notes. The script is customized from Richard Doolings "Send Keynote Text to Desktop Markdown File". I found the previous version too noisy, printing slides and headlines even though no data was present.

## General enhancements:
- **Output selection:** Gives opportunity to select and export content from any combination of Title, Body Text and Presenter Notes.
- Skipped slides are skipped.

## Reduced Noise:
- Only prints slides that has elements with content under current selection.
- Only prints headlines that has content under current selection
- Truncated output for reduced noise —  i.e. If only Notes is selected, its headline will be omitted. If Body and Notes is selected, Body and Notes headline will only display if Body contains text.
