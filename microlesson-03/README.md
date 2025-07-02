<h1>
  <span class="headline">Use Case: Debugging with GenAI</span>
  <span class="subhead">Pair-Programming with GenAI—Debug, Refactor, and Refine</span>
</h1>

**Learning objective:** By the end of this lesson, students will be able to tktk

In this final lesson, you’ll collaborate with GenAI to debug and improve code through an *iterative* process—just like a real pair-programming session.

---

## A workflow for safe and effective AI pair-programming

1. **Prompt clearly.** Explain what you need—bug fix, refactor, or explanation.
2. **Review the suggestion.** Don’t just copy-paste! Check for errors, assumptions, and logic gaps.
3. **Test in Colab.** Run with a variety of inputs.
4. **Refine and repeat.** Use the feedback to prompt GenAI for improvements, more explanation, or alternative solutions.

---

## Activity: Debug a “broken” function with GenAI

### Take a look at this example prompt and output "broken" function.

>**Prompt:**\
*Create a Python function that takes a list of numbers and returns the mean, median, and mode. Keep it simple and do not use the statistics module or any external libraries.*

**Output:**
``` 
def get_stats(numbers):
    # Returns a dictionary with mean, median, and mode for a list of numbers
    stats = {}
    # Mean
    stats['mean'] = sum(numbers) / len(numbers)
    # Median
    numbers.sort()
    mid = len(numbers) // 2
    if len(numbers) % 2 == 0:
        stats['median'] = (numbers[mid] + numbers[mid-1]) / 2
    else:
        stats['median'] = numbers[mid]
    # Mode
    freq = {}
    for n in numbers:
        if n in freq:
            freq[n] += 1
        else:
            freq[n] = 1
    max_freq = max(freq.values())
    mode_vals = []
    for k, v in freq.items():
        if v == max_freq:
            mode_vals.append(k)
    stats['mode'] = mode_vals[0]
    return stats
```

1. Try to identify some flaws on your own first

2. Prompt ChatGPT:  
   - “What’s wrong with this function?”  
   - “How would you fix it?”
   - “Can you rewrite this to be more efficient or readable?”

3. Copy the GenAI fix into Colab. Test, review, and iterate as needed.

4. Challenge: Ask GenAI to explain *why* its changes work (or don’t).

---

## Reflection: Human + AI > AI Alone

- What did you notice about the *back-and-forth* process with GenAI?
- Where did your expertise make the biggest difference?
- How would you use this workflow in your real projects?

> 🏆 **Best practice:**  
> Treat GenAI as a coding partner—one who’s fast, creative, but not always right.

---

## Key takeaway

Collaborating with GenAI means prompting, reviewing, testing, and refining, *not* blindly accepting every suggestion. Human-in-the-loop is your superpower.
