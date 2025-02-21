# Acceptance Criteria

## CV Upload (User Story: As a user... upload CV)

* The system should allow users to input the CV via text.
* The CV upload feature should support .doc, .docx, and .pdf file formats.
* The system should display an error message if the uploaded file is not in a supported format.
* The system should extract the text content from the uploaded CV for analysis.
* The system should handle different CV formatting styles (e.g., chronological, functional, combination).
* The system should detect the language of the CV.

## Job Description Input (User Story: As a user... input job description)

* The system should allow users to input job descriptions via text or URL.
* The system should extract the text content from the job description.
* The system should handle different job description formats.
* The system should detect the language of the job description.

## AI Analysis (User Story: As a free/paid user... view analysis)

* The system should accurately calculate an ATS score for the CV.
* The system should identify and list the strengths and weaknesses of the CV.
* The system should provide actionable suggestions for improving the CV.

## Optimized CV (User Story: As a paid user... download optimized CV)

* The system should generate an ATS-optimized CV tailored to the job description.
* The optimized CV should be downloadable in a common format (e.g., .docx, .pdf).

## Bilingual Support (User Story: As a user... bilingual support)

* The application should provide a user interface in both English and French.
* The application should use the detected language of the CV and job description to determine the language for result generation.