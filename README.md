# vimrc_ide

# Instalando no Debian Jessie

apt-get install libncurses5-dev \
                libgnome2-dev \
                libgnomeui-dev \
                libgtk2.0-dev \
                libatk1.0-dev \
                libbonoboui2-dev \
                libcairo2-dev \
                libx11-dev \
                libxpm-dev \
                libxt-dev \
                python-dev \
                python3-dev \
                ruby-dev \
                lua5.1 \
                lua5.1-dev \
                libperl-dev \
                git

git clone https://github.com/vim/vim.git

cd vim
./configure 
make install
