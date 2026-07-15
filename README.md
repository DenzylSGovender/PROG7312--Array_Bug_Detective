
# PROG7312 – Theme: Jagged Arrays

---

# Activity 1 –  Bug Detective

## Scenario

The following program crashes when displaying student marks. Your team has been asked you to investigate the issue before it is deployed.

### Code

```csharp
int[][] marks =
{
    new int[] {70,80},
    new int[] {90,100,65},
    new int[] {88}
};

for(int row = 0; row < marks.Length; row++)
{
    for(int col = 0; col < marks.Length; col++)
    {
        Console.Write(marks[row][col] + " ");
    }

    Console.WriteLine();
}
```
---
Student Tasks

Identify the bug.

Explain why the bug occurs.

Correct the code.

Explain why your solution works.

---

# Activity 2 –  Code Review Challenge

## Scenario

You are Senior Software Developers reviewing code submitted by a junior developer before it is merged into production.

### Code

```csharp
int[][] students =
{
    new int[]{10,20},
    new int[]{30,40,50},
    null
};
```
---
Discuss the following:

Is this valid C# code?

What problems could occur?

Under what circumstances would the program crash?

How could you improve the design?

---

# Activity 3 –  Production Failure

## Scenario

The Varsity College timetable system has crashed.

After investigating the logs, the following code was discovered.

### Code

```csharp
string[][] timetable =
{
    new string[]{"Programming","Math"},
    new string[]{"Networking"},
    new string[]{"Cyber","Programming","Database"}
};

Console.WriteLine(timetable[2][3]);

```
---
Discuss the following:

Explain why the program crashes.

Identify the exact line causing the problem.

Correct the code.

Suggest one strategy to prevent this type of error in future.

---
