name: Continuous Project Run

on:
  workflow_dispatch:
  schedule:
    - cron: "0 * * * *" # Runs every hour

jobs:
  run-project:
    runs-on: ubuntu-latest

    steps:
    - name: Checkout code
      uses: actions/checkout@v2

    - name: Start Project
      run: npm start
        # Start your project here
        # Example command:
        npm start
