# Notes

## Deployment to GitHub Pages
- ```myst init --gh-pages``` did NOT work on 1 November 2024.
- But I figured out that all this command does is placed the deploy.yml file (from https://mystmd.org/guide/deployment-github-pages) into the .github/workflows subdirectory. 
  - GitHub then picks up this file and runs it upon pushes to the repo.