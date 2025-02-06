# Tailwind CSS Classes Not Applying (Intermittent Issue)

This repository demonstrates a seemingly random issue where some Tailwind CSS classes fail to apply, while others work correctly. The problem is intermittent and difficult to reproduce consistently.  The `bug.html` file showcases the problematic code, while `bugSolution.html` offers a possible solution involving purging unused CSS.

**Steps to Reproduce (Inconsistent):**

1. Clone this repository.
2. Open `bug.html` in a browser.
3. Observe that some Tailwind classes (e.g., `bg-blue-500`) might not apply, while others do.
4. Refresh the page; the behavior might change.

**Possible Solution (In `bugSolution.html`):**

The solution implemented in `bugSolution.html` focuses on purging unused CSS. This is because in certain scenarios, an unexpectedly large unused CSS file in the build process might cause issues with some classes not being picked up correctly.