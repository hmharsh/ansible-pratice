To start with 

k3d cluster create test
k run ubuntu --image=ubuntu -- sleep 10000
k exec -it ubuntu -- bash
apt-get udate
apt-get install git  ansible bash-completion vim


