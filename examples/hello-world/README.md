# Hello World Example
The simplest Juvix program - prints Hello, World!
## Code
Create Hello.juvix: module Hello; open import Stdlib.Prelude; main : IO; main := printStringLn "Hello, World!";
## Compile & Run
juvix compile Hello.juvix && ./Hello
## Output
Hello, World!
## Next Steps
- Change the message
- Add user input
- Explore more examples
