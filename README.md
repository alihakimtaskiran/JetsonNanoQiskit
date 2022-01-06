# How to install qiskit on nvidia-jetson nano:
 After a clean installation, follow the following steps:
 1. sudo apt update
 2. sudo apt update
 3. sudo apt install python3.8 nano
 4. sudo apt install python3.8-pip
 5. python3.8 -m pip install --upgrade pip setuptools wheel
 6. cd Downloads
 7. wget https://files.pythonhosted.org/packages/2e/e4/4e6d17c0e23139977e3aa654de5ca095742280d3c9668d7341345207417a/qiskit-0.34.0.tar.gz
 8. python3.8 -m pip install qiskit-0.34.0.tar.gz
 9. wget https://files.pythonhosted.org/packages/9d/b8/13830a3bc96ff2da54cc100e75d9842879c70c3c22cfb1dc58620ffdbd89/qiskit_aer-0.10.1-cp38-cp38-manylinux_2_17_aarch64.manylinux2014_aarch64.whl
 10. python3.8 -m pip install qiskit_aer-0.10.1-cp38-cp38-manylinux_2_17_aarch64.manylinux2014_aarch64.whl
 11. nano "home/user-name/.bashrc" (then write <code>export LD_PRELOAD="~/.local/lib/python3.8/site-packages/qiskit_aer.libs/libgomp-d22c30c5.so.1.0.0"</code> in the end of the file)
 12. It's okay

## Run Qiskit

It can be only runned in python3.8 
