# Ultra Quick Start
A pre-setup django(rest-framework) and vue(tify) template for web development
## Install
```shell
yarn install
virtualenv -p python3 venv
source venv/bin/activate
pip install -r requirements.txt
```
## Folder structure
`api`: Django app for exposing your drf api
`backend`: Django project root
`src`: Vue frontend code
`tests` Vue frontend tests
`public`: Vue public files
#### Ingored folders
`node_modules`: frontend dependencies
`venv`: backend dependencys
`dist`: frontend build output