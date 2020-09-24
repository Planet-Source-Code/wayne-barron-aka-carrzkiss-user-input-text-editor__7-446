<div align="center">

## User Input Text Editor


</div>

### Description

Updated on May 06, 2005

This was made with Delphi 6.02 Professional

And will work with Delphi 5 not sure about any version below. Give it a try with Versions below 5 and email me please.

For Beginners to Intermediate

This is an intense tutorial on how to create a text editor. Thought that I add something to this sight, instead of just always taken from it. This tutorial is very detailed on what needs to be done, and all source codes are highlighted. With a grayed background.

I am very proud of this tutorial and would really like to hear from you, about how you feel about it, and would like for you to votes for us on it. Rather good or bad.

Thank you and please enjoy

For the images that are used in the editor. that go with the tutorial please click on the email link below. Add Editor Images to the Subject Heading.

And someone here at the office will try and find them for you, as this project is very old.

And we are not sure if the actual code for it was destroyed or not.

But please feel free to contact us anyway, if just to say hello :-)

Thanks All;

Wayne &amp; Carr Barron

Carrz-Fox-Fire Promotions

(Please check out our other code samples and Delphi Registry Backup information as well)
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Wayne Barron aka: Carrzkiss](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/wayne-barron-aka-carrzkiss.md)
**Level**          |Intermediate
**User Rating**    |4.7 (66 globes from 14 users)
**Compatibility**  |Delphi 6, Delphi 5
**Category**       |[Internet/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-html__7-34.md)
**World**          |[Delphi](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/delphi.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/wayne-barron-aka-carrzkiss-user-input-text-editor__7-446/archive/master.zip)





### Source Code

<DIV><FONT face=Arial size=2><FONT color=#000080 size=4><STRONG>Carrz-Fox-Fire
Promotions </STRONG></FONT></FONT></DIV>
<DIV><FONT face=Arial color=#000080><STRONG>I ask that if you like what I have
for you here, to please Vote for me.</STRONG></FONT></DIV>
<DIV><FONT face=Arial color=#000080><STRONG>This is the only thing that I have
going on at the moment is learning</STRONG></FONT></DIV>
<DIV><FONT face=Arial color=#000080><STRONG>Delphi, have Created 6 fully
functional apps, and the best of all</STRONG></FONT></DIV>
<DIV><FONT face=Arial color=#000080><STRONG>raising my son on my
own.</STRONG></FONT></DIV>
<DIV></DIV>
<DIV><FONT face=Arial color=#000080><STRONG>Time to Rock 'n'
Roll</STRONG></FONT></DIV>
<DIV>
 <p><FONT face=Arial color=#000080><STRONG>Have Fun!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!</STRONG></FONT></p>
 <p><strong><font face="Arial" color="#000080">Edited Contents: May 23rd, 2006</font></strong><b><br>
 <br>
 </b></p>
</DIV>
<DIV><STRONG><FONT face=Arial color=#000080 size=2>{Source code is available
upon request and votes only!!}</FONT></STRONG></DIV>
<DIV><FONT face=Arial size=2><FONT color=#000080 size=4></FONT></FONT></DIV>
<DIV><STRONG><FONT color=#000080 size=4><U>Updated on Oct. 19, 2001</U></FONT><U>
 </U><FONT color=#000080
size=4><<<<<<<<<<---------</FONT></STRONG> </DIV>
<DIV><FONT color=#000080></FONT></DIV>
<DIV></DIV>
<DIV><STRONG><FONT color=#0000ff size=3><U>New code added on Oct. 19, 2001
</U><FONT
color=#000000><<<<<<<<<<<<<<<<<<<<<<-----------------
L<FONT color=#ff0000>oo</FONT>k <FONT color=#0000ff>:</FONT>~</FONT><FONT
color=#ff0000>)</FONT></FONT></STRONG></DIV>
<DIV><STRONG><FONT color=#0000ff size=3><U>New codes are located at the Bottom
of article </U><FONT color=#000000><FONT
color=#000000><<<<<<<<<<<<<<<<<<<<<<------------------L<FONT
color=#ff0000>oo</FONT>k <FONT color=#0000ff>:</FONT>~<FONT
color=#ff0000>)</FONT></FONT></FONT></FONT></STRONG></DIV>
<DIV><FONT color=#0000ff size=3><STRONG><U>(Save As, Print, Drag & Drop,
Lines in TStatusBar)</U><FONT color=#000000> <FONT
color=#000000><<<<<<<<<<<<<<<<<<<<<<------------------L<FONT
color=#ff0000>oo</FONT>k <FONT color=#0000ff>:</FONT>~<FONT
color=#ff0000>)</FONT></FONT></FONT></STRONG></FONT></DIV>
<DIV>We are going to build us a fully functional Text Editor<BR>with User input.
This will allow the end user to answer several questions that you make up for
them, and then submit the information into the editor.<BR>We are going to be
using the TRichEdit Component for our project.</DIV>
<DIV></DIV>
<DIV>This Project will be designed using Delphi 6 Professional.<BR>But we are
going to try our hardest to make sure that nothing is used that that will only
compile with this version of Delphi.</DIV>
<DIV></DIV>
<DIV><FONT color=#00ff00></FONT><FONT color=#0000ff>Please rate this
Code/Tutorial and e-mail us your comments or suggestions for future
codes/tutorials<BR></FONT><hr><BR>
 <FONT
color=#ffffff><b>Part.1</b><BR>
 </FONT>Start Delphi, open a new form. Name it {<FONT
color=#ff0000>UserTextEditor</FONT>}<BR>Then in the <FONT
color=#ff0000>Caption</FONT>. Add this<FONT color=#ff0000>: User input Text
Editor<BR></FONT>Click <FONT color=#ff0000>File/Save All </FONT>in order <FONT
color=#ff0000>1st name Editor<BR>2nd naming
UserFriendlyTextInputEditor</FONT>.</DIV>
<DIV></DIV>
<DIV>Next we want to add the following:<BR><FONT color=#ff0000>1 TPanel with
Aligned alClient</FONT></DIV>
<DIV><FONT color=#ffff00><FONT color=#ff0000>1 TPageControl aligned alClient
Name the PageControl "PageKeeper" w/o the " "<BR>1 TRichEdit aligned
AlClient<BR>Click on {Lines} in the Object Inspector and delete the default
RichEdit1</FONT>. </FONT>This will give your RichEdit a clean surface with no
writing in it)</DIV>
<DIV></DIV>
<DIV>Next we are going to <FONT color=#ffff00><FONT color=#ff0000>name</FONT>
 </FONT>the <FONT color=#ffff00><FONT
color=#ff0000>RichEdi</FONT><font color="#FF0000">t</font></FONT>.<BR>
 Let's give it the Name of <FONT
color=#ff0000>InputKeeper.</FONT><BR>This will be a good time to <FONT
color=#ff0000>Save All your work</FONT>.</DIV>
<DIV></DIV>
<DIV><FONT color=#0000ff>Hint: Click on the Shortcut icon on the Control Panel
with the <BR>3-floppy disk.:)</FONT></DIV>
<DIV></DIV>
<DIV>Now lets hit the shortcut keys for the compiler : <FONT color=#0000ff>Shift
F9 </FONT>:<BR>and then lets run our editor. We can type text into the editor
but that is about it for the time being.</DIV>
<DIV></DIV>
<DIV>Now lets add some more goodies to this joker to get it up and going.</DIV>
<DIV></DIV>
<DIV><BR><FONT color=#ff0000>go to Dialogs in the scrollable Pagecontrol in
Delphi. And choose the following:<BR>1: TPrintDialog<BR>1: TOpenDialog (Yellow
Folder)<BR>1: TSaveDialog (Green Floppy Disk)<BR>1: TPrinterSetupDialog<BR>1:
TFontDialog</FONT></DIV>
<DIV></DIV>
<DIV>Before going any further lets click on the <FONT color=#ff0000>SaveDialog
</FONT>first<BR>and do the following<BR>Object Inspector Properties do the
following</DIV>
<DIV></DIV>
<DIV><FONT color=#ff0000>DefaultExt.: TXT<BR>Filter : Click this and add the
following exactly as indicated here -> <BR>Filter Name Filter</FONT></DIV>
<DIV></DIV>
<DIV><FONT color=#ff0000>Text Files(*.txt) *.txt<BR>HTML (*.html,*.htm)
*.html,*.htm<BR>All Files (*.*) *.*</FONT></DIV>
<DIV></DIV>
<DIV>Click OK and do the same to the <FONT
color=#ff0000>TOpenDialog<BR></FONT><FONT color=#0000ff>Hint: After clicking OK,
Click CTRL C and then click on TOpenDialog and click on the Filter Box and hit
CTRL V<BR>This is a shortcut for long information to be added to these Dialogs
:)<BR>_______________________________________________________________<BR></FONT>Part.2</DIV>
<DIV></DIV>
<DIV>Now we are going to add the following Components to the Form<BR>1:
TMainMenu<BR>1: TPopupMenu</DIV>
<DIV></DIV>
<DIV>TMainMenu Add the following:<BR>The following is: {File} is the Top Caption
and below fall under {File} and so on... Write each of the following in the
Caption area and then add the letters aside to the Shortcut:</DIV>
<DIV></DIV>
<DIV><FONT color=#ff0000>&File &Edit
&Help<BR>-----------------------------------------------------------------------------------------
<BR>&New CTRL+N &Undo CTRL+Z &Help <BR>Open CTRL+O - _<BR>- (Dash
for space) - &About...<BR>&Save CTRL+S Cu&t CTRL+X<BR>Save &As
&Copy CTRL+C<BR>&Close CTRL+F4 &Paste CTRL+V<BR>- <BR>P&rinter
Setup -<BR>&Print Se&lect All CTRL+A<BR>- -<BR>&Exit CTRL+F9
&Insert Date CTRL+D
<BR>&Font<BR>---------------------------------------------------------------<BR>TPopupMenu</FONT></DIV>
<DIV></DIV>
<DIV><FONT color=#ff0000>Add in the Cut, Copy, Paste and Select all -(for space)
and close.<BR></FONT></DIV>
<DIV></DIV>
<DIV>This will be a good time to Compile and save all your work.<BR><FONT
color=#0000ff>Remember
Hint.1<BR>_______________________________________________________________</FONT></DIV>
<DIV></DIV>
<DIV></DIV>
<DIV></DIV>
<DIV>-----------------------------------------------------------------------<BR>Now
we are going to add another Component to the form and add some information to
it.</DIV>
<DIV></DIV>
<DIV>On the <FONT color=#0000ff>Win32 Tab </FONT>in Delphi double click on the
<BR><FONT color=#ff0000>TStatusBar (it will automatically align alBottom Leave
this as Default)<BR></FONT>Double click on the <FONT color=#0000ff>TStatusBar
</FONT>to invoke the <FONT color=#0000ff>StatusBar Editor </FONT>and add the
following information to it.</DIV>
<DIV></DIV>
<DIV>Click on the <FONT color=#0000ff>Yellow Folder 7 times<BR>(make sure that
the property tab is showing in the Object inspector)</FONT></DIV>
<DIV></DIV>
<DIV><FONT color=#ff0000>0: Line: 1 Col:1 width 150<BR>1: TStatusPanel width 100
Alignment = taCenter<BR>2: Total Lines width 60<BR>3: CAPS width 50 Alignment =
taCenter Style OwnerDraw<BR>4: INS width 50 Alignment = taLeftJustify Style
OwnerDraw <BR>5: NUM width 50 Alignment = taLeftJustify Style OwnerDraw<BR>6:
Insert the date example: 2001-10-11 (This is just to let end user know when you
created the application)<BR></FONT><FONT color=#0000ff><BR>Now compile and save
all </FONT></DIV>
<DIV></DIV>
<DIV>Now we are going to add another component that will help the <FONT
color=#0000ff>TStatusBar</FONT>: On the <FONT color=#ff0000>Additional
tab<BR></FONT><FONT color=#0000ff>hunt for the ApplicationEvents (Blue circle
w/3 black arrows)</FONT></DIV>
<DIV></DIV>
<DIV>After inserting the component into your project form: do the following and
add the following code:</DIV>
<DIV></DIV>
<DIV><FONT color=#0000ff>In the Object Inspector <BR>double click and add the
following code to each of the following</FONT></DIV>
<DIV></DIV>
<DIV><FONT color=#ff0000>OnActivate </FONT><FONT
color=#ff0000>//paint</FONT><FONT color=#ff0000> the caps, num,
ins<BR>StatusBar1.Invalidate;</FONT></DIV>
<DIV></DIV>
<DIV><FONT color=#ff0000>OnHint StatusBar1.Panels[2].Text :=
Application.Hint;</FONT></DIV>
<DIV></DIV>
<DIV><FONT color=#ff0000>OnMessage </FONT><FONT color=#ff0000>//This</FONT><FONT
color=#ff0000> checks for the caps, numlock and insert key presses<BR>if
Msg.message = WM_KEYUP then<BR>StatusBar1.Invalidate;</FONT></DIV>
<DIV></DIV>
<DIV><FONT color=#ff0000>OnRestore </FONT><FONT
color=#ff0000>//paint</FONT><FONT color=#ff0000> the caps, num,
ins<BR>StatusBar1.Invalidate;</FONT></DIV>
<DIV></DIV>
<DIV></DIV>
<DIV></DIV>
<DIV><FONT face=Arial
size=2>---------------------------------------------------------------------------------------------------------------</FONT></DIV>
<DIV><FONT face=Arial size=2>Now lets add the information to show the line #
counts in the <FONT color=#0000ff>TStatusBar</FONT></FONT></DIV>
<DIV><FONT face=Arial size=2>Click on Your <FONT color=#0000ff>TRichEdit
</FONT>to activate it, On the <FONT color=#0000ff>Object Inspector. Events
Handler Tab</FONT></FONT></DIV>
<DIV><FONT face=Arial size=2>Double Click on the <FONT
color=#ff0000>OnSelectionChange</FONT>. Insert this code</FONT></DIV>
<DIV><FONT face=Arial size=2>This will count the Number of lines that are
inserted into the <FONT color=#0000ff>TRichEdit </FONT>Component</FONT></DIV>
<DIV><FONT face=Arial size=2>Into the <FONT
color=#0000ff>TStatusBar</FONT>:</FONT></DIV>
<DIV></DIV>
<DIV><FONT color=#ff0000><FONT face=Arial size=2>var<BR>CharPosX,CharPosY:
integer;<BR>EM_EXLINEFROMCHAR :integer;<BR>begin<BR>CharPosY :=
SendMessage(TRichEdit(Sender).Handle, EM_EXLINEFROMCHAR,
0,TRichEdit(Sender).SelStart);<BR>CharPosX := (TRichEdit(Sender).SelStart -
SendMessage(TRichEdit(Sender).Handle, EM_LINEINDEX, CharPosY,
0));<BR>Inc(CharPosY);<BR>Inc(CharPosX);<BR>StatusBar1.Panels[0].Text:=
Format('Line: %d Col: %d', [CharPosY,
CharPosX]);</FONT><BR></FONT>----------------------------------------------------------------------<BR>Part.3:<BR><FONT
color=#0000ff>Lets Start Coding!! :)</FONT></DIV>
<DIV></DIV>
<DIV>This is the fun part. {I ask that with all my hard work that you do not
Copy and Paste this code into your Forms Editor. But that you Print this out,
and follow all instruction's and and set their and have fun typing, Keeping in
mind too take a break every 30 - 60minutes to give your fingers a break in the
Coding process. Or your fingers will become stressed and cramped. to the point
to where it will become hard to type and keep up with your own self without
making allot of mistakes.} :)</DIV>
<DIV></DIV>
<DIV></DIV>
<DIV></DIV>
<DIV>now we are going to click the <FONT color=#0000ff>Statusbar </FONT>and go
to the <FONT color=#0000ff>Object inspector Events tab </FONT>and <BR><FONT
color=#0000ff>double click </FONT>the<FONT color=#0000ff> OnDrawPanel </FONT>and
add the following code for the drawing of information<BR>to the <FONT
color=#0000ff>TStatusBar.</FONT></DIV>
<DIV></DIV>
<DIV><FONT color=#ff0000>var<BR>Color: TColor;<BR>MyRect:
TRect;<BR>begin</FONT></DIV>
<DIV></DIV>
<DIV><FONT color=#ff0000>MyRect :=
Rect;<BR>StatusBar1.Canvas.FillRect(Rect);</FONT></DIV>
<DIV></DIV>
<DIV><FONT color=#ff0000>case Panel.Index of<BR>3:<BR>begin<BR>if
GetKeyState(VK_CAPITAL) = 0 then<BR>Color := clGray<BR>else<BR>Color :=
clBlack;<BR>end;<BR>4:<BR>begin<BR>if GetKeyState(VK_INSERT) = 0 then<BR>Color
:= clBlack<BR>else<BR>Color := clGray;<BR>end;<BR>5:<BR>begin<BR>if
GetKeyState(VK_NUMLOCK) = 0 then<BR>Color := clGray<BR>else<BR>Color :=
clBlack;<BR>end;<BR>end; </FONT><FONT color=#ff0000>//end</FONT><FONT
color=#ff0000> case<BR>StatusBar1.Canvas.Font.Color := Color;</FONT></DIV>
<DIV></DIV>
<DIV><FONT
color=#ff0000>DrawText(StatusBar1.Canvas.Handle,<BR>PChar(Panel.Text),<BR>-1,<BR>MyRect,<BR>DT_SINGLELINE
or DT_VCENTER or DT_CENTER);</FONT></DIV>
<DIV></DIV>
<DIV><BR>------------------------------------------------------------------<BR>next:<BR>
 lets add the information for our <font color="#0000FF">MainMenu</font></DIV>
<DIV></DIV>
<DIV>Not in a complete order of rows.<BR>Going by what comes to mind
first.</DIV>
<DIV></DIV>
<DIV><FONT color=#0000ff>Double click on TMainMenu to activate the Menu Editor
& do the following:</FONT></DIV>
<DIV></DIV>
<DIV><FONT color=#ff0000>double click Cut insert this code =
InputKeeper.CutToClipboard();</FONT></DIV>
<DIV></DIV>
<DIV><FONT color=#ff0000>double click Copy insert this code =
InputKeeper.CopyToClipboard();</FONT></DIV>
<DIV></DIV>
<DIV><FONT color=#ff0000>double click Paste insert this code =
Inputkeeper.PasteFromClipboard();</FONT></DIV>
<DIV></DIV>
<DIV><FONT color=#ff0000>double click Undo insert this code =
SendMessage(InputKeeper.Handle,WM_UNDO,0,0);<BR><BR>double click Select All
insert this code = InputKeeper.SelectAll;</FONT></DIV>
<DIV></DIV>
<DIV><FONT color=#ff0000>double click Insert Date insert this code
=<BR>InputKeeper.SelText := FormatDateTime(sDateTimeFormat, Now);</FONT></DIV>
<DIV></DIV>
<DIV>(now we have to add 1 more thing to make the sDateTimeFormat
work)<BR>Scroll to the top of the Form Editor and between the <BR>uses and type
sections<FONT color=#0000ff> </FONT>add this<FONT color=#0000ff>:
const<BR>sDateTimeFormat: String = 'yyyy-mm-dd';</FONT></DIV>
<DIV></DIV>
<DIV><FONT color=#0000ff>double click Font </FONT>insert this code =</DIV>
<DIV></DIV>
<DIV><FONT color=#ff0000>//this</FONT><FONT color=#ff0000> will allow you to
choose the font size and style of your text<BR>begin </FONT><FONT
color=#ff0000>//this</FONT><FONT color=#ff0000> is the start. the default
begin<BR>if FontDialog1.Execute then<BR>begin<BR>InputKeeper.Font.Color :=
FontDialog1.Font.Color;<BR>InputKeeper.Font.Name :=
FontDialog1.Font.Name;<BR>InputKeeper.Font.Size :=
FontDialog1.Font.Size;<BR>InputKeeper.Font.Height :=
FontDialog1.Font.Height;<BR>InputKeeper.Font.Style :=
FontDialog1.Font.Style;<BR>InputKeeper.Font.Charset :=
FontDialog1.Font.Charset;<BR>InputKeeper.Font.Pitch :=
FontDialog1.Font.Pitch;<BR>end; </FONT><FONT color=#ff0000>//their</FONT><FONT
color=#ff0000> is 2 end; in the procedure call </FONT></DIV>
<DIV></DIV>
<DIV></DIV>
<DIV><FONT face=Arial size=2>Now we need to add in the code for you to be able
to create a new file. This will give you a warning to let you</FONT></DIV>
<DIV><FONT face=Arial size=2>know that you are about to get rid of the changes
that you have made to the current file in the editor.</FONT></DIV>
<DIV></DIV>
<DIV><FONT face=Arial size=2><FONT color=#0000ff>MainMenu </FONT>click on the
 <FONT color=#ffffff><FONT color=#0000ff>New</FONT> </FONT>link and add this
 <FONT color=#0000ff>code </FONT>in the <font color="#0000FF">Editor:</font></FONT></DIV>
<DIV></DIV>
<DIV><FONT face=Arial color=#ff0000 size=2>var</FONT></DIV>
<DIV><FONT face=Arial color=#ff0000 size=2>rc : LongInt;</FONT></DIV>
<DIV><FONT face=Arial color=#ff0000 size=2>begin</FONT></DIV>
<DIV><FONT face=Arial color=#ff0000 size=2>rc := MessageBox(0, 'You will loose
anything thats not saved! Do you want to continue with this?','War</FONT></DIV>
<DIV><FONT face=Arial color=#ff0000 size=2>if rc = mrYes Then</FONT></DIV>
<DIV><FONT face=Arial color=#ff0000 size=2>InputKeeper.Lines.Clear;</FONT></DIV>
<DIV></DIV>
<DIV><FONT face=Arial size=2>Now we will need to add in the code to make the
application close when clicked.</FONT></DIV>
<DIV></DIV>
<DIV><FONT face=Arial size=2><FONT color=#0000ff>MainMenu </FONT>click on the
<FONT color=#0000ff>Exit</FONT> and enter the following line : Short Code: <FONT
color=#ff0000>Close;</FONT></FONT></DIV>
<DIV></DIV>
<DIV></DIV>
<DIV><FONT color=#0000ff>double click Open insert this code: <BR>{this will call
the TOpenDialog component in action. to choose a file from your
computer}</FONT></DIV>
<DIV></DIV>
<DIV><FONT color=#ff0000>OpenDialog1.InitialDir := GetCurrentDir();<BR>If
OpenDialog1.Execute Then
begin<BR>InputKeeper.Lines.LoadFromFile(OpenDialog1.FileName);<BR>InputKeeper.SelStart
:= 0;</FONT></DIV>
<DIV></DIV>
<DIV>double click Save insert this code :<BR>{This will save the current open
file}<BR><FONT color=#ff0000>var<BR>sEdit :
String;<BR>begin<BR>SaveDialog1.InitialDir := GetCurrentDir();<BR>sEdit :=
InputKeeper.Text;<BR>If Length(Trim(sEdit)) = 0 Then<BR>MessageDlg('No Text To
Be Saved',mtError,[MBOK],0)<BR>Else If SaveDialog1.Execute
Then<BR>inputKeeper.Lines.SaveToFile(SaveDialog1.Filename);</FONT></DIV>
<DIV></DIV>
<DIV><BR>double click <FONT color=#ff0000>Printer Setup </FONT>insert this code
<FONT color=#ff0000>PrinterSetupDialog1.Execute;</FONT></DIV>
<DIV></DIV>
<DIV>-----------------------------------------------------------------------------------<BR>Now
if you know how to make a <FONT color=#ffffff>.</FONT><FONT color=#0000ff>hlp
file (Help File) </FONT>then you will add this under the Help drop down<BR>if
you do not have a Help File created then you will receive an error <BR><FONT
color=#ff0000>Application.HelpFile := ExePath +
'UserTextEditor.hlp';<BR>Application.HelpContext(10);</FONT></DIV>
<DIV></DIV>
<DIV>---------------------------------------------------------------------------------------------<BR>
 Now we are going to add some calls to the <font color="#0000FF">Main Forms Events
 Handler</font>.<BR>
 1st go to <FONT color=#0000ff>Object inspector's Events tab
</FONT>and choose from the drop down list<BR><FONT color=#0000ff>the name of the
Editor. </FONT>In our case this will be the very last one on the list<BR><FONT
color=#0000ff>UserTextEditor TUserTextEditor <BR>Double click and insert the
following code into each of the following</FONT></DIV>
<DIV></DIV>
<DIV><FONT color=#ff0000>OnClose: <BR>var<BR>Winstate:
integer;<BR>begin<BR>IniFile.Clear;</FONT></DIV>
<DIV></DIV>
<DIV><FONT color=#ff0000>if UserTextEditor.WindowState = wsMaximized
then<BR>WinState := 1<BR>else<BR>WinState := 0;</FONT></DIV>
<DIV></DIV>
<DIV><FONT color=#ff0000>IniFile.Add(IntToStr(WinState));</FONT></DIV>
<DIV></DIV>
<DIV><FONT color=#ffff00><FONT color=#ff0000>IniFile.SaveToFile(ExePath +
'UserTextEditor.ini');<BR>IniFile.Free</FONT>;<BR></FONT>(Now we have to add a
<FONT color=#0000ff>Type Private </FONT>in order to make the .ini & ExePath
work without errors)<BR>(These 2 calls must be added above any <FONT
color=#0000ff>procedure or function<BR></FONT><FONT color=#ff0000>IniFile:
TStringList;<BR>ExePath: string; </FONT></DIV>
<DIV><FONT color=#ffff00><FONT color=#000000>add the following code into the
</FONT></FONT><FONT color=#0000ff>Oncreate and OnResize</FONT></DIV>
<DIV></DIV>
<DIV><BR><FONT color=#ff0000>OnCreate</FONT></DIV>
<DIV></DIV>
<DIV><FONT color=#ff0000>var<BR>WinState: integer;<BR>begin<BR>ExePath :=
ExtractFilePath(Application.ExeName);<BR>IniFile :=
TStringList.Create;</FONT></DIV>
<DIV></DIV>
<DIV><FONT color=#ff0000>if FileExists(ExePath +
'UserTextEditor.ini')then<BR>begin<BR>IniFile.LoadFromFile(ExePath +
'UserTextEditor.ini');<BR>WinState := StrToInt(IniFile.Strings[0]);</FONT></DIV>
<DIV></DIV>
<DIV><FONT color=#ff0000>if WinState = 1 then<BR>UserTextEditor.WindowState :=
wsMaximized<BR>else<BR>UserTextEditor.WindowState := wsNormal;<BR>end;
</FONT><FONT color=#ff0000>//their</FONT><FONT color=#ff0000> is 2 end; in the
procedure call </FONT></DIV>
<DIV></DIV>
<DIV><FONT color=#ff0000>OnResize<BR>var<BR>MinusWidth:
integer;<BR>begin<BR>MinusWidth := StatusBar1.Panels[0].Width
+<BR>StatusBar1.Panels[1].Width +<BR>StatusBar1.Panels[3].Width
+<BR>StatusBar1.Panels[4].Width +<BR>StatusBar1.Panels[5].Width
+<BR>StatusBar1.Panels[6].width;<BR>StatusBar1.Panels[2].Width :=
StatusBar1.Width - MinusWidth; </FONT></DIV>
<DIV></DIV>
<DIV>----------------------------------------------------------------<BR>Now
over to the <FONT color=#0000ff>TRichEdit Component </FONT>lets do the same as
above<BR>on the <FONT color=#0000ff>Events tab</FONT></DIV>
<DIV></DIV>
<DIV><FONT color=#0000ff>OnKeyDown</FONT></DIV>
<DIV></DIV>
<DIV><FONT color=#ff0000>var<BR>i: integer;<BR>begin<BR>if (Shift = [ssShift])
and (Key = VK_F12) then<BR>begin<BR>for i := 0 to TRichEdit(Sender).Lines.Count
- 1 do<BR>TRichEdit(Sender).Lines.Strings[i] := 'document.write("'
+TRichEdit(Sender).Lines.Strings[i] + '");';<BR>end; </FONT><FONT
color=#ff0000>//their</FONT><FONT color=#ff0000> is 2 end; in the procedure
call</FONT></DIV>
<DIV></DIV>
<DIV></DIV>
<DIV></DIV>
<DIV>--------------------------------------------------------------------<BR>
 Now lets add to our editor a <FONT color=#0000ff>TToolBar </FONT>from the <FONT
color=#0000ff>Win32 Tab</FONT>. This will <font color="#0000FF">automatically
 align alTop</font><FONT color=#ffffff><BR>
 </FONT>Now we are going to add some <FONT color=#0000ff>buttons
</FONT>to the <FONT color=#0000ff>ToolBar</FONT><FONT color=#00ffff>. <FONT
color=#000080>We will do this by simply right clicking on<BR>the toolbar and
choosing New Button</FONT>.<BR></FONT><FONT color=#0000ff>Add 4 New
Buttons</FONT> and then <FONT color=#0000ff>Add a New Separator </FONT>(<FONT
color=#0000ff>Located below the New Button</FONT>)<BR>next<BR><FONT
color=#0000ff>Add 1 New Button and a New Separator<BR>Add 3 New Buttons and a
New Separator<BR>Add 1 New Button </FONT></DIV>
<DIV></DIV>
<DIV>Next add a <FONT color=#0000ff>TImageList </FONT>from the <FONT
color=#0000ff>Win32 Tab <BR></FONT>Double click the <FONT color=#ffffff><FONT
color=#0000ff>TImageList</FONT> </FONT>to invoke the <FONT color=#0000ff>Image
Collector</FONT>. <FONT color=#000080>Browse into the Directory that
you<BR>unzipped the Tutorial into and double click the image file, Except Yes to
all for the images to separate</FONT>.</DIV>
<DIV></DIV>
<DIV><FONT color=#0000ff>Add images to the button by # of buttons<BR></FONT>In
the Object inspector Click on the <FONT color=#0000ff>Toolbar </FONT>and go to
<FONT color=#0000ff>Images</FONT>. <FONT color=#0000ff>Double click</FONT>, this
will bring in the<BR><FONT color=#000080>imagelist1</FONT>. Now on each button
do the following: Object inspector click on each button and and go to<BR>
 <font color="#0000FF">ImageIndex</font>. Follow the following rule<FONT color=#0000ff>:
 </FONT>do the following in the <font color="#0000FF">Events OnClick</font><FONT color=#ffffff><BR>
 </FONT><FONT color=#0000ff>1st: New ImageIndex 6 New1Click<BR>
 2nd: Open ImageIndex 23 Open1Click <BR>
 3rd: Save ImageIndex 46 Save1Click<BR>
 4th: Close ImageIndex 69 Exit1Click<BR>
 5th: Printer ImageIndex 101 Printer1Click<BR>
 6th: Cut ImageIndex 0 Cut1Click<BR>
 7th: Copy ImageIndex 1 Copy1Click<BR>
 8th: Paste ImageIndex 2 Paste1Click<BR>
 9th: Undo ImageIndex 3 Undo1Click
 <BR>-----------------------------------------------------------------------<BR></FONT><FONT
color=#000080>Now we are going to add in the fun stuff.:)</FONT></DIV>
<DIV></DIV>
<DIV>O.K. What we are going to do here, is design a few input edits that will
drop the information right directly into our Editor. From what the user types
into the RunTime edits.</DIV>
<DIV></DIV>
<DIV>Are we Ready? Lets Go Rock & Roll</DIV>
<DIV></DIV>
<DIV>1st: Lets go to the <FONT color=#ffffff><FONT color=#0000ff>MainMenu</FONT>
</FONT>and open it up, by <FONT color=#0000ff>double clicking it to invoke the
Menu Editor.</FONT></DIV>
<DIV></DIV>
<DIV>Now we are going to add the following to it.<BR>we already have the
following in here: now make it look like the below example:<BR><FONT
color=#000080>File Edit Help - - User I&nput <BR>Sample 1<BR>Sample
2<BR>Sample 3</FONT></DIV>
<DIV></DIV>
<DIV><FONT color=#000080>Under Sample 1 add the following</FONT></DIV>
<DIV></DIV>
<DIV><FONT color=#0000ff>var<BR>Hello : String;<BR>YourName : String;<BR>//when
writing information here. you are allowed to go 250 letter characters<BR>//use
the following to split it into 2 or more line of words. add this to the end and
then the beginning<BR>// at the end ' + at the beginning of the next line ' see
example:<BR>//When adding a message box always pay attention to the end of the
code? the end;<BR>//With a message and a little bit of code you will always need
2 end;<BR>//If you have allot of code you will need as many as 10 end; at the
end of the code<BR>begin<BR>MessageDlg ('How do you like this tutorial ? Please
write a sample of what you like most about it: And please remember to vote if
you' +<BR>' Like or dislike this Tutorial.',mtConfirmation,[mbYes],0);<BR>if
Messagedlg('If you choice not to run this script press No, Otherwise Yes to
continue',mtConfirmation,[mbYes,mbNo],0)=mrYES then<BR>// this will allow the
end-user to have a choice of wanting to continue or not<BR>begin<BR>YourName :=
InputBox ('Link', 'Please enter your full name','');<BR>Hello := InputBox
('Link', ' Please let me know how you like this
tutorial','');<BR>InputKeeper.SelText := ' ' + YourName + '
';<BR>InputKeeper.Lines.Add(''); //this will split the lines so that they will
not be added on the same line<BR>InputKeeper.SelText := ' ' + Hello + '
';</FONT></DIV>
<DIV><FONT color=#0000ff>end;<BR></FONT></DIV>
<DIV></DIV>
<DIV>----------------------------------------------------------------------------<BR>Let's
add 2 more code<FONT color=#000080>. Let's call this the Bonus
Code:</FONT></DIV>
<DIV>On the <FONT color=#0000ff>TToolBar</FONT>, lets add <FONT color=#0000ff>2
 TSpeedButtons </FONT>with the <font color="#0000FF">Width of 50</font></DIV>
<DIV>Name one <FONT color=#0000ff>mail </FONT>and the other <FONT
color=#0000ff>Sight<BR></FONT>Under each button add the following code:</DIV>
<DIV></DIV>
<DIV><FONT color=#000080>under Mail Button</FONT></DIV>
<DIV></DIV>
<DIV><FONT color=#0000ff>ShellExecute(Handle, 'open', 'mailto:Enter your own e-mail
 address here'<BR>
 ,nil,nil, SW_SHOWNORMAL);</FONT></DIV>
<DIV></DIV>
<DIV><FONT color=#000080>under Sight Button</FONT></DIV>
<DIV></DIV>
<DIV><FONT color=#0000ff>ShellExecute(Handle, 'open', 'http://www.carrz-fox-fire.com'<BR>
 ,nil,nil, SW_SHOWNORMAL); </FONT></DIV>
<DIV></DIV>
<DIV>Now we are going to need to scroll to the top of the editor and add the following
 to the <font color="#0000FF">Uses list</font><FONT color=#ffffff><BR>
 </FONT><FONT
color=#ffff00><FONT color=#0000ff>ShellAPI </FONT></FONT>the mail and url calls
will not work without it.</DIV>
<DIV>----------------------------------------------------------------------------------------------------------------------------------------------------------</DIV>
<DIV><FONT color=#ff0000 size=3>New Code Added On Oct. 19, 2001 <FONT
color=#000000><FONT
color=#000000><<<<<<<<<<<<<<<<<<<<<<-----------------
L<FONT color=#ff0000>oo</FONT>k <FONT color=#0000ff>:</FONT>~</FONT><FONT
color=#ff0000>)</FONT></FONT></FONT></DIV>
<DIV>Now we are going to add some code for the Print: Add the following
information to the TToolBar Print Button & </DIV>
<DIV>MainMenu Print Function: <FONT
color=#000000><<<<<<<<<<<<----------------- color="#ff0000" L<FONT>oo</FONT>k
 <FONT color=#0000ff>:</FONT>~</FONT><FONT
color=#ff0000>)</FONT></DIV>
<DIV><FONT color=#0000ff>var<BR>FileName: String;<BR>begin<BR>if
PrintDialog1.Execute then<BR>InputKeeper.Print(FileName);<BR>end;</FONT></DIV>
<DIV></DIV>
<DIV>Now we are going to add the information for the Save As Procedure:</DIV>
<DIV>Add the following code un the MainMenu's Save As..... <FONT
color=#000000><<<<<<<<<----------------->oo</FONT>k <FONT color=#0000ff>:</FONT>~<FONT
color=#ff0000>)</FONT></DIV>
<DIV></DIV>
<DIV><FONT color=#0000ff>var<BR>FileName : String;<BR>begin<BR>if
SaveDialog1.Execute
then<BR>begin<BR>InputKeeper.Lines.SaveToFile(FileName);<BR>end; // uses 2
end;</FONT></DIV>
<DIV>-----------------------------------------------------------------------------------------------------------------------------------------------------</DIV>
<DIV>We are going to add a really nice feature to our application now?? <FONT
color=#000000><<<----------------- &>oo</FONT>k <FONT color=#0000ff>:</FONT>~<FONT
color=#ff0000>)</FONT></DIV>
<DIV>we are going to add the ability to <FONT color=#ff0000>Drag & Drop
</FONT>files right into the the <FONT color=#0000ff>TRichEdit</FONT>:</DIV>
<DIV></DIV>
<DIV>1st we are going to add a procedure into the Type list (not the Private
(or) Public but the Type)</DIV>
<DIV>
 <p>Add this Code<br>
  (1st you will need to add something to your Uses)<br>
  Uses ShellAPI; // If ShellAPI is not added you will receive an Error in D6
  and above for DragQueryFile</p>
</DIV>
<DIV><FONT color=#0000ff>procedure DropFiles(var Msg: TWMDropFiles); message
wm_DropFiles;</FONT>
</DIV>
<DIV><FONT color=#0000ff></FONT> </DIV>
<DIV><FONT color=#0000ff>n<FONT color=#000000>ow we are going to add the
Procedure to our Code Editor:</FONT></FONT></DIV>
<DIV><FONT color=#0000ff></FONT> </DIV>
<DIV><FONT color=#0000ff> //this simply adds the ability to Drag & Drop
into our application's Editor<BR>procedure TUserTextEditor.DropFiles(var Msg:
TWMDropFiles);<BR>var<BR> nFiles:Integer;<BR>
fName:String;<BR> FileName: String;<BR>begin<BR> nFiles:=
DragQueryFile(MSg.Drop,$FFFFFFFF,nil,0);<BR>
try<BR> if (nFiles > 1)
then<BR>
begin<BR>
MessageBox(Handle,'Please, drag one file by
time.',<BR>
@Caption[1],MB_ICONWARNING or MB_OK);<BR>
end<BR> else<BR>
begin<BR>
SetLength(fName,MAX_PATH);<BR>
DragQueryFile(Msg.Drop,0,@fName[1],MAX_PATH);<BR>
fName:=PChar(fName);<BR> if
FileExists(fName) then<BR>
begin<BR>
FileName:=fName;<BR>
InputKeeper.Lines.LoadFromFile(FileName);<BR>
end<BR>
else<BR>
MessageBox(Handle,'Draged file does not
exists.',<BR>
@Caption[1],MB_ICONWARNING or MB_OK);<BR>
end;<BR> finally<BR>
DragFinish(Msg.Drop);<BR> end;<BR>end;</FONT></DIV>
<DIV><FONT color=#0000ff></FONT> </DIV>
<DIV><FONT color=#0000ff><FONT color=#000000>On the Forms OnCreate
add the Following Code:</FONT></FONT></DIV>
<DIV><FONT color=#0000ff></FONT> </DIV>
<DIV><FONT color=#0000ff>DragAcceptFiles(Handle,True);</FONT><FONT
color=#000000>
</FONT></DIV>
<DIV><FONT color=#0000ff></FONT> </DIV>
<DIV><FONT color=#0000ff><FONT color=#000000>Now Shift F9 to compile and F8 to
run your App </FONT></FONT></DIV>
<DIV><FONT color=#0000ff><FONT color=#000000>Now open a folder and drag
something into it :~]</FONT></FONT></DIV>
<DIV><FONT color=#0000ff></FONT> </DIV>
<DIV><FONT color=#0000ff><FONT
color=#000000>------------------------------------------------------------------------------------------</FONT></FONT></DIV>
<DIV><FONT color=#0000ff>Now we are going to make the lines count better in out
TStatusBar</FONT></DIV>
<DIV>Click on the <FONT color=#0000ff>TRichEdit </FONT>to activate it on the
Object Inspector</DIV>
<DIV>Now Double Click the <FONT color=#0000ff>OnSelectionChange </FONT>and
enter this code into </DIV>
<DIV>it's Editor</DIV>
<DIV> <FONT color=#000000><<<<<<----------------- L<FONT color=#ff0000>oo</FONT>k
 <FONT color=#0000ff>:</FONT>~</FONT><FONT
color=#ff0000>)</FONT></DIV>
<DIV><FONT color=#0000ff>with InputKeeper.CaretPos
do<BR> StatusBar1.Panels[0].Text:=Format('%d:
%d',[y + 1,x + 1]);</FONT></DIV>
<DIV><FONT color=#0000ff></FONT> </DIV>
<DIV>This procedure is alot better I think than the original one that is
submitted</DIV>
<DIV>but I am going to leave the original on the tutorial just incase
someone</DIV>
<DIV>likes it better ( Your Choose )<BR></DIV>
<DIV><FONT face=Arial
size=2>-----------------------------------------------------------------------------------------------------------------------------------------------------------</FONT></DIV>
<DIV><FONT face=Arial size=2>A little code testing for yourself to
try:</FONT></DIV>
<DIV><FONT face=Arial size=2>Add in the code to make the SaveAs and Print
work.</FONT></DIV>
<DIV><FONT face=Arial size=2>Also create yourself an About form. For the About
in the MainMenu.</FONT></DIV>
<DIV><FONT face=Arial size=2>If you shall need any help on doing this. Please
feel free to write me. Would love to help and hear from 1 and all.</FONT></DIV>
<DIV> </DIV>
<DIV><FONT face=Arial size=2>A little hint, Thought this was neat.
Under the Print in the MainMenu you can add the code
Print;</FONT></DIV>
<DIV><FONT face=Arial size=2>this will do a print-out of the application. This
is neat if you want to have a print-out of the editor to add to </FONT></DIV>
<DIV><FONT face=Arial size=2>your source code when completed.</FONT></DIV>
<DIV> </DIV>
<DIV><FONT face=Arial size=2>Some extra things that you may want to do, is
create a new folder either in the directory where Delphi</FONT></DIV>
<DIV><FONT face=Arial size=2>is installed or within' a directory of it's self. A
folder to keep all of the source code that you create.</FONT></DIV>
<DIV><FONT face=Arial size=2>name a folder ( My Source Code ) and a
folder named (Delphi Source Codes) and within' each of the </FONT></DIV>
<DIV><FONT face=Arial size=2>folder's within' the primary folders, name them
exactly what the name of the source code and version # is.</FONT></DIV>
<DIV><FONT face=Arial size=2>This is handy for all programs that you download to
your computers harddrive.</FONT></DIV>
<DIV> </DIV>
<DIV><FONT face=Arial size=2> I will be adding all this information to our
business sight once we go live. This way you will be able to go in and find
anything and </FONT></DIV>
<DIV><FONT face=Arial size=2>make suggestions of anything that you may want to
see in the near future.</FONT></DIV>
<DIV> </DIV>
<DIV><FONT face=Arial size=2>Take Care and please have as much fun as possible
and learn this terrific programming language.</FONT></DIV>
<DIV> </DIV>
<DIV><FONT face=Arial size=2>Wayne & Carr Barron (Carr is my 7 yr old son. Whom
 will be 8 on the 16th of October.2001)</FONT></DIV>
<DIV><FONT face=Arial size=2>We are from N.C U.S.A.</FONT><br>
 <br>
 How long has this tutorial been up here at the Planet?<br>
 Well, As you see the age of my son right above.<br>
 He is now: 12yrs Old - Attending Middle School and will be 13yrs old this Oct.
 16th 2006.<br>
 Man oh Man,,,, How time sure does fly.<br>
 <br>
 Take Care everyone, and remember to reach for the stars --&gt; May 23rd, 2006<br>
</DIV>
<DIV> </DIV>
<DIV>-----------------------------------------------------------------------------------------------------</DIV>
<DIV> </DIV>
<DIV><FONT color=#800080>Warning: When compiling the completed source you
will receive the following Code:</FONT></DIV>
<DIV> </DIV>
<DIV><FONT color=#800080>[Warning] Editor.pas(7): Unit 'FileCtrl' is specific to
a platform<BR>[Warning] Editor.pas(229): Variable 'Color' might not have been
initialized </FONT></DIV>
<DIV> </DIV>
<DIV><FONT color=#800080>Just keep clicking CTRL F9 until it is
gone.</FONT></DIV>
<DIV> </DIV>
<DIV><FONT color=#800080> This is the only thing that I cannot stop. But it
does not cause a problem</FONT></DIV>
<DIV> </DIV>
<DIV>have fun! :)</DIV>
<DIV> </DIV>
<DIV> </DIV>
<DIV>This tutorial is dedicated to all the Victims of Sept.11th 2001 Tragedies
here in the United States.</DIV>
<DIV>New York, Washington and on Flight 93.</DIV>
<DIV>Thoughts to you and your families.<BR></DIV><PRE></PRE>
</BODY></HTML>

