📚 AI Study Pal

![AI Study Pal Banner](assets/banner.png)  <!-- Replace with your banner image -->

**AI Study Pal** is an intelligent **learning companion** designed to help students of grades 1–10 study efficiently.
It generates **personalized weekly study plans**, interactive **quizzes**, and provides **tips for every subject**.
This project runs directly in **Google Colab** using **Flask and Ngrok**, making it accessible via a **public URL**.

📑 Table of Contents

1. [Features](#-features)
2. [Tech Stack](#-tech-stack)
3. [Setup & Installation](#-setup--installation)
4. [Usage](#-usage)
5. [Screenshots / Demo](#-screenshots--demo)
6. [Future Plans](#-future-plans)
7. [Contributing](#-contributing)
8. [License](#-license)
9. [Contact](#-contact)

✨ Features

* Generate **7-day personalized study plans** for each student
* Interactive **10-question quizzes** for each subject
* Supports **Maths, English, Science, Social**
* Adaptive quiz difficulty based on **student grade** (easy, medium, hard)
* Download **quiz CSV files** for offline practice
* Beautiful, **responsive UI** with gradient backgrounds
* Fully **cloud-based** (runs in Google Colab) — no local setup required

🛠 Tech Stack

* **Language:** Python
* **Web Framework:** Flask
* **Tunneling:** Ngrok (for public URLs)
* **Platform:** Google Colab / Jupyter Notebook
* **Libraries:** `flask`, `pyngrok`, `random`, `csv`

🚀 Setup & Installation (Google Colab)

1. Open the notebook [`AI_Study_Pal.ipynb`](https://github.com/Madhu-271005/Launched-Global-Projects/blob/main/AI_Study_Pal.ipynb) in **Google Colab**
2. Install required libraries (already included in the notebook):

   ```python
   !pip install flask pyngrok --quiet
   ```
3. Replace your **Ngrok token** in the notebook:

   NGROK_TOKEN = "YOUR_NGROK_AUTH_TOKEN"
   
5. Run the **entire notebook**
6. Wait for Colab to print the **public URL**:

   ```
   Public URL: https://xxxx-xxx-xxx-xxx.ngrok.io
   ```
7. Click the URL to open the **AI Study Pal web interface**

> ✅ No local installation required — runs entirely in Google Colab

🎮 Usage

1. Open the **public Ngrok URL**
2. Fill the form with:

   * **Student Name**
   * **Grade** (1–10)
   * **Board** (CBSE, ICSE, State)
   * **Subject** (Maths, English, Science, Social)
   * **Hours per day**
3. Click **Generate Study Plan**
4. View your:

   * **Weekly study plan** (2 lessons per day)
   * **Tips for the selected subject**
   * **Interactive quiz** with 10 questions
5. Optionally, click **Download Quiz CSV** to save quiz offline


## 🖼 Screenshots / Demo

### Home Page / Input Form

<img width="1920" height="1080" alt="Screenshot (56)" src="https://github.com/user-attachments/assets/e4578166-830b-476c-b13b-0c0a695ad9f5" />

<img width="1920" height="1080" alt="Screenshot (61)" src="https://github.com/user-attachments/assets/2b8fb570-50b5-4ecf-916a-e79dc2f8b7f9" />


### Generated Study Plan & Quiz

<img width="1920" height="1080" alt="Screenshot (57)" src="https://github.com/user-attachments/assets/a295432d-7c37-44a7-b230-31cec9f67131" />


### Quiz CSV Download

<img width="1920" height="1080" alt="Screenshot (58)" src="https://github.com/user-attachments/assets/af3e7104-6184-490c-8778-ffccce266952" />

<img width="1920" height="1080" alt="Screenshot (60)" src="https://github.com/user-attachments/assets/c474a0d1-fd61-4799-b295-a604d8c08a93" />

---

## 🛠 Future Plans

* 🎤 **Voice-based input** for easier question entry
* 🌍 **Multi-language support** for students in regional languages
* 📊 **Student performance tracking** to visualize progress over time
* ➕ Add **more subjects and advanced question templates**
* 🔗 Connect with **Google Sheets or database** to save study plans
* 
## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch (`feature/new-feature`)
3. Commit your changes
4. Open a Pull Request

 📄 License

This project is licensed under the **MIT License** – see [LICENSE](LICENSE) for details.

## 📬 Contact

**Author:** Madhusree Sivakumar
🔗 GitHub: [Madhu-271005](https://github.com/Madhu-271005)
📧 Email: madhusiva2710@gmail.com


💡 *AI Study Pal – Study Smarter, Not Harder!*


This way your **repo will look extremely professional and complete**.

Do you want me to do that next?
