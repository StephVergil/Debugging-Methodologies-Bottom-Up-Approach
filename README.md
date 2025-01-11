# Debugging Methodologies: Bottom-Up Approach

This repository explores the **bottom-up debugging methodology**, a systematic process that starts at the lower-level components of a system and works upwards to identify and resolve issues. This approach is particularly effective for complex systems with interdependent components.

## Debugging Methodology

The **bottom-up approach** involves starting the debugging process by examining the lower-level components of a system and gradually working upwards to identify and fix issues. This methodology is based on the idea that problems in higher-level components often stem from errors in lower-level components.

### Key Concepts
- **Bottom-Up Debugging**: Focuses on understanding and verifying the behavior of low-level components (e.g., functions, modules) before moving to higher-level systems.
- **Systematic Process**: Analyzing components one by one ensures that the source of issues is identified and resolved systematically.

## Debugging Tool: Chrome DevTools

One effective debugging tool for this methodology is **Chrome DevTools**, a set of web development and debugging tools built into the Google Chrome browser.

### Features of Chrome DevTools:
- Inspect HTML, CSS, and JavaScript code.
- Set breakpoints to step through code execution.
- Monitor network activity.
- Analyze performance and memory usage.
- Debug the Document Object Model (DOM).

Using Chrome DevTools with the bottom-up debugging methodology allows developers to start with low-level analysis and progressively move up the stack, ensuring that individual components function correctly before addressing the larger system.

## Usage

1. **Analyze Low-Level Components**:
   - Start debugging with the smallest, most fundamental units like functions, classes, or modules.
2. **Use Chrome DevTools**:
   - Set breakpoints in your code.
   - Step through execution to examine the behavior of individual components.
   - Monitor application states in real time.
3. **Validate Higher-Level Components**:
   - Once the lower-level components are verified, debug the higher-level functionalities that depend on them.

## Document Link

For more details, refer to the complete document:  
[Debugging Methodology: Bottom-Up Approach by Stephanie Vergil](https://github.com/StephVergil/Debugging-Methodologies-Bottom-Up-Approach/blob/main/Debugging%20Methodology%20Module%2013.docx)
