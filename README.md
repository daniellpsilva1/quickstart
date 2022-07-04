# Vital quickstart

To get started with Vital quickstart, start with reading our [Docs](https://docs.tryvital.io/welcome/quickstart)

To run the backend.

```
# Note: If on Windows, run
# git clone -c core.symlinks=true https://github.com/vital/quickstart
# instead to ensure correct symlink behavior
git clone https://github.com/tryvital/quickstart.git
cd backend/python

# Copy the .env.example file to .env, then fill
# out VITAL_CLIENT_ID and VITAL_SECRET in .env
cp .env.example .env

# Note: must use python 3
# For virtualenv users:
# virtualenv venv
# source venv/bin/activate
poetry install

# Start the backend app
source ./start.sh
```

To run the frontend

```
# Install dependencies
cd quickstart/frontend
npm install

# Start the frontend app
npm dev

# Go to http://localhost:3000
```
