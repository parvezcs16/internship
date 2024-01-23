<p align="center"><img src="https://github.com/parvezcs16/internship/blob/main/image.png" width="200"></p>
<p align="center"><i>AI</i>FLO - by <i>AI</i>Factor</p>
 

Current version:

* AIFLO 0.2.24

## Easy installation 
### For Linux
#### Start with Anaconda, currently the version we have 2023.09-0 

1. curl -O https://repo.anaconda.com/archive/Anaconda3-2023.09-0-Linux-x86_64.sh

2. bash ~/Downloads/Anaconda3-2023.09-0-Linux-x86_64.sh

      2.1. Press Enter to review the license agreement. Then press and hold Enter to scroll.
  
      2.2. Enter yes to agree to the license agreement.
  
      2.3. Use Enter to accept the default install location, use CTRL+C to cancel the installation, or enter another file path to specify an alternate installation directory. If you accept the default   install location, the installer displays PREFIX=/home/<USER>/anaconda3 and continues the installation. It may take a few minutes to complete.

       
      Note
      2.4. Anaconda recommends you accept the default install location. Do not choose the path as /usr for the Anaconda/Miniconda installation.
      2.5. Anaconda recommends you enter “yes” to initialize Anaconda Distribution by running conda init.
      2.6. If you enter “no”, then conda will not modify your shell scripts at all. In order to initialize conda after the installation process is done, run the following commands:

#### Installing Postgres and setting up database for application

1.  sudo apt install postgresql

2.  sudo su - postgres

      2.1. psql

      2.2. create role <role-name> with login password '<your-password>'

      2.3. create database aiflo owner='<role-name>'
    
#### Installing Packages with conda virtual environment

1. cd aiflo-api
 
   For Linux

2. conda env create -f environment-linux.yml 

  For Windows

2. conda env create -f environment-win.yml

    
## Users registration

## Screenshots of public pages

### How To Write Templates

### API Documentation
Read in our wiki - https://github.com/kirilkirkov/Shopping-Cart-Solution-CodeIgniter/wiki/API

### Application Requirements
- Python 3.9.
