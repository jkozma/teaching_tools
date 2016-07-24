# teaching_tools
JavaScript snippets for instructional use
These are some pages I've developed, mostly for programming classes, that make use of javascript.

Pseudocode Flowchart Viewer
This tool allows students to view equivalant pseudocode and flowcharts side by side. It is a somewhat large file, as all the flowchart images are embedded.

Robot Drawing Arm
This activity has students fill in missing expressions in a JavaScript program that simulates a "Robot Drawing Arm" using an HTML 5 canvas element.

Grading Rubric
This tool facilitates the creation of rubrics and grading of assignments. To create a rubric, the instructor would substitute appropriate data for the criteria array, specifying the name of the criterion, the point value, and feedback comments for each array element. The name of the assignment should also be changed in the heading-- the page here shows a rubric for a review assignment from a business law class. The rubric may be made available to students to show how the assignment will be graded, and may be used by the instructor to compute grades and generate individualized feedback comments for each students work.

Encryption Puzzle
This page appears to be interactive, but in fact includes no JavaScript. It uses an html textarea element to simulate encryption. Text that is pasted or typed in the text area appears to encrypted because it is displayed with an embedded ROT-13 font. The pre-loaded text is encrypted in ROT-13 so that it appears unencrypted when the page is loaded.

Moodle Matching Question Generator
This is a tool for creating GIFT formatted questions to import into Moodle. Each line of input should include one or more terms and a definition. Several form elements are provided to allow adjustment of question parameters and input format. The tool also provides context sensitive help using help buttons for the various form elements.

Moodle Multiple Choice Question Generator
This is a prototype generating GIFT formatted multiple choice questions from unformatted text passages. My eventual goal is to create a question generator that will do more detailed grammatical analysis. The prototype here simply splits sentences at prepositions, using a tokenizer created by Ariel Flesler. To use the prototype you simply type or paste text in the text area and click Generate Questions. The output can be directly imported into Moodle to create quiz questions, but without post editing the questions will be of poor quality.

Animated Thought Bubbles
This is an animated picture that displays thought bubbles when you mouse over people in the picture. It uses simple variable locks to prevent more than one thought being displayed at a time. It also uses hidden html elements to determine the size of bubbles for the corresponding text.
