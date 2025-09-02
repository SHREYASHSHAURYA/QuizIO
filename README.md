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

Screenshots

<img width="819" height="115" alt="Screenshot 2025-09-02 234425" src="https://github.com/user-attachments/assets/5b48f53f-69df-4443-9d02-f7b597ae7d99" />
<img width="816" height="491" alt="Screenshot 2025-09-02 234332" src="https://github.com/user-attachments/assets/51674788-35dd-49e4-885d-29f091448188" />
<img width="822" height="291" alt="Screenshot 2025-09-02 234342" src="https://github.com/user-attachments/assets/1b507ade-df83-4453-8a36-32b679c7b43f" />
<img width="815" height="617" alt="Screenshot 2025-09-02 234353" src="https://github.com/user-attachments/assets/723b4de4-e21d-422b-ae32-629869f8ddf6" />
<img width="817" height="498" alt="Screenshot 2025-09-02 234402" src="https://github.com/user-attachments/assets/a4da44f6-1db8-406b-81c9-290051bf19ba" />
<img width="822" height="526" alt="Screenshot 2025-09-02 234413" src="https://github.com/user-attachments/assets/dc066289-d643-4bc1-9a3a-49ee943279e8" />



🚀 How to Run

```bash
# Give executable permission if needed
chmod +x quizio.sh

# Run the script
./quizio.sh
