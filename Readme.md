<!-- default file list -->
*Files to look at*:

* [CommandUIBindings.cs](./CS/RichEditCommandExample/CommandUIBindings.cs) (VB: [CommandUIBindings.vb](./VB/RichEditCommandExample/CommandUIBindings.vb))
* [Form1.cs](./CS/RichEditCommandExample/Form1.cs) (VB: [Form1.vb](./VB/RichEditCommandExample/Form1.vb))
* [Program.cs](./CS/RichEditCommandExample/Program.cs) (VB: [Program.vb](./VB/RichEditCommandExample/Program.vb))
<!-- default file list end -->
# How to bind RichEdit commands to buttons, check boxes and other UI elements


<p>This project illustrates how to bind an XtraRichEdit command to the UI element. <br />
A <a href="http://documentation.devexpress.com/#WindowsForms/clsDevExpressXtraEditorsSimpleButtontopic">DevExpress.XtraEditors.SimpleButton</a> button is bound to <a href="http://documentation.devexpress.com/#WindowsForms/clsDevExpressXtraRichEditCommandsUndoCommandtopic">Undo command</a>  via creating a command-enabled descendant. Another <strong>SimpleButton</strong> is bound to <a href="http://documentation.devexpress.com/#WindowsForms/clsDevExpressXtraRichEditCommandsRedoCommandtopic">Redo command</a> via the Command Adapter technique. A <a href="http://documentation.devexpress.com/#WindowsForms/clsDevExpressXtraEditorsCheckEdittopic">CheckEdit</a> is bound to the <a href="http://documentation.devexpress.com/#WindowsForms/clsDevExpressXtraRichEditCommandsToggleFontBoldCommandtopic">ToggleFontBold command</a>. <br />
Once implemented in the application, the command UI elements properly respond to changes in the XtraRichEdit control. This behavior is illustrated by an example, in which the command buttons correctly reflect changes in Undo and Redo command state. Moreover, all command elements are automatically grayed out and disabled when the RichEditControl becomes read-only.</p>

<br/>


