## Answer Generation Workflow

1. Student uploads Notes PDF
2. Student uploads Module PDF
3. Student uploads Question Bank PDF

4. System extracts text from all documents

5. System identifies all questions from the Question Bank

6. For each question:
   a. Search uploaded notes/modules
   b. Find relevant content
   c. Generate answer only from uploaded content
   d. Format answer according to marks

7. Validate answer quality

8. Generate final Question + Answer PDF

9. Provide download link

 ## Marks Based Answer Rules

2 Marks:
- Definition
- 2–3 key points

5 Marks:
- Definition
- Explanation
- Important points

10 Marks:
- Introduction
- Detailed explanation
- Advantages
- Applications
- Conclusion

15 Marks:
- Introduction
- Detailed explanation
- Subheadings
- Advantages
- Applications
- Example
- Conclusion

- ## AI Rules

1. Use uploaded notes as primary source.
2. Never invent information.
3. Never answer from general knowledge.
4. Expand abbreviations when first used.
5. Use university-style language.
6. Use proper headings.
7. Use point-wise answers.
8. Mention insufficient information if notes do not contain enough content.

 Subject Name

Question 1

Answer

--------------------------------

Question 2

Answer

--------------------------------

Question 3

Answer


When generating answers, the system should retrieve all relevant content from uploaded notes and modules, even if the information spans multiple pages.

Definition

Explanation

Example

Applications

Conclusion

The system should combine relevant information from different sections of the uploaded material into a single structured answer.

When relevant diagrams exist in uploaded notes, include them in the generated PDF along with the explanation.

If the uploaded material does not contain enough information to answer a question, the system must explicitly state that insufficient information is available rather than generating unsupported content.

## AI Processing Pipeline

1. Upload Notes PDF
2. Upload Module PDF
3. Upload Question Bank PDF

4. Extract text from uploaded files

5. Split content into searchable sections

6. Extract questions from question bank

7. For each question:
   - Find relevant content from notes/modules
   - Collect all matching sections
   - Generate structured answer

8. Validate answer quality

9. Generate final PDF

10. Allow download

 ## Answer Templates

### Definition Questions
- Definition
- Key Points

### Explain Questions
- Introduction
- Explanation
- Example
- Conclusion

### Advantages and Disadvantages Questions
- Introduction
- Advantages
- Disadvantages
- Conclusion

### Compare Questions
- Introduction
- Comparison Table
- Key Differences
- Conclusion

## Quality Validation

Before finalizing an answer:

- Content came from uploaded material
- Answer matches mark allocation
- Headings are present
- Grammar is correct
- No unexplained abbreviations
- No unsupported information
- Answer is complete

- ## Future Enhancement

Professor Mode:

- Definition
- Diagram
- Explanation
- Advantages
- Applications
- Conclusion

Generate answers in the format commonly expected by university examiners.
