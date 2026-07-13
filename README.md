# Contribution 2: Math Decimal Separator Issue

**Contribution Number:** 2
**Student:** Andranik Avagyan
**Issue:** https://github.com/nvaccess/nvda/issues/20425
**Status:** Phase I

---

## Why I Chose This Issue

I chose this issue because it is a good way to apply my Python skills to a real open-source project. Fixing this UI bug by removing a broken dropdown option is a practical way to improve an accessibility tool that many people rely on. My main goal is to get hands-on experience navigating a large codebase, understanding how wxPython connects to backend logic, and going through the full pull request process from start to finish.

---

## Understanding the Issue

### Problem Description

The issue is with the setting that controls how decimal point numbers are read. The Custom option does not work as expected.

### Expected Behavior

The Custom option should allow the user to choose a decimal separator behavior. Since that behavior is not implemented, the current solution is to remove the Custom option.

### Current Behavior

When I choose the Custom option, there is no way to configure a custom decimal separator.

### Affected Components

The affected component is the Math settings option for choosing how decimal separators are handled.

---

## Reproduction Process

### Environment Setup

Install the correct Python version and the required Visual Studio Build Tools version with the necessary dependencies.

### Steps to Reproduce

1. Download all necessary dependencies for the environment.
2. Run the application through Command Prompt.
3. Open the NVDA Settings/Preferences section, open the Math subsection, and select Custom in the decimal point setting.
4. Confirm that choosing Custom does not provide any additional options.

### Reproduction Evidence

- **Commit showing reproduction:** https://github.com/andavag/nvda.git
- **Screenshots/logs:** [If applicable]
- **My findings:** The Custom option does not do anything, and as directed by the maintainer, it needs to be removed.

---

## Solution Approach

### Analysis

There is no implementation that allows the user to configure the Custom option.

### Proposed Solution

Remove the Custom option.

### Implementation Plan

Using UMPIRE framework (adapted):

**Understand:** The Custom option is not needed because it is not implemented.

**Match:** Check how the other options, such as Automatic, dot, and comma, work in the code.

**Plan:** [Step-by-step implementation plan]
1. Find all places that expose or reference the Custom option.
2. Remove or disable the code that allows the Custom option to appear.

**Implement:** https://github.com/andavag/nvda/tree/beta

**Review:** Follow `contributing.md` and make the changes in the required format.

**Evaluate:** Run the application and confirm that the Custom option no longer appears in the Math settings.

---

## Testing Strategy

### Unit Tests

- [ ] Test case 1: [Description]
- [ ] Test case 2: [Description]
- [ ] Test case 3: [Description]

### Integration Tests

- [ ] Integration scenario 1
- [ ] Integration scenario 2

### Manual Testing

[What you tested manually and results]

---

## Implementation Notes

### Week [X] Progress

[What you built this week, challenges faced, decisions made]

### Week [Y] Progress

[Continue documenting as you work]

### Code Changes

- **Files modified:** [List]
- **Key commits:** [Links to important commits]
- **Approach decisions:** [Why you chose certain approaches]

---

## Pull Request

**PR Link:** [GitHub PR URL when submitted]

**PR Description:** [Draft or final PR description - much of the content above can be adapted]

**Maintainer Feedback:**
- [Date]: [Summary of feedback received]
- [Date]: [How you addressed it]

**Status:** [Awaiting review / Iterating / Approved / Merged]

---

## Learnings & Reflections

### Technical Skills Gained

[What you learned technically]

### Challenges Overcome

[What was hard and how you solved it]

### What I'd Do Differently Next Time

[Reflection on your process]

---

## Resources Used

- [Link to helpful documentation]
- [Tutorial or Stack Overflow post that helped]
- [GitHub issues or discussions that helped]
