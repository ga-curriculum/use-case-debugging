<h1>
  <span class="headline">Use Case: Debugging with GenAI</span>
  <span class="subhead">Where GenAI Helps—Generating, Debugging, and Refactoring Code</span>
</h1>

**Learning objective:** By the end of this lesson, students will be able to tktk

In this lesson, you’ll explore how GenAI (like ChatGPT) can support you as a coding partner—especially when you need to generate, debug, or refactor Python code.

You’ll practice writing effective prompts for coding tasks, discuss the strengths and limits of GenAI, and use both ChatGPT and Google Colab to test code in a safe, repeatable workflow.

---

## GenAI as a coding partner: What’s possible?

> 💡 GenAI can help at multiple points in the coding process:
>
> - **Code generation:** Quickly draft functions, classes, or scripts from a natural language prompt.
> - **Debugging:** Review code for errors, get suggestions for fixes, or ask “What’s wrong with this code?”
> - **Refactoring:** Rewrite code for readability, performance, or style.
> - **Explaining:** Break down code line by line, or summarize what a block does.

But GenAI isn’t magic. It’s a helpful collaborator, not a replacement for your brain.

---

## Activity: Try prompting GenAI for code

1. **Open ChatGPT in your browser.**
2. Try one or more of these prompt types:
    - “Write a Python function that returns the nth Fibonacci number.”
    - “Here’s my code—why does it throw an error? [Paste your code]”
    - “Refactor this code to use list comprehensions instead of loops.”
    - “Explain what this function does and where it could fail. [Paste function]”
3. Copy the output to a new cell in Google Colab and run it.

> ⚠ **What to watch for:**  
> - Did the code run as expected?
> - Did ChatGPT miss anything, or make incorrect assumptions?
> - How clear and testable was the code output?

---

## Discussion: Where does GenAI shine? Where does it struggle?

Discuss as a group or reflect in writing:
- What kinds of code requests did GenAI handle well?
- When did it make a mistake or miss important context?
- What’s your personal “rule” for trusting or not trusting AI-generated code?

---

## Key callouts

> 🏆 **Best practices when using GenAI for coding:**
>
> - Always read and understand AI-generated code before running it.
> - Use Colab or another sandboxed environment—never run code directly in your main project first.
> - Test outputs with sample data, edge cases, and “bad” inputs.
> - Don’t be afraid to ask GenAI for clarification or a step-by-step explanation.

---

## Wrap-up: Your workflow, upgraded

You now have experience prompting GenAI to generate and improve Python code, and running it in Colab to check results. In the next lesson, you’ll learn how to critically review AI-generated code, spot logical errors, and debug more safely.

