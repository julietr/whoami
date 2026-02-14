# [@julietr](https://github.com/julietr)

My name is Juliet Rosenthal. I'm a professional code monkey in Omaha, Nebraska.

I primarily use C#, F#, PowerShell, and SQL (many flavors).

## How did you get into software?

### tl;dr version:

* In 1998 (age 11), my Dad helped me write my first syntax error. I started coding as a hobby.
* In 2007 (age 19), I got my first programming job.
* Since then, I've produced, debugged, and polished millions of lines of production code.

### Long version:

*(I've told a version of this story at least 1000 times. I enjoy telling this story.)*

In 1998, I was 11 years old. Dad was taking his first computer science classes at the local community college. He was excited to show me his completed homework assignment:

Dad points to a gray window on the computer monitor. The window's title bar reads `Form1`. Dad points to the shape of a square centered inside the form: 🟦.

He clicks on the square: it turns into a circle: 🔵.

He clicks on the circle: it turns back into a square: 🟦.

He clicks a few times: it cycles between the two shapes: 🔵->🟦->🔵->🟦.

_"Dad, did you **make** that?!"_ He did!

He closes the program. The gray form re-renders itself in "design mode" embedded within a Visual Basic 5 development environment. In the form designer, Dad shows me the properties and event handlers of the `Shape` component. He navigates to a function:

```vb
Private Sub Shape1_Click()
    If Shape1.Shape = vbShapeSquare Then
        Shape1.Shape = vbShapeCircle
    ElseIf Shape1.Shape = vbShapeCircle Then
        Shape1.Shape = vbShapeSquare
    End If
End Sub
```

I'd never seen source code prior to Dad's homework assignment on conditionals. I had no working idea of what `Private` or `Sub` meant, but the `If-Then` pattern made perfect sense. He showed me how the IDE's autocomplete functionality works, how to set the shape's line color and line weight. It was neat to see with my own eyes.

Dad tells me his homework assignment is written in Visual Basic. He creates a new project called `HelloWorld`. The IDE shows a gray `Form1` rendered in design mode. Dad drags a button from the toolbox onto the form. It renders with the default name `Command1`. He double-clicks the button, which creates an empty `Command1_Click` event handler in the form's code-behind. Dad fills in the event handler:

```vb
Private Sub Command1_Click()
    Dim userName As String

    userName = InputBox("Please enter your name:", "Name")

    If userName <> "" Then
        MsgBox "Hello, " & userName & "!"
    End If
End Sub
```

He executes the program in the debugger. The form and button render a new window. Dad clicks the button. An input dialog appears, prompting me to enter my name and press Enter. A second dialog appears with the familiar greeting.

He shows me some permutations of these programs: adding OK/Cancel buttons to the `MsgBox`, different event handlers (`MouseDown`, `MouseOver`).

Dad's toy-like programs left quite an impression on my younger self. He encouraged me to copy the code snippets from his college textbooks into the IDE, tinker with the code, and see what I could make (or break). I quickly took to programming as a hobby.

In 2007, my hobby spiraled out of control when it became my career. I found gainful employment as a Level 1 Code Monkey, then spent the next 20+ years building big systems, solving hard problems, and meeting highly interesting people in IT.

If not for Dad's encouragement, I may not have discovered my passion for hacking and tinkering with computers. I might have gone a completely different direction with my life. Maybe I would have become a skydiving instructor. Or a secret agent. A professional boxer. Cat toy designer. A rodeo clown, perhaps.

My name is Juliet and I like to code.