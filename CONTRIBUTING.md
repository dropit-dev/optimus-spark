# Contributing to Optimus Spark

🎉 Thank you for considering contributing to **Optimus Spark**! We’re excited to have you join the team. Whether you’re fixing a bug, adding a new template, or improving documentation, your contribution is valuable to us.

---

## 🛠 How to Contribute

1. **Fork the Repository**  
   Start by forking the repository to your own GitHub account:
   ```bash
   git clone https://github.com/your-username/optimus-spark.git
   ```
   Replace `your-username` with your GitHub username.

2. **Create a New Branch**  
   Work on your changes in a new branch to keep things organized:
   ```bash
   git checkout -b feature/feature-name
   ```
   Replace `feature-name` with something descriptive, like `add-new-template` or `fix-bug-xyz`.

3. **Make Your Changes**  
   - Add your amazing feature, bug fix, or improvement.  
   - Follow the coding style and conventions of the project.  

4. **Test Your Changes**  
   Ensure your changes work as expected and do not break existing functionality:
   ```bash
   pytest
   ```
   If applicable, write new tests for your feature.

5. **Commit Your Changes**  
   Use a meaningful commit message:
   ```bash
   git add .
   git commit -m "Add new transformation template for [use-case]"
   ```

6. **Push Your Branch**  
   Push your branch to your forked repository:
   ```bash
   git push origin feature-name
   ```

7. **Create a Pull Request**  
   - Go to the original **Optimus Spark** repository.  
   - Click the **New Pull Request** button.  
   - Select your branch and add a clear description of your changes.

---

## ✍️ Guidelines for Contributions

### Code Style
- Follow [PEP 8](https://peps.python.org/pep-0008/) for Python code style.
- Write descriptive comments to explain complex logic.

### Documentation
- Update or add relevant documentation for any new templates or features.
- Use clear and concise language.

### Tests
- Write unit tests for new functionality.
- Ensure all tests pass before submitting a pull request:
  ```bash
  pytest
  ```

### Templates
If you’re adding a new transformation template:
- Place it in the appropriate subfolder of the `templates` directory.
- Include a short description in the file’s docstring explaining its purpose.
- Add an example usage in the `examples` directory.

---

## 🤝 Code of Conduct
By participating in this project, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md). Be respectful, inclusive, and constructive.

---

## 📧 Need Help?
If you have questions or need assistance, feel free to open a [GitHub Issue](https://github.com/yourcompany/optimus-spark/issues) or reach out to the maintainers.

---

### 🚀 Ready to Transform?  
We can’t wait to see your contributions! Let’s roll out 🚗💨 and make **Optimus Spark** even more powerful.
