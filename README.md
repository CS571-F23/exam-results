Download the following files and place them in the `includes` folder...
 - The entire gradebook from Canvas as `gradebook.csv`
 - The scantron summary results from Canvas underneath "TE_EXAMS" as `canvas.csv`
 - The scantron question-by-question breakdown (received via email) as `scantron.csv`

In `canvas.csv`, correct any unknown "SIS User ID". These can be found by cross-referencing `gradebook.csv`

In `answers.json`, specify all exam versions and answer keys. **KEEP IN MIND THIS FILE IS PUBLIC**. CSV files are ignored; however, this file is not. Do not commit this file unless you intend to do so.

In `scantron.csv`, fix all "SpecialCodes" to match the version(s) specified in `answers.json`

Run `node index.js`. Results are saved to `output.csv`. Use this for mail merging.