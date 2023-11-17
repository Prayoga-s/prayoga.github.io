# prayoga-website
This website is static website used to host our projects and capabilities.
# Dev Docs
- Clone the repo from `https://github.com/PrayogaLab/home.git` and cd into the repo
- Use Python to make the build.
- Create Virtual Env with `python -m venv venv`
- activate the virtual environment
- Install packages from requirement.txt `pip install -r /path/to/requirements.txt` 
    - Not Required Step: to add the packages into file use `pip freeze > requirements.txt`
- Create new branch and make changes and push and then make PR.
- Use this docs to refer for any doubts `https://www.mkdocs.org/getting-started/`, `https://www.mkdocs.org/user-guide/deploying-your-docs/`
- Use below command to direct add to github page `mkdocs gh-deploy --config-file ./mkdocs.yml --remote-branch <Remote-branch-name>`