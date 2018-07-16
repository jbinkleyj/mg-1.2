# # mg-1.2
#   301  history | grep tar
#   302  tar -xvf mg-1.2.tar.gz 
#   303  cd mg-1.2
#   304  ls
#   305  ls -alt
#   306  git init
#   307  echo "# mg-1.2" >> README.md
#   308  git ad README.md
#   309  git add README.md
#   310  it commit -m "first commit"
#   311  git remote add origin git@github.com:jbinkleyj/mg-1.2.git
#   312  git push -u origin master
#   313  ls .git
#   314  more .git/config
#   315  git push  origin master
#   316  history
#   317  git commit -m "first commit"
#   318  git push -u origin master
#   319  history | tail -20
#   320  history | tail -20 >> README.md
#   319  history | tail -20
#   320  history | tail -20 >> README.md
#   321  git commit -m "readm commit"
#   322  git add .
#   323  git commit -m "readm commit"
#   324  git push -u origin master
#   325  git push  origin master
#   326  ls -alt
#   327  ls -al ~/.ssh
#   328  ls -al ~/.ssh/known_hosts
#   329  more ~/.ssh/known_hosts
#   330  ssh-keygen -t rsa -b 4096 -C "jbinkley@hargray.com"
#   331  eval "$(ssh-agent -s)"
#   332  ssh-add ~/.ssh/id_rsa
#   333  sudo apt-get install xclip
#   334  xclip -sel clip < ~/.ssh/id_rsa.pub
#   335  git push  origin master
#   336  git add .
#   337  git commit -m "ssh commit"
#   338  history | tail -20 >> README.md
