# Setup Guide for Dynamic GitHub Profile

Use this kit in your profile repository:
- Repository name must be exactly: luisgutierrez001
- Repository owner must be: luisgutierrez001

## 1) Create or open your profile repository

If you do not have it yet, create this repository in GitHub:
- Name: luisgutierrez001
- Visibility: Public
- Add a README file

## 2) Copy files from this kit

Copy these files into your profile repository root:
- README.md
- .github/workflows/snake.yml
- .github/workflows/update-readme.yml

## 3) Replace placeholders

In README.md, replace:
- Live Demo links
- Architecture Notes link
- Case Study link
- LinkedIn URL
- Portfolio URL

## 4) Run workflows manually once

In GitHub:
- Go to Actions
- Run "Generate Snake"
- Run "Update README Timestamp"

After the first run:
- The workflow creates branch: output
- Snake image starts rendering in README
- Timestamp section updates automatically

## 5) Optional hardening

- Keep all workflows in YAML with spaces only (no tabs)
- Do not start YAML files with markdown separators
- Keep README markers in one line:
  <!--LAST_UPDATED_START-->value<!--LAST_UPDATED_END-->
