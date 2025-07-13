🚀 About Me
🎓 Computer Engineering Student @ Universal Engineering College

💻 Developing impactful web & mobile apps

🌐 Exploring the latest in AI, Web3, and System Design

🛠️ Experienced with Python, JavaScript, React, Node.js, C/C++, and more

📚 Always learning, always building

🌟 Goals
🚀 Launch scalable products

🎯 Contribute to open-source

🌍 Make tech more accessible and meaningful

🔗 Connect With Me
📧 Email | 🔗 LinkedIn | 🌐 Portfolio
ujolkarki293@gmail.com
# ujwalkarki.py

class Developer:
    def __init__(self, name, skills, motto):
        self.name = name
        self.skills = skills
        self.motto = motto

    def introduce(self):
        return f"Hi, I'm {self.name} 👋\n" \
               f"I'm a {', '.join(self.skills)}\n" \
               f"My motto: {self.motto}"

ujwal = Developer(
    name="Ujwal Jung Karki",
    skills=["Computer Engineering Student", "Full-Stack Developer", "Tech Explorer", "Problem Solver"],
    motto="Code with purpose, build with impact."
)

print(ujwal.introduce())
