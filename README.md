# llm-fundamentals

### Steps to start a new repo from vs code

1. Create new repo in github through web browser
2. Create target folder in local directory
3. Open installed VS Code and navigate to target folder
4. Open terminal (should ooen in this folder)
5. Pull the repo :: git pull origin main
6. Create a local branch :: git branch local
7. Move to the local branch :: git checkout local
8. conda create --prefix ./env [optional python version python==3.12]
9. conda activate ./env :: (base) should change to (env absolute path)
10. add gitignore file to ignore env files
11. conda instsall pip
12. Place requirements.txt file and run :: pip install -r requirements.txt
13. Create notebook and select kernel to the env (needs to setup for first time)