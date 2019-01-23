在ホームディレクトリ，
git clone https://github.com/torch/distro.git ~/torch --recursive
cd ~/torch
bash install-deps
./install.sh
对询问的回答为，yes

在Torch目录下，
source ~/.bashrc
然后可使用th指令

毎回source ~/.bashrcの必要性について，
Mac OS Xのデフォルトでは、HOMEに.bashrcを作成してもターミナル起動時に自動で読み込むようにはなっていないようなので、自動で読み込むように.bash_profileに記述すると良い模様。
.bash_profileに
source .bashrc
を記述
*
source /Users/shirui/.bashrc
更加稳妥，原模式以来打开bash窗口的位置。

关于版本问题：
libpng warning: 
Application built with libpng-1.4.12 but running with 1.6.36