# Project Documentation for ffmtg

This project is a GitHub Pages site that includes a top page with a sidebar linking to 16 folders (ff1 to ff16), each containing a Markdown page. Below are the instructions for setting up and using the project.

## Project Structure

The project is organized as follows:

```
ffmtg
├── _includes
│   └── sidebar.html
├── _layouts
│   └── default.html
├── ff1
│   └── index.md
├── ff2
│   └── index.md
├── ff3
│   └── index.md
├── ff4
│   └── index.md
├── ff5
│   └── index.md
├── ff6
│   └── index.md
├── ff7
│   └── index.md
├── ff8
│   └── index.md
├── ff9
│   └── index.md
├── ff10
│   └── index.md
├── ff11
│   └── index.md
├── ff12
│   └── index.md
├── ff13
│   └── index.md
├── ff14
│   └── index.md
├── ff15
│   └── index.md
├── ff16
│   └── index.md
├── _config.yml
├── index.md
└── README.md
```

## Setup Instructions

1. **Clone the Repository**: Start by cloning the repository to your local machine.
   ```
   git clone https://github.com/yourusername/ffmtg.git
   ```

2. **Navigate to the Project Directory**:
   ```
   cd ffmtg
   ```

3. **Edit the Markdown Files**: Each folder (ff1 to ff16) contains an `index.md` file. You can edit these files to add content specific to each section.

4. **Configure the Site**: Modify the `_config.yml` file to set up your site settings, including the theme and other options.

5. **Add Sidebar Links**: In the `_includes/sidebar.html` file, ensure that links to each of the 16 folders are correctly set up.

6. **Deploy to GitHub Pages**:
   - Push your changes to GitHub:
     ```
     git add .
     git commit -m "Initial commit"
     git push origin main
     ```
   - Go to your GitHub repository settings and enable GitHub Pages from the `main` branch.

## Usage

Once deployed, you can access your GitHub Pages site at `https://yourusername.github.io/ffmtg`. The sidebar will allow you to navigate between the different sections (ff1 to ff16).

## Conclusion

This README provides a basic overview of the project structure and setup instructions for the GitHub Pages site. For further customization, refer to the Jekyll documentation or GitHub Pages documentation.