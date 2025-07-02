<h1>
  <span class="headline">Use Case: Debugging with GenAI</span>
  <span class="subhead">Reviewing and Debugging AI-Generated Code</span>
</h1>

**Learning objective:** By the end of this lesson, students will be able to tktk

Now that you’ve generated code with GenAI, let’s focus on *critically reviewing* and *debugging* it. Remember: just because code “looks right” doesn’t mean it is right.

---

## Why review AI-generated code?

> ⚠ **GenAI can make convincing mistakes.**
>
> - Code may work for one test, but fail in edge cases.
> - It might suggest unsafe or outdated patterns.
> - Logical errors are especially tricky—they’re often invisible until you look closely.

---

## Activity: “Red Team” the AI’s code

1. Use ChatGPT to generate a function for a specific task (pick your own or use: “Write a function that checks if a string is a palindrome”).
2. **Your job:** Play “Red Team” and find as many bugs, logic flaws, or unsafe practices as you can.
    - Does it handle all types of input (numbers, punctuation, mixed case)?
    - Is it efficient and readable?
    - Are there security or safety concerns?
3. Run the code in Google Colab and test with normal and edge-case inputs.
4. Share your findings in your group. What did the AI miss?

> 💡 **Tip:** Try asking ChatGPT, “What edge cases could break this code?”

---

## Discussion: What makes AI-generated code risky?

Reflect or discuss:
- What kinds of errors are *hardest* to catch just by reading the code?
- When do you feel comfortable trusting GenAI’s output?
- How can you improve your review process?

---

## Key callouts

> 💡 Even if code “works,” it might be wrong in subtle ways. GenAI has no intuition for your business rules or unique data!

