# Automate_xe_configuration
A basic setup to automate xe os configuration.

The tasks folder contains a `main.yml` file which will execute some tasks among which:

1. Creation of a **extended test acl**.

## Usage

The code has been tested with ansible version **2.3.0.0**.

There are **three steps** required to run the ansible playbook:

 1. Clone the repository:
    
        git clone https://github.com/GaetanoCarlucci/automate_xe_configuration.git

 2. Create the file `invertory.yml` based on the sample file `invertory_sample.yml`. Set the variables according to your setup.

 3. Within the **directory** run the command:
 
        ansible-playbook -i inventory.yml site.yml -v




