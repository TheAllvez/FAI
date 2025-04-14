A complete Python code for an application focused on studying and analyzing data from various employees in my company through individual records.

To achieve this, the application must first allow adding, editing, and deleting employee profiles. These profiles should have separate sections for each part of the employee data, and these sections must be: Personal Information, PCOs, Performance, Pulses, Follow-ups, and Notes.

In the Personal Information section, I must be able to edit the following fields:

- Photo (insert a square PNG file)

- Name

- Age

- Date of Birth

- Start Date (with an adjacent display showing the number of years, months, and days from the start date to the current date, which should always be up-to-date)

- Job Title

In the PCOs section, it must be possible to add, remove, and edit surveys completed by the employee. Each survey is a table with multiple quantitative questions (from 0 to 10), grouped by themes. There are 5 questions per theme, and the themes are: Routine, Climate, Relationships, and Environment.
Questions should be labeled using the first two letters of the theme followed by the question number within that theme (e.g., the second question of Relationships would be “Re2”).
The table must support pasting data directly from an Excel spreadsheet, i.e., when multiple columns of numbers are copied from Excel and pasted into the table, the application should understand this as separate columns instead of pasting everything into a single text box.

In the Performance section, I should be able to do the same as in the PCOs section, but instead of having themed groups, the surveys will be simple tables with 10 numbered questions (1 to 10), and the answers should be editable in the same way as in the PCOs section.

In the Pulses section, it must be possible to add, edit, and remove short surveys completed with the employee. Each of these surveys includes three questions:

- Describe your week in one word

- What score would you give to your motivation?

- What will we do differently?

In the Follow-ups section, it must be possible to add, edit, and remove surveys completed with the employee, where the answers are represented by a table titled “Wheel of Life”, which consists of 4 themes with 3 questions per theme. All answers should range from 1 to 10.
The themes and questions are:

- Personal: Health & Vitality, Intellectual Development, Emotional Balance

- Professional: Achievement & Purpose, Financial Resources, Social Contribution

- Relationships: Family, Romantic Relationship, Social Life

- Quality of Life: Hobbies & Fun, Fulfillment & Happiness, Spirituality

Additionally, each survey should have a note section for adding extra information in plain text.

In the Notes section, it should be possible to add text notes with a clear title and date. When editing a note, the full text should open for editing.

Besides all this, it must be possible to add tags to each employee profile, and profiles must be filterable by these tags. Tags should also be applicable to every editable survey in all sections of the profiles.

The application should also have an additional chart tab for analyzing the scores provided in all editable surveys across the profile sections. These charts must be organized by section (e.g., PCOs, Performance, Pulses, etc.) and show data based on the tags applied to each survey.
For example, the Pulse survey chart should show the average of all Pulse responses for tag “1”, and it must be possible to analyze different tags individually.

The application interface should use a dark theme, with shades of gray, black, and purple. The design must be minimalist and easy to navigate.
