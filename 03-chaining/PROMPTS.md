# PROMPTS.md: Living Prompt Pack

> Module 3 · Prompt Chaining. Re-architect the build with prompt chains; capture the reusable ones here.

## How to use this pack

_Each prompt is a reusable step. Chain them: the output of one becomes the input to the next._

## Prompt chain: Fix-Auditgaps-to-make-prototype-compete

### Step 1: Expand, build new screens in a strict sequence
```
Build the next phase of this app in a strict sequence:
1. Reconstruct the flow to resolve how I'm testing my hypothesis adding features.
2. Add ancillary functions to support the prototype e.g. export functions.
3. At the end of the journey, add a feature which will trigger an action.
```

### Step 2: Behavior, hard-code the states
```
Apply the appropriate handoffs within the flow to ensure they're capable of exception handling.
e.g. what if there's a timeout when hitting one of the buttons,
e.g. what if the database connection is unavailable.
```

### Step 3: Refine, one surgical polish
```
Ensure new content added is done so in a consistent style from the original design
Don't change anything else in the project or touch the underlying logic.
```

## Reusable techniques learned

- _____
- _____

## What broke (and the fix)

_Where a single mega-prompt failed and chaining fixed it._

_____
# PROMPTS.md: Living Prompt Pack

> Module 3 · Prompt Chaining. Re-architect the build with prompt chains; capture the reusable ones here.

## How to use this pack

_Each prompt is a reusable step. Chain them: the output of one becomes the input to the next._

## Prompt chain: [name your flow]

### Step 1: [purpose]
```
[prompt text, with {{variables}} for the parts you swap]
```
**Expects in:** _____
**Produces out:** _____

### Step 2: [purpose]
```
[prompt text]
```
**Expects in:** _____
**Produces out:** _____

### Step 3: [purpose]
```
[prompt text]
```
**Expects in:** _____
**Produces out:** _____

## Reusable techniques learned

- _____
- _____

## What broke (and the fix)

_Where a single mega-prompt failed and chaining fixed it._

_____
