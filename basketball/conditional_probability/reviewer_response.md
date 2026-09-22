# Response to reviewers

**Module:** A Look at Paul George's Missed Free Throws: Estimating Probabilities from Data

Thank you for your thoughtful feedback and for the student feedback on the module. We have revised the module to address each suggestion, as detailed below.

1. **Broken CSV link.** We replaced the data link in the facilitation notes with the suggested [pgfreethrow.csv link](https://github.com/kgfitzgerald/baylor_apu_score/blob/main/basketball/conditional_probability/pgfreethrow.csv).

2. **Intended student level.** We added an explicit statement at the top of the module identifying the intended audience as introductory statistics students, including first-year college students who are not statistics or data science majors. The facilitation notes continue to identify basic familiarity with R as a prerequisite.

3. **Expected completion time.** We added an estimated completion time of **30-45 minutes** at the top of the module, consistent with the reviewer recommendation and student feedback.

   **Related suggestion: basketball terminology.** We added a short explanation at the beginning of the introduction defining a free throw, noting that each successful attempt is worth one point, and explaining what a "trip to the free throw line" means. The definition links to the NBA rules for reference.

4. **Learning objective about intersections.** We revised the objective to read, "Estimate the probability that two events both occur using data," and updated the corresponding summary item. In "Using the Conditional Probability Formula," we now explicitly explain that "A and B" means that both events occur, introduce the term "intersection" and its notation, and connect it to making both free throws in the same trip. We also corrected the nearby explanation of `lag(make)` to match the code that identifies two made shots.

5. **Motivation for conditional probability.** We added a short discussion at the start of "Estimating Conditional Probabilities." It explains that a player might adjust after a miss, experience pressure, or face conditions that affect both attempts. It defines independence in this context and explains why comparing second-shot probabilities after a make and after a miss is useful. We also clarify that these are possible explanations, that differences in observed proportions can arise by chance, and that those differences alone do not establish dependence or causation.

Thank you again for the suggestions, which helped us clarify the module's audience, expectations, and probability concepts.
