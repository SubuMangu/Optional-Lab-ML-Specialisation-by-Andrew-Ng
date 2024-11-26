# Instructions
- Download the dependencies in `requirements.txt`
```
pip install -r ../requirements.txt
```
## Setting up protobuf
- Set the environmental variable of protobuf as shown below.
```
set PROTOCOL_BUFFERS_PYTHON_IMPLEMENTATION=python
```
## Setting up graphviz
1. **Install Graphviz:** Download the latest version of Graphviz in [Graphviz](https://graphviz.gitlab.io/download/) website.
2. **Add Graphviz to System PATH:**
  - Find the installation directory of Graphviz (e.g., `C:\Program Files\Graphviz\bin`).
  - Open the Start Search, type in "env", and select "Edit the system environment variables".
  - In the System Properties window, click on the "Environment Variables" button.
  - In the Environment Variables window, under "System variables", find and select the "Path" variable, then click "Edit".
  - Click "New" and add the path to the Graphviz bin directory.
  - Click OK to close all windows.
3. **Verify Installation:** Open a new command prompt or terminal window and type `dot -version` to verify that Graphviz is correctly installed and accessible from the command line.
4. **Restart Your IDE or Terminal:** If you had your IDE or terminal open during the installation, restart it to ensure the changes to the PATH variable take effect.
