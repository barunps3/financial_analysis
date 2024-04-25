# Installation

1. Install jupyterlab
    ```
    brew install jupyterlab
    ```

2. Install pyenv and pyenv virtual environment
    ```
    brew install pyenv
    brew install pyenv-virtualenv
    ```

3. Add the following to ~/.zshrc
    ```
    eval "$(pyenv init -)"
    eval "$(pyenv virtualenv-init -)"
    ```

4. Restart your terminal

5. Test if your pyenv is working fine with listing all the python versions you can download
    ```
    pyenv install --list
    ```

6. Install a python version 3.12.2
    ```
    pyenv install 3.12.2
    ```

7. Create python virtual environment in the project folder with the name of project directory
    ```
    cd to/your/project_dir
    pyenv virtualenv 3.12.2 project_dir_name
    ```

## Daily Running Procedure

8. Activate the virtual environment
    ```
    pyenv activate project_dir_name
    ```

9. Install required python libraries with
    ```
    pip install -r requirements.txt
    ```

10. Start the jupyter lab server in the project directory
    ```
    jupyter lab
    ```
