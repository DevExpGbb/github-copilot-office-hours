# Week 2: Advanced Code Generation Techniques
**Duration:** 60 minutes  
**Format:** 30-minute structured demo + 30-minute community session

## Session Overview
This session focuses on maximizing GitHub Copilot's code generation capabilities through effective prompting techniques, understanding when to use different Copilot features, and mastering advanced AI-assisted coding practices.

---

## Part 1: Structured Demo Session (30 minutes)

### 1. Welcome & Week 1 Recap (3 minutes)
- **Quick check-in** on Week 1 "Hello Copilot" challenge experiences
- **Key learnings** from initial Copilot exploration
- **Session objectives** for advanced techniques

### 2. Writing Effective Comments and Prompts (8 minutes)
#### The Art of Prompt Engineering for Code (5 minutes)
- **Comment-driven development** approach
  - Writing descriptive function headers
  - Specifying input/output expectations
  - Including edge case considerations
- **Best practices for prompts:**
  - Be specific about requirements
  - Include context about the broader system
  - Mention performance or security considerations
  - Specify coding style preferences

#### Live Demo: Before and After (3 minutes)
```python
# Bad prompt example:
# function to sort

# Good prompt example:
# Create a function that sorts a list of dictionaries by a specified key
# Input: list of dicts, key name (string)
# Output: sorted list (ascending order)
# Handle: missing keys gracefully, maintain original list
```

### 3. Copilot Chat vs Inline Suggestions (7 minutes)
#### Understanding When to Use Each (4 minutes)
- **Inline suggestions best for:**
  - Code completion and continuation
  - Repetitive patterns
  - Standard implementations
  - Quick fixes and modifications

- **Copilot Chat best for:**
  - Complex problem explanation
  - Code refactoring discussions
  - Learning new concepts
  - Debugging and troubleshooting
  - Architecture decisions

#### Live Comparison Demo (3 minutes)
- **Same task, different approaches:**
  - Building a REST API endpoint
  - Show inline vs chat approaches
  - Highlight strengths of each method

### 4. Advanced Code Generation Scenarios (12 minutes)
#### Complex Algorithm Generation (4 minutes)
**Demo Focus:** Graph algorithms and data structures
- **Prompt:** "Implement Dijkstra's shortest path algorithm"
- **Show:** How Copilot handles complex algorithmic logic
- **Highlight:** Step-by-step generation and explanation

#### Multi-File Project Generation (4 minutes)
**Demo Focus:** Microservice architecture
- **Prompt:** "Create a user authentication service with JWT"
- **Show:** How context spreads across multiple files
- **Highlight:** Consistent naming and pattern recognition

#### Error Handling and Edge Cases (4 minutes)
**Demo Focus:** Robust error handling patterns
- **Prompt:** "Add comprehensive error handling to this function"
- **Show:** Exception handling, logging, validation
- **Highlight:** Security considerations and best practices

---

## Part 2: Community Session (30 minutes)

### 1. Volunteer Demos of Unique Use Cases (15 minutes)
#### Participant Showcase (12 minutes)
**Structured sharing format (3 minutes per participant):**
- **The Challenge:** What problem were you solving?
- **The Approach:** How did you prompt Copilot?
- **The Result:** What did Copilot generate?
- **The Learning:** What surprised you or what would you do differently?

#### Discussion and Feedback (3 minutes)
- **Group insights** on effective techniques
- **Common patterns** observed across different domains
- **Unexpected discoveries** and creative solutions

### 2. Tips and Tricks Sharing Session (10 minutes)
#### Community Knowledge Exchange (8 minutes)
**Open floor for sharing:**
- **Keyboard shortcuts** and workflow optimizations
- **Custom prompting patterns** that work consistently
- **Integration tricks** with other VS Code extensions
- **Language-specific discoveries** and techniques

#### Rapid-Fire Tips Round (2 minutes)
- **One-sentence tips** from each participant
- **Quick wins** that improved their Copilot experience
- **Tools and settings** that enhance productivity

### 3. Collaborative Problem-Solving (5 minutes)
#### Group Challenge Session
- **Present a complex coding challenge** to the group
- **Collaborate on prompting strategies**
- **Compare different approaches** and solutions
- **Vote on most effective technique**

**Example Challenge:**
"Create a caching decorator that supports both synchronous and asynchronous functions, with configurable TTL and storage backends"

---

## Week 2 Mini-Challenge: "Prompt Engineering Mastery"

### Challenge Description
**Objective:** Master the art of effective prompting for code generation

### Tasks:
1. **Refactor Challenge:**
   - Take a poorly documented function from your codebase
   - Use advanced prompting to generate comprehensive documentation
   - Add error handling and optimization suggestions

2. **Multi-Method Implementation:**
   - Choose a programming problem (e.g., implementing a cache)
   - Generate solutions using both inline suggestions and chat
   - Compare and document the differences

3. **Cross-Language Translation:**
   - Implement the same algorithm in 2-3 different languages
   - Use Copilot to help with language-specific optimizations
   - Note how context affects suggestions across languages

### Deliverables:
- **Before/after code samples** with your prompting strategies
- **Screenshot or recording** of your Copilot interaction
- **Reflection document** on what techniques worked best

---

## Resources for Week 2

### Advanced Prompting Guides
- [GitHub Copilot Prompt Engineering Guide](https://docs.github.com/en/copilot/using-github-copilot/prompt-engineering-for-github-copilot)
- [Best Practices for AI-Assisted Coding](https://github.blog/2023-06-20-how-to-write-better-prompts-for-github-copilot/)

### Practice Scenarios
1. **Algorithm Implementation:**
   - Data structure challenges (trees, graphs, heaps)
   - Sorting and searching algorithms
   - Dynamic programming problems

2. **System Design Patterns:**
   - Design patterns implementation
   - Architecture pattern generation
   - Code organization strategies

3. **Error Handling Patterns:**
   - Exception handling frameworks
   - Logging and monitoring integration
   - Input validation and sanitization

### Keyboard Shortcuts Mastery
- **Ctrl+Enter:** View alternative suggestions
- **Alt+]:** Next suggestion
- **Alt+[:** Previous suggestion
- **Ctrl+Shift+P → "Copilot":** Access all Copilot commands

---

## Success Metrics for Week 2
By the end of this session, participants should be able to:
- Write effective prompts that generate high-quality code
- Choose appropriately between inline suggestions and Copilot Chat
- Handle complex code generation scenarios confidently
- Apply prompt engineering principles to improve code quality
- Collaborate effectively using Copilot in team environments

**Next Week Preview:** Exploring Copilot across different development domains - web, backend, data science, and testing!
