- This is a question paper generator

- Requirements: You need to have Node.js > v10 installed in your system.

- Follow these steps to run the programme.

1. Clone the repo.

```bash
git clone https://github.com/SainiAditya1/Backend-Internship-Assignment-.git
```

2. Add questions inside data object in question-store.json file. \
   Ex:
   // Question Subject Topic Difficulty Marks

```json
["What is the speed of light", "Physics", "Waves", "Easy", 5]
```

3. Setup config.json file. \
   Ex: For total 100 marks, 20% easy, 50% medium and 30% hard difficulty questions and question store file path.

```json
{
	"totalMarks": 100,
	"difficulty": {
		"easy": 20,
		"medium": 50,
		"hard": 30
	},
	"filePath": "./question-store.json"
}
```

4. Run .

```bash
cd Backend-Internship-Assignment-

node main.js
```

5. Result format (in arrays questions will be stored).

```json
{
	"easy": [],
	"medium": [],
	"hard": []
}
```
