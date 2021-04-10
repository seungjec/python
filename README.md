# python
## This is test page

Conda doesn't have a way to set this, AFAIK, but you can easily accomplish it with some editing of .bashrc (or whatever the initialization file is for your shell). Simply add

conda activate kf
to the bottom of your .bashrc (e.g., echo "conda activate kf" >> ~/.bashrc). Also, you might as well disable the auto-activation of base:

conda config --set auto_activate_base false
