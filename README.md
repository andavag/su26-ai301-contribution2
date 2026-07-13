# Contribution 2: Math decimal separator issues

**Contribution Number:** 2
**Student:** Andranik Avagyan 
**Issue:** https://github.com/nvaccess/nvda/issues/20425
**Status:** Phase I

---

## Why I Chose This Issue

I chose this issue because it’s a great way to apply my Python skills to an actual open-source project. Fixing this UI bug—removing a broken dropdown option and updating the docs—is a straightforward way to improve an accessibility tool that a lot of people rely on. My main goal is to get hands-on experience navigating a large codebase, figuring out how wxPython connects to the backend logic, and going through the full pull request process from start to finish.

---

## Understanding the Issue

### Problem Description

The problem is the settings for reading decimal point number in desiered way, custom option is not working.

### Expected Behavior

Custom option should allow to chose the option but current solution is to remove the option of chosing custom.

### Current Behavior

When I chose custom option I do not have a way to chose my option.

### Affected Components

The settings choosing option.

---

## Reproduction Process

### Environment Setup

Instoll the right python version, install the right visual studo build tool version with the necesary depandacys.

### Steps to Reproduce

1. Download all the nesery depandacis for the enviernment.
2. Run the application thru command prompt
3. open NVDA setting/preferance section, open math subsection select custom in decimal point section.
4. See that choosing custom does not allow for options.

### Reproduction Evidence

- **Commit showing reproduction:** https://github.com/andavag/nvda.git
- **Screenshots/logs:** [If applicable]
- **My findings:** The custom option does nothing, and as directed by the author needs to be removed

---

## Solution Approach

### Analysis

There is no implementation to allow how to chose the custom option.

### Proposed Solution

Remove the option for custom.

### Implementation Plan

Using UMPIRE framework (adapted):

**Understand:** No need to have Custom option

**Match:** Check the code how the other optins like Automatic, dot, or comma work

**Plan:** [Step-by-step implementation plan]
1. find all the places which are supposed to implement the custom option
2. Remove the code for allowing the custom option, or comment out

**Implement:** https://github.com/andavag/nvda/tree/beta

**Review:** Following to the contribution.md make the changes in the asked format

**Evaluate:** Run the application and check that Custom option does not apper in the Math Settings.

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
