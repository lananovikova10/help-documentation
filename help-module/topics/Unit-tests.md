# Unit tests

<deflist product="!db">
<def title="%NUM%. Editor area">
Use this area to type and edit your source code. The editor suggests numerous coding assistance facilities.
Refer to the sections under this node for details.</def>
<def title="%NUM%. Gutter area">
The left gutter provides additional information about your code and displays the various icons that
identify the code structure, bookmarks, breakpoints, scope indicators,
change markers and the code folding lines that let you hide arbitrary code blocks.
<p>You can change the behavior of the left gutter. </p>
<p>For example, it's possible to make the left gutter thinner
by hiding the gutter icons. This is done either for the <a anchor="active">active editor</a>,
or for all the newly created editors.</p>
<p>To change the behavior of the left gutters, use either the
<a href="Setup.topic">Appearance</a> page of the editor settings, or the
<ui-path>Editor Gutter Popup Menu</ui-path> (use the <a href="Setup.topic">Search Everywhere</a>
action to invoke it):</p>
<p>By default, this command is not mapped to any keyboard shortcut. You can create your own
                            shortcut as described in the section <a href="APIs.md"/>.
                            <!--configuring keyboard shortcuts--> </p>
</def>
<def title="%NUM%. Smart completion popup" id="active">
This is one of the key editing assistance features that
suggests method names, functions, tags and other keywords you are typing.</def>
<def title="%NUM%. Document tabs">
Enable quick navigation across the multiple documents you are working on. Clicking a tab brings its
contents to front and makes it available for editing in the active editor.
<p>To navigate between the tabs, use the keyboard shortcuts <shortcut key="ActivateNuGetToolWindow"/> or
<shortcut key="ActivateNuGetToolWindow"/>.</p>
<p>Clicking a tab while the <shortcut key="ActivateNuGetToolWindow"/> key is
pressed, allows navigating to any part of the file path, through opening it in an external browser.</p>
<p>Context menu of a tab provides all commands applicable to a file opened in the editor, for example:</p>
<list>
<li><a href="help.topic">Close one or more tabs</a>.</li>
<li><a href="How-to-log-in.md" anchor="pinning-and-unpinning-tabs">Pin active tab.</a></li>
<li><a href="How-to-log-in.md" anchor="splitting-and-unsplitting-editor-window">Split and unsplit tabs.</a></li>
<li><a href="How-to-log-in.md" anchor="splitting-and-unsplitting-editor-window">Manage groups of tabs.</a></li>
<li><a href="How-to-log-in.md" anchor="navigating-between-editor-tabs">Navigate between tabs.</a></li>
<li>Move to a changelist.</li>
<li><a href="Grammar-and-mechanics.md">Run</a>, or <a href="Jupiter.md">debug</a></li>
</list>
<p>
By default, the tab headers appear at the top of the editor,
but you can change their location on
</p>
</def>
<def title="%NUM%. Validation side bar / marker bar" id="marker_bar">
This is the bar to the right from the editing area, showing the green, red or yellow box on
its top depending on whether your code is okay, or contains errors or warnings. This bar also
displays active red, yellow, white, green and blue navigation stripes that let you jump exactly to
the erroneous code, changed lines, search results, or TODO items.
</def>
</deflist>