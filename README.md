# Coding Style


   - Unix-style line endings
   - K&R-style indentation
   - No space before newlines
   - A blank line at the end of each file
   - Never more than one blank line in a row
   - No more than 80 characters per line
   - Always tabs, never spaces
   - One tab per indent
   - A space between control keywords and their corresponding paren 
      (`if (x)`, `while (x)`, and `switch (x)`, never `if(x)`, `while(x)`, or `switch(x)`)
   - A space after most of the keyword and around operators
   - A space between anything and an open brace
   - No space between a function name and an opening paren 
      (`puts(x)`, never `puts (x)`)
   - Always use brackets, even for single-statement blocks
   - Split long conditional expressions into small `static inline`
   - Place the * before the variable name, never after the type
   - To comment out some code, use #if 0 (...) #endif


> Also check the [Clockwise/Spiral Rule](http://c-faq.com/decl/spiral.anderson.html) technique,
> which enables any C programmer to parse in their head any C declaration!
