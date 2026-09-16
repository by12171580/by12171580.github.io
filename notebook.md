## Table of Contents





- [Notebook Style Guide](#markdown-style-guide-for-coding-notebooks)

  - [Headings](#headings)

  - [Text Formatting](#text-formatting)
 
  -  [Blocks](#blocks)
    
- [Concepts](#concepts)
  
- [Vocabulary](#vocabulary)

  
# By12171580 Notebook.


 
## Blocks
- Hat blocks have a rounded top and always sit at the very top of a script to start a program when a specific event happens, like clicking a green flag. Directly underneath, you can snap together puzzle-like Stack or Command blocks, which feature notches on top and bumps on the bottom to perform main actions like moving a character. 

- Stack or Command blocks feature notches on top and bumps on the bottom to perform main actions like moving a character, snapping together like puzzle pieces directly underneath a hat block.

- C-blocks use an open C-shape that creates a container space meant to wrap around and control other stack blocks.

- Reporter blocks are oval-shaped and hold text or numbers to drop into round input fields whenever other blocks require data.

- Boolean blocks have a hexagonal shape to fit into diamond-shaped slots, reporting whether a specific condition is strictly true or false.

- Repeat blocks are a specific type of C-block that loops the code inside them a set number of times based on the number you type into their input slot.

- Wait Until blocks pause the program entirely, requiring a hexagonal Boolean condition to become true before letting the script move forward.

- If Then blocks use their diamond-shaped notch to check a condition, running the inner code of their C-shape only if that condition evaluates to true.

- Forever blocks are C-blocks with a closed bottom that run their inner code continuously until the program is completely stopped.

## Concepts
- Sequence dictates the exact step-by-step order a computer must execute instructions to achieve the correct result.

- Parameters act as specific settings that change how an individual command behaves when input values are modified.

- Loops / Iteration provide a programming shortcut to repeat actions efficiently without writing redundant code.Sensors serve as the physical components that allow a robot to detect and measure data from its surroundings.

- Sense → Think → Act represents the continuous cycle where a robot gathers data, processes it, and responds physically.Comparisons evaluate the relationship between two values using math symbols to determine how they relate.

- Booleans & Conditions produce a simple true-or-false value that a computer uses to check states.Conditionals function as "if-then" choices that dictate exactly how a program branches and reacts to situations.

- Coordinates map out the exact horizontal and vertical position of a robot on an X and Y grid.

- Patterns reveal structural repetitions that allow programmers to design cleaner and more efficient algorithms.

## Vocabulary
1. VR Robot + Playground
- VR Robot: A virtual robot used in digital learning environments to practice coding and robotics concepts without needing physical hardware.
- Playground: The 3D virtual environment or map where the VR Robot interacts, moves, and executes programs.

2. Programming Language + Project
- Programming Language: A formal set of instructions and syntax (such as Blocks or Python) used to write code that a computer or robot can understand.
- Project: A specific program or file created by combining code blocks or text to make the robot complete a designated task.

3. Behavior + Command
- Behavior: The action or series of actions that a robot performs, such as turning around or stopping at a wall.
- Command: A specific instruction within a program that tells the robot to perform a single, distinct action.

4. Drivetrain
* Drivetrain: The system of components (motors, wheels, and gears) that allows the VR Robot to move forward, backward, and turn.

5. Loop + Iteration
- Loop: A programming structure that repeats a specific block of code multiple times or until a condition is met.
- Iteration: A single repetition of a loop or a single execution of a set of instructions.

6. Sensor + Bumper Sensor
- Sensor: A device that detects and measures physical properties from the surrounding environment and sends that data to the robot.
- Bumper Sensor: A physical-contact sensor on the VR Robot that detects when it bumps into an object or wall.

7. Boolean + Condition + TRUE/FALSE
- Condition: A statement or check that evaluates to either true or false to determine what the robot should do next.
- Boolean: A data type that can only have one of two possible values: TRUE or FALSE.

8. Distance Sensor + Threshold
- Distance Sensor: A sensor that uses ultrasonic waves or lasers to measure how far away an object or wall is from the front of the robot.
- Threshold: A specific numerical value or limit used in a program to trigger an action (e.g., stopping when the distance sensor reads less than 50 mm).

9. Coordinate Plane + X/Y Coordinates (X-axis, Y-axis, X-coordinate, Y-coordinate)
- Coordinate Plane: A two-dimensional grid system formed by a horizontal line (X-axis) and a vertical line (Y-axis).
- X/Y Coordinates: The specific values (X-coordinate and Y-coordinate) that pinpoint the exact location of the VR Robot on the grid.

10. Location Sensor
- Location Sensor: A built-in sensor that reads and reports the current X and Y coordinates, as well as the angle (heading), of the VR Robot on the playground.

11. Comment
- Comment: A note written within the code by the programmer to explain how the program works; it is completely ignored by the robot during execution.

12. Eye Sensor
- Eye Sensor: A color and light sensor on the VR Robot (usually pointing front or down) that detects the presence, color, and brightness of objects or lines.

13. Conditional Statement
- Conditional Statement: A programming construct (like an "If-Then" statement) that directs the robot to make decisions and execute specific code only if a certain condition is met.


## Markdown Style Guide for Coding Notebooks

Follow this guide to keep your coding notebook **clear, consistent, and professional**.  

This ensures your notes are easy for you (and others) to read later.


## Headings

**When to use:** Organize your notebook into sections (like days, topics, or projects).  

- `#` for the notebook title (use once at the top).  

- `##` for each day or major topic.  

- `###` for subsections (like "Notes", "Practice", "Reflections").  

# Example:

# My Coding Notebook

## Day 1

### Notes

### Practice

# Text Formatting

When to use: Highlight important ideas or add emphasis.

Use bold for key terms or definitions.

Use italic for emphasis or side comments.

Use inline code for keywords, functions, or commands.


# Example:

**Class** = a blueprint for objects  

*Remember:* always test your code  

Use `System.out.println()` to print

 

# Code Blocks

When to use: Anytime you write multiple lines of code.

Inline code for short snippets.

Fenced code blocks with language for full examples.

# Example:

```java

public class Hello {

    public static void main(String[] args) {

        System.out.println("Hello World!");

    }

}

```

# Lists

When to use: Organize steps, notes, or key points.

Numbered lists for sequences or steps.

Bulleted lists for unordered ideas.

# Example:

Define the class
Write the main method
Test your program
Variables

- Loops

- Conditionals

 

# Checklists

When to use: Track progress on assignments or tasks.

# Example:

[x] Complete coding warm-up

- [ ] Finish project draft

- [ ] Reflect on learning

 

# Blockquotes

When to use: Call out notes, reminders, or teacher comments.

# Example:

> 💡 Remember: Loops repeat code until a condition is false.

 

# Tables

When to use: Compare values, track progress, or organize data neatly.

# Example:

| Task        | Status   | Notes          |

|--------------|------------|-----------------| 

| Homework 1  | Done #  | Submitted      |

| Homework 2  | Pending  | Needs review   |

 

# Links & Images

When to use: Add references, resources, or visuals.

# Example:

[Java Docs](https://docs.oracle.com/javase/8/docs/api/)  

![Markdown Logo](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)

To make an image that is a link, paste the image, then add the following before it, replacing website address with the link:

<a href="website address">

And after the image info, add: </a>

# Collapsible Sections

When to use: Hide solutions, extended notes, or extra details.

# Example:

<details>

  <summary>Click to reveal solution</summary>

  

System.out.println("Answer: 42");

</details>

 

# Footnotes

When to use: Add references or side notes without cluttering the page.

# Example:

This concept is related to object-oriented programming.[^1]

[^1]: See "Objects and Classes" in your textbook.

 

# Style Rules

Consistency matters more than creativity

Always use headings to structure your notes.

Always use code blocks for multi-line code.

Clarity first

Bold key terms.

Use lists instead of long sentences when outlining steps.

Professional tone

Don’t mix casual notes with formal work in the same section.

Use blockquotes for reflections or teacher feedback.

Track your learning

Use checklists to mark what’s done.

Use collapsible sections if you want to hide answers until review time.

 

# Bottom Line:

Headings = Structure

Bold/Italic = Emphasis

Code blocks = Code

Lists = Steps/Ideas

Tables = Organization

Checklists = Progress

Blockquotes = Notes/Tips

Collapsible = Hide/Show detail

Keep it simple, consistent, and clear.
