![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg) 

# **Email Cracker v[2.7]**

<!-- [Email Cracker v2.7](https://github.com/evilfeonix/EmailCracker/blob/main/banner.png) -->
![Email Cracker v2.7](banner.png) 


# **Email Cracker (***Educational Use Only***)**

**Email Cracker** is a Python-based project that simulate a password guessing (brute force or dictionary) attack based on email services.

 **Email Cracker** aimed to generates a list of password (**wordlist**) based on the victim's informatiom provided and attempt to crack the victim's email passwords.

Those password that this tool generate are 4 in minimum and 18 in maximum (length). The tool is designed for users to test the security of their own accounts or those they have explicit permission to test. 


> **Important: This tool should **only** be used on accounts that you own or have explicit written consent to test. Unauthorized use of this tool on accounts you do not own or have permission to test is illegal and unethical.**


> **Note that the creators of this tool are not responsible for any misuse or damage caused by its usage.**

## **Disclaimer**

This tool is intended **for educational purposes only** and should be used responsibly. By using this tool, you agree to comply with all applicable laws and regulations. Do not use this tool for illegal activities or without the explicit consent of the account holder.

## **Features**

- **Email Configuration**: This tool uses an easily configurable `config.ini` file where users can specify the email service provider's host and port.
- **Generate list of Passwords**: This tool generate a list of passwords also known as (**wordlist**), based on the information it collecated.
- **Password Cracking Simulation**: This tool simulates a password cracking process using common attack methods like dictionary or brute force.


> **IMPORTANT NOTE:** This tool requists some informations about the victims (*such as nickname, son name, pet name, phone number, year of birth*), in order to generate wordlist (passwords).

> **TIP:** If you're ask to enter victim's information that you dont know, just replace it with the one you know.

## **Prerequisites**

Before running **Email Cracker**, ensure you have the following:

- Python 3.x or above
- Required Python libraries (can be installed using `pip`)

## **Setup**
### **Clone the Repository**

```bash
git clone https://github.com/evilfeonix/EmailCracker.git
cd EmailCracker
```
## **Configure the Tool (config.ini)**

The tool requires the configuration of the `config.ini` file before use. The configuration file allows you to specify the email provider's host and port.

The default configuration in `config.ini` is set up for Gmail, but you can modify these settings to test other email providers (such as Yahoo, Outlook, etc.).

### **Example config.ini for Gmail:**

```ini
[SMTP]
host = smtp.gmail.com
port = 587
```

If you're testing with a different provider, replace the host and port with the appropriate values.

<!-- ## Install Dependencies

If you haven't already, you can install all the necessary Python dependencies: -->

## **Run the Tool**

After configuring the config.ini file, run the tool:  <!-- by passing in the target email address: -->
```bash
python3 cracker.py
```

## **Monitor the Cracking Process**

<!-- ![Email Cracker v2.7](https://github.com/evilfeonix/EmailCracker/blob/main/cracker.png) -->
![brute force attack](cracker.png)

The tool will log its attempts to find the correct password, simulating a password guessing attack (brute force or dictionary). If the password is found, it will be displayed in the output.

<!-- ![Email Cracker v2.7](https://github.com/evilfeonix/EmailCracker/blob/main/granted.png) -->
![password is found](granted.png)

### **Legal Disclaimer**

> By using this tool, you agree that you will not attempt to access email accounts without permission. Any unauthorized use of this tool is illegal and may result in criminal charges.

### **Surport Us**

Support us by liking, forking, and sharing our repo and also follow us on [github.com](https://github.com/evilfeonix), [instagram.com](https://instagram.com/evilfeonix), and [youtub.com](https://youtub.com/evilfeonix) for latest hacking tips and tricks.

### **License**

This project is licensed under the GPL License - see the LICENSE file for details.
