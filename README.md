# Auto-Pass-Generator

## Description
This is a terminal run python application that enables a user to auto master , lock and generate passwords from the credential

## Built By Vincent-Juma

## User freedom

This will enable users to:

* Copy credentials to the clipboard
* Save login credentials
* To create an account with the credentials
* Generate new credentials for a new user


## Specifications
| Behaviour | Input | Output |
| :---------------- | :---------------: | ------------------: |
| Display codes for navigation | **In terminal: $./password_locker.py** | Welcome, choose an option: ca-Create Account, li-Log In, ex-Exit |
| Display prompt for creating an account | **Enter: ca** | Enter your first name, last name and password |
| Display prompt for login in | **Enter: li** | Enter your account name and password |
| Display codes for navigation | **Successful login** | Choose an option: cc - Create Credential, dc - Display Credentials, copy - Copy Credential, ex - exit |
| Display prompt for creating a credential | **Enter: cc** | Enter the site name, your username and password |
| Display a list of credentials | **Enter: dc** | Prints a list of saved credentials |
| Display prompt for which credential to copy | **Enter: copy** | Enter the site name of the credential you wish to copy. |
| Exit application | **Enter: ex** | Exit the current navigation stage |

## SetUp / Installation Requirements
### Prerequisites
* python3.9
* pip3
* pyperclip


### Cloning
* In your terminal:
        
        $ git clone https://github.com/Vincent-Juma/Auto-Pass-Generator.git
        $ cd Auto-Pass-Generator

## Running the Application
* To run the application, in your terminal:

        $ python3.9 password_locker.py
        
## Testing the Application
* To run the tests for the class file:

        $ python3.9 user_credentials_test.py
        
## Technologies Used
* Python3.9.0

## License
MIT &copy;2021`(Vincent-Juma)

