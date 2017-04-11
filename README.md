# biz-scripts
Short scripts for mundane tasks. Non-programmer. So help me God.

## [Export selected Keynote items to Markdown](https://github.com/bonka/biz-scripts/blob/master/Export%20Selected%20Keynote%20items%20to%20Markdown)
This AppleScript converts Keynote slide items to text with Markdown formatting. It lets you export any combination of Title, Body and Presenter notes. The script is customized from Richard Doolings [Send Keynote Text to Desktop Markdown File](https://gist.github.com/RichardDooling/5e616a40d2969ba136a4). I found the previous version too noisy, printing slides and headlines even though no data was present. Also - it didn't skip slides that were skipped.

### General enhancements:
- Output selection: Gives opportunity to select and export content from any combination of Title, Body Text and Presenter Notes.
- Skipped slides are skipped.

### Reduced Noise:
- Only prints slides that has elements with content under current selection.
- Only prints headlines that has content under current selection
- Truncated output for reduced noise —  i.e. If only Notes is selected, its headline will be omitted. If Body and Notes is selected, Body and Notes headline will only display if Body contains text.
