# System Users Management

1. Introduction

   This project aims to automate the management of local user accounts on remote hosts using Ansible playbooks. It includes tasks for creating multiple local users, adding them to specified groups, configuring SSH access with authorized keys, and granting sudo privileges without a password.

2. Technology Used

   - Ansible

3. Features

   - Feature 1: Create multiple local user accounts on remote hosts.
   - Feature 2: Configure SSH access with authorized keys for each user.
   - Feature 3: Grant sudo privileges to specified user groups without requiring a password.

4. Usage

   To use this project, follow these steps:
   - Step 1: Ensure Ansible is installed on your system.
   - Step 2: Configure the `ansible.cfg` file as needed.
   - Step 3: Update the `inventory` file with the IP addresses of your managed hosts.
   - Step 4: Create a file named `users_vars.yml` under the `vars` directory and define the list of users with their details as shown in the example provided.
   - Step 5: Place the public key files for each user in the `files` directory following the naming convention: `<username>.key.pub`.
   - Step 6: Run the playbook `users.yml` using the command: `ansible-playbook users.yml`.

5. Installation

   To install and set up this project, follow these steps:
   - Step 1: Clone the repository to your local machine.
   - Step 2: Ensure Ansible is installed on your system.
   - Step 3: Configure the `ansible.cfg` file according to your requirements.
   - Step 4: Update the `inventory` file with the IP addresses of your managed hosts.
   - Step 5: Follow the Usage instructions provided above.

