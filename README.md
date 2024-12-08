# Cómo inicializar el servidor
cd <your_bs_folder>
sudo apt-get update -y
sudo apt-get install -y python2.7-dev
chmod 777 bombsquad_server
chmod 777 config.py
chmod 777 bs_headless
pkill -f tmux
tmux
./bombsquad_server
