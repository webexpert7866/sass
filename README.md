## 📚 Comprehensive SCSS Syllabus and Learning Roadmap

1. Basics of SCSS

   - Syntax, file extension (`.scss`), nesting rules.

2. Variables

   - Declaration & usage
   - Data types (colors, numbers, strings)
   - Scope & `!default`

3. Nesting

   - Nested selectors - done
   - Parent selector (`&`) - done
   - Nested properties - done

4. Partials & Import (or Modules)

   - Partial files (`_filename.scss`) - done
   - `@use` (modern, preferred) - done
   - `@import` (older, legacy) - done

5. Mixins

   - Define & include (`@mixin`, `@include`) - done
   - Arguments with defaults - done

6. Functions

   - Built-in (e.g., `lighten`, `darken`, `map-get`)
   - User-defined (`@function`, `@return`)

7. Control Directives

   - `@if`, `@else if`, `@else` - done 
   - Loops (`@for`, `@each`) - done 
   - Interpolation (`#{}`) - done

8. Extends & Placeholders

   - `@extend` directive 
   - `%placeholders`

9. Maps & Lists*- *(for design systems & themes)*

   - Maps → `map-get`, `map-merge`
   - Lists → `nth`, `append`

10. Output Styles & Debugging

- Nested, Expanded, Compressed
- `@debug`, `@warn`, `@error`


👉 The optional/advanced topics*- (you can skip at first):

- Detailed operators section (covered in basics).
- Comments (trivial).
- Source maps/line comments (compiler feature, not core SCSS).
- Very advanced module visibility rules.
