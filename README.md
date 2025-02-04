# Invalid Nested HTML Tag Bug

This repository demonstrates a common HTML error: incorrectly nested tags.  Specifically, a `<div>` element is nested inside a `<p>` element, which is invalid HTML. This can lead to unexpected rendering behavior in browsers and validation errors. The `bug.html` file contains the erroneous code, while `bugSolution.html` provides the corrected version. 

**Bug:** The `<div>` element is incorrectly placed within the `<p>` element. Browsers may handle this differently, but it is not valid HTML according to the specification.

**Solution:** The `<div>` element should be placed outside the `<p>` element or structured differently to maintain valid HTML.