# pythonflaskcourse
Install python and flask and write a simple app on Mac using Terminal and Visual Code. This guide can not be translated 1 to 1 to windows. 

## Step 1: Install the tools you need
1. Install Xcode from the App Store
2. Install python3 via Terminal
    ```console
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
    ```
    and 
    ```console
    brew install python
    ```
    You can afterwards check if you succeded by entering following code:
    ```console
    python3 --version
    ```
4. Download Visual Code
5. Create a new Folder in your personal macOS folder (eg "dev")
6. Open Visual Code and open that folder

## Step 2: Prepare your environment
1. Inside Visual Code open the terminal and enter following command to install [virtualenv](https://github.com/pypa/virtualenv) allowing your to run all dependicies and tools you need straight from the folder of your application (this allows you to share your app easily with other people): 
    ```console
    pip3 install virtualenv
    ```
2. configure virtualenv in your folder by running
    ```console
    virtualenv env
    ```
    "env" hereby stands for the folder used to place your environment, it can have any name but env is       common.
3. activate your environment with the following terminal command: 
    ```console
    source env/bin/activate
    ```
  
