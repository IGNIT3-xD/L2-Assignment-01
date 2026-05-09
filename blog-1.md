Why is any labeled a "type safety hole," and why is unknown the safer choice for handling unpredictable data? Explain the concept of type narrowing.

TypeScript is a powerful type system, designed to prevent runtime errors by catching type related issues at run time. 
However, developers sometimes reach for the "any" type to sidestep type restrictions. 
While convenient, "any" effectively turns off TypeScript’s safety features, creating what’s known as a type safety hole.

In contrast, the "unknown" type offers flexibility without sacrificing type safety. Understanding how "unknown" differs from "any" and how type narrowing works is essential for writing robust, predictable TypeScript code.