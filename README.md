
<div align="center">
  <img src="https://osschile.lat/assets/logo.png" alt="OSSChile Logo" width="200">
</div>

<div align="center" style="display: flex; align-items: center; gap: 10px;">
  <h1>🇨🇱 <a href="osschile.lat">OSSChile</a></h1>
  <img src="https://img.shields.io/github/actions/workflow/status/OSSChile/OSSChile.github.io/pages%2Fpages-build-deployment" alt="GitHub Actions Workflow Status">
</div>

This is list of open-source projects made in Chile, with links to their repositories. Whether you're looking to contribute, explore, or just get inspired, this is the place to find cool projects from the Chilean community.

## How to Add a New Project

To add your project to the list, follow these steps:

1. **Fork this repository**: Click the "Fork" button at the top right of this page.
2. **Clone your fork**:

   ```bash
   git clone https://github.com/your-username/OSSChile.github.io.git
   ```

3. **Modify the `data.yaml` file**: Add your project details in the following format:

   ```yaml
   - url: "https://github.com/your-username/your-project"
     domain: ["domain1", "domain2"]  # e.g., ["ai", "cli"]
     lang: "programming-language"     # e.g., "rust", "python"

4. **Commit and push your changes**:

   ```bash
   git add data.yaml
   git commit -m "Add [Your Project Name] to the list"
   git push origin main
   ```

5. **Submit a Pull Request**: Go to the original repository and click "New Pull Request" to submit your changes for review.

## Project Structure

- `data.yaml`: Contains the list of projects in YAML format.
- `index.html`: The main webpage displaying the projects.
- `assets/`: Directory for static files (CSS, images, etc.).

## Contributing

We welcome contributions! If you have any suggestions or improvements, feel free to open an issue or submit a pull request.

Join our Discord community for discussions and updates: [Discord Server](https://discord.gg/nNS2nT6WpM)

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=OSSChile/OSSChile.github.io&type=Date)](https://www.star-history.com/#OSSChile/OSSChile.github.io&Date)
