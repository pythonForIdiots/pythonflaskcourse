# pythonflaskcourse
Install python and flask and write a simple app on Mac using Terminal and Visual Code

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
1. Inside Visual Code open the terminal and enter following command to install virtualenv allowing your to run all dependicies and tools you need straight from the folder of your application: 
    ```console
    pip3 install virtualenv
    ```
2. configure virtualenv in your folder by running
    ```console
    virtualenv env
    ```
