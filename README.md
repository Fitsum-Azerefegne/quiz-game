🧠 Quiz Game - README

A simple command-line quiz game that tests your knowledge with true/false questions.

 🚀 How to Run
1. Make sure you have Python installed
2. Clone/download all files:
   - `quiz_brain.py`
   - `question_model.py`
   - `data.py`
3. Run the game:
   ```bash
   python quiz_brain.py
   ```

 🎮 How to Play
- Answer each question with "True" or "False"
- The game will track your score as you progress
- See your final score at the end

 📂 Files Overview
- `quiz_brain.py` - Main game logic and flow
- `question_model.py` - Question class definition
- `data.py` - Contains all the quiz questions and answers

 📊 Question Format
Each question follows this structure:
```python
{
    "text": "Question here", 
    "answer": "True"  # or "False"
}
```

 📝 Customizing Questions
1. Edit `data.py` to add/remove questions
2. Follow the same JSON format
3. Save and run the game again

 📈 Scoring
- 1 point for each correct answer
- Final score shown as: `correct/total`


Enjoy the quiz! Test your knowledge and try to get a perfect score! 🏆
