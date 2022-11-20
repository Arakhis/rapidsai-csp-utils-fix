# rapidsai-csp-utils

Colab folder contains
- update_gcc.sh: This updates Colab's gcc version form 7.4.0 to a RAPIDS compatible 9.3.0
- install_rapids.py: main bash script to properly install RAPIDS onto a Colab GPU instance.  This script will conda install RAPIDS.
- env-check.py: python script to check whether or not your GPU can run RAPIDS
- rapids-colab.sh: this now just displays the new template and instructions for users running the previous install method

################################################################################
  <h4>This error are fixed here</h4>
################################################################################
 Exception: Version mismatch: this is the 'cffi' package version 1.15.1, located in '/usr/local/lib/python3.7/dist-packages/cffi/api.pyc'.
    When we import the top-level '_cffi_backend' extension module, we get version 1.15.0, located in '/usr/local/lib/python3.7/dist-packages/_cffi_backend.x86_64-linux-gnu.so'.  
    The two versions should be equal; check your installation.
