pkg update -y && pkg install proot-distro -y && proot-distro install debian && proot-distro login debian
apt update && apt upgrade -y && apt-get install sudo vim git -y
nvm install v<major_version_here>
curl -fsSL https://code-server.dev/install.sh | sh -s -- --dry-run
curl -fsSL https://code-server.dev/install.sh | sh
termux-change-repo
pkg update
pkg upgrade -y
pkg install -y \
  build-essential \
  binutils \
  pkg-config \
  python3 \
  nodejs-lts
npm config set python python3
node -v
code-server --auth none
npm update --global code-server --unsafe-perm
wget download_link
rm -rf /usr/local/go && tar -C /usr/local -xzf archive_name
sudo apt-get update
sudo apt-get install make build-essential libssl-dev zlib1g-dev \
  libbz2-dev libreadline-dev libsqlite3-dev wget curl llvm \
  libncursesw5-dev xz-utils tk-dev libxml2-dev libxmlsec1-dev libffi-dev liblzma-dev
curl -L https://github.com/pyenv/pyenv-installer/raw/master/bin/pyenv-installer | bash
export PYENV_ROOT="/root/.pyenv"
export PATH="/root/.pyenv/bin:$PATH"
eval "$(pyenv init --path)"
eval "$(pyenv virtualenv-init -)"
proot-distro login debian
proot-distro login debian -- code-server
