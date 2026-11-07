# FUTURE_PE_01: AI Website Copy Generator for Local Businesses

- **Internship:** Future Interns, Prompt Engineering Track
- **Task 1:** AI Website Copy Generator for Local Businesses 
- **Intern:** Mounetha E
- **Tools used:** Claude, GitHub

## Objective
Use structured prompts to generate website-ready copy (Homepage, Services, CTA) for different local businesses, adapting the tone to each business type.

## Businesses covered
| # | Business (sample) | City | Tone |
|---|---|---|---|
| 1 | Glow Beauty Salon | Salem | Friendly, warm |
| 2 | Brew & Bite Cafe | Salem | Casual, fun |
| 3 | CareFirst Family Clinic | Salem | Trustworthy, calm |

*These are sample businesses created for practice.*

## Repository structure
```
FUTURE_PE_01/
├── README.md
├── 01_prompts.md     (prompt template, prompt logic, final prompts)
└── 02_outputs.md     (generated website copy)
```

## Workflow
```
Pick business -> Write structured prompt (RTCFT) -> Generate -> Review -> Refine -> Save prompt + output
```

## Key learnings
- A structured prompt (Role, Task, Context, Format, Tone) gives far better copy than a one-line prompt.
- The same prompt with a different Tone line changes the whole feel of the content.
- Short follow-up prompts ("make it shorter", "add a stronger CTA") improve the output quickly.
- Unverifiable claims ("best salon", "years of experience", "slots fill up fast") were left out on purpose. Real details from the client can be added later.
