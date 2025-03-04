# 👋 Hello, World!

## About Me

```cpp
#include <iostream>
#include <string>
#include <vector>

class Superpatrex
{

private:
    std::string username;
    std::string linkedinUrl;
    std::vector<std::string> pronouns = {"he", "him", "his"};
    std::vector<std::string> programmingLanguages = {"C#", "C++", "C", "Java", "Python", "JavaScript"};
    std::vector<std::string> tools = {"Git", "VS Code", "Unity"};
    std::vector<std::string> hackathonWins = {"ShellHacks", "KnightHacks", "HackJam",
                                            "IVRHA Virtual Reality and Healthcare Hackathon"};

    void display(std::string itemName, const std::vector<std::string>& items)
    {
        std::cout << itemName << std::endl;

        for (const auto& item : items) {
            std::cout << " - " << item << std::endl;
        }
    }

public:
    Superpatrex(std::string uname, std::string linkUrl) : username(uname), linkedinUrl(linkUrl)
    {
    }

    void displayUserInfo() {
        std::cout << "Username: " << username << std::endl;
        std::cout << "LinkedIn: " << linkedinUrl << std::endl;

        display("Programming Languages", programmingLanguages);
        display("Tools", tools);
        display("Hackathon Wins", hackathonWins);
    }
};

int main(void)
{
    Superpatrex superpatrex("Superpatrex", "https://www.linkedin.com/in/johnandrewscs/");
    superpatrex.displayUserInfo();
 
    return 0;
}
```

Hi there! I'm Superpatrex, a passionate software engineer and Honors Computer Science student at the University of Central Florida. Welcome to my GitHub profile!

- 🌐 Find me on the web: [My LinkedIn](https://www.linkedin.com/in/johnandrewscs/)

## 🔧 Technologies & Tools

Here are some of the technologies and tools I frequently work with:

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Superpatrex&layout=compact&theme=dark)

## 📊 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Superpatrex&count_private=true&show_icons=true&theme=dark)

## 🌱 Current Learning

I'm currently learning and interested in virtual reality and general software development. Always eager to explore new things and broaden my knowledge!

## 🎯 Current Projects

Here are some projects I'm currently working on:

- [InterView](https://github.com/Superpatrex/InterView.git): Virtual Reality Application written in Unity utilizing a large language model to interview individuals for different positions in companies, Oculus Voice SDK, and XR Interactive Toolkit.
- [Quackademy](https://github.com/Superpatrex/Quackademy.git): Virtual Reality Application written in Unity to function as a classroom for neuro-divergent elementary school children
- [DABOMS](https://github.com/Superpatrex/VRHHI.git): Augmented Reality Application written in Unity using GroKit Core that simulates visual and nervous system disorders for GERT suits, product development, and generation of empathy for those affilicted with those disabilities, diseases, and impairments

## 💻 Hackathons Attended

### ShellHacks 2023
- 🏆 **1st Place:** Microsoft Mixed Reality Challenge
- 🏆 **2nd Place:** Assurant Way Challenge
- 🚀 Check out my team's project [Quackademy](https://github.com/Superpatrex/Quackademy)
- 📄 [Devpost](https://devpost.com/software/interview-ai-powered-interview-prep)

### Knight Hacks 2023
- 🏆 **2nd Place:** Overall
- 🚀 Check out my project [InterView](https://github.com/Superpatrex/InterView)
- 📄 [Devpost](https://devpost.com/software/interview-ai-powered-interview-prep)

### HackJam
- 🏆 **1st Place:** Overall
- 🚀 Check out my project [Cubedle](https://github.com/Superpatrex/Cubedle)

### VRHA Virtual Reality and Healthcare Hackathon
- 🏆 **1st Place:** Overall
- 🚀 Check out my project [DABOMS](https://github.com/Superpatrex/VRHHI)

### ShellHacks 2024
- 🏆 **2st Place:** Overall
- 🏆 **1nd Place:** Microsoft AI Challenge
- 🏆 **2nd Place:** Google Challenge
- 🚀 Check out my team's project [ARSL](https://github.com/Superpatrex/ARSL)
- 📄 [Devpost](https://devpost.com/software/arsl-vr-asl-learning)

### Knight Hacks 2024
- 🏆 **1nd Place:** Most Useful Project
- 🚀 Check out my project [Chat Clip That](https://github.com/Superpatrex/chat-clip-that)
- 📄 [Devpost](https://devpost.com/software/chat-clip-that)
  
## 🚀 Interests

Apart from coding, I have a keen interest in:

- 📚 Reading and learning new technologies.
- 🍽️ Cooking new foods and always eating.

## 📫 Let's Connect

<div align="center">
 <a href="https://www.linkedin.com/in/johnandrewscs/" target="_blank"><img align="center" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
 <a href="https://github.com/Superpatrex" target="_blank"><img align="center" src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" target="_blank"></a>  
  <a href="https://www.jackandrews.xyz" target="_blank"><img align="center" src="https://img.shields.io/badge/Personal%20Website-https://www.jackandrews.xyz-<BLUE>?style=for-the-badge&logo=google-chrome&logoColor=white" target="_blank"></a>  
</div>
