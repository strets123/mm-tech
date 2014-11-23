mm-tech
=======

Installation of local rbenv

  git clone https://github.com/sstephenson/rbenv.git ~/.rbenv
  echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bashrc
  echo 'eval "$(rbenv init -)"' >> ~/.bashrc
  git clone https://github.com/sstephenson/ruby-build.git ~/.rbenv/plugins/ruby-build
  rbenv install -l
  rbenv install 2.0.0-p598
  
