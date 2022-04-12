# perso-transcendence

add .gitignore 
{# compiled output
.vscode}

add .dockerignore 
{*/node_modules/}

add backend/.env and modify "localhost" by your ip address
{CLIENT_SECRET=9944807a22d32f2777f88bdbe170d6144548d057ec5e39d5f8a7aec2775f05fc
CLIENT_ID=3a68ec0578b1ddb8b72705c05b0e73ef78ff5a1775aa2fe801d02e5437c98a79
REDIRECT_URI=http://localhost/oauth/redirect
ENDPOINT=https://api.intra.42.fr/v2
AUTHORIZATION_URI=https://api.intra.42.fr/oauth/token
SECRET_KEY=topsecret51}


Before run app.sh don't forget to "yarn install"
