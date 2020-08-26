## Vulnerable Flask Application for ZAP to test against e2e and/or automate in GitHub Actions

> There are still deprecated dependancy (like MySQL-python) and e2e testing issues but here is 'jist' ;-)
1) cd into app folder and run this command 'pip install -r requirements.txt'
2) to serve app from app folder, run 'python app.py'
3) to run e2e test, cd to tests folder and run 'python e2e_zap.py'

## Ports
> Vuln App should appear on port 5050 & ZAP should be set to run on port 8090
