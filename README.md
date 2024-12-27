# 📑 Latex-CV-Builder

Create a **professional and elegant curriculum vitae** using this LaTeX template. Perfect for showcasing your education, work experience, skills, and certifications in a clear and structured format.

## 📸 Preview
Check out an example of the generated CV:
[CV.pdf](CV.pdf)

## 🛠️ How to Use

Follow these simple steps to customize your own LaTeX CV:

1. **Open the `main.tex`** file in your preferred LaTeX editor.
2. **Customize your personal information** by editing the `\constants.tex` file at the beginning of the document. Here, you can replace placeholders with your details such as:
   - Full Name
   - Location
   - Email Address
   - GitHub Username
   - LinkedIn Profile
3. **Personalize each section** by modifying the corresponding `.tex` files found in the `sections` directory. Here's a breakdown of each section:
   - **`summary.tex`**: Write a brief summary of your professional background and career goals.
   - **`skills.tex`**: List your technical expertise, programming languages, and soft skills.
   - **`education.tex`**: Add your academic qualifications and any relevant achievements.
   - **`experience.tex`**: Include your work experience, highlighting roles, responsibilities, and key accomplishments.
   - **`certifications.tex`**: Mention any certifications or training programs you've completed.
4. Once you've edited the content, **compile** the `main.tex` file to generate a polished PDF of your CV.
5. Review the output PDF to ensure that everything looks perfect.
6. You can also **customize** the LaTeX template further to change fonts, colors, or layout according to your preferences.
7. When satisfied, **share** your CV digitally or print it for physical distribution.

## ⚙️ Prerequisites

Ensure you have a LaTeX editor installed on your system. Some popular options include:
- **Overleaf** (Web-based)
- **TeXShop** (macOS)
- **TeXworks** (Windows)
- **TeXLive** (Linux)

## 🎨 Additional Customization

Feel free to get creative with this template:
- **Change colors, fonts, and layouts** to better reflect your style.
- **Add or remove sections** to fit your specific needs (e.g., awards, publications, hobbies).
- Modify the overall structure of the CV to match your personal branding.

## ✔️ Compatibility and Testing

This template has been thoroughly tested on various LaTeX editors and operating systems, including:
- **Overleaf** (web-based)
- **TeXShop** (macOS)
- **TeXworks** (Windows)
- **TeXLive** (Linux)

## 🚀 Generating Releases

This project uses **GitHub Actions** to automate the creation of a new release and version tag whenever changes are merged into the `main` branch. Here's how it works:

1. **Automated Release Creation**:
   - When a commit is merged into `main`, a new GitHub release is automatically created.
   - This process includes creating a version tag and packaging the generated CV PDF file.

2. **Version Control**:
   - Each release is versioned based on the tags. The versioning follows a simple scheme (e.g., `v1.0.0`).
   - You can view the generated releases by navigating to the [Releases](https://github.com/RArroyo00/Latex-CV-Builder/releases) section of this repository.

3. **GitHub Actions Workflow**:
   - The workflow triggers automatically on a merge to `main` using a `workflow_dispatch` trigger or a `push` event.
   - Once the workflow completes successfully, the new release is uploaded along with the latest CV PDF.
   
For more detailed information, you can check the [GitHub Actions](https://github.com/RArroyo00/Latex-CV-Builder/actions) for this project.


## 🤝 Contributions and Collaboration

We welcome contributions! If you have suggestions for improvements or have encountered an issue, feel free to:
- Open an [issue](https://github.com/RArroyo00/Latex-CV-Builder/issues)
- Submit a [pull request](https://github.com/RArroyo00/Latex-CV-Builder/pulls)

## 📜 License

This project is licensed under the **Creative Commons License**. For more information, please refer to the `LICENSE.md` file.

## 🔗 Useful Links
- [LaTeX Tutorial](https://www.latex-tutorial.com/) - Learn the basics of LaTeX.
- [CV Style Guide](https://www.careercenter.illinois.edu/resumes) - Tips for creating a winning CV.
- [Creative CV Examples](https://www.visualcv.com/examples/) - Get inspired by real-world CV designs.
