QuizIO 🎯

**QuizIO** is an interactive, terminal-based quiz platform designed for UNIX systems. It provides a simple yet functional interface for conducting timed quizzes with automatic scoring and result recording.


🧠 Features

- ✅ **Multiple-choice quiz format**
- 🔄 **Shuffling of options** using `shuff` flag
- ⏱️ **Time-limited quizzes** (default: 10 minutes, configurable)
- 📋 **Scoring system**:
  - +4 for correct answers
  - -1 for incorrect answers
  - 0 for unattempted
- 🧾 **Student details recorded** (name, date, time)
- 💾 **Results saved to a `.txt` file**
- 📅 Automatically logs quiz date & time



💻 Technologies Used

- Bash / Shell scripting
- UNIX command-line tools (like `date`, `read`, etc.)
- File I/O for saving results



🚀 How to Run

```bash
# Give executable permission if needed
chmod +x quizio.sh

# Run the script
./quizio.sh
