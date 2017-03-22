# Create you accounts

1. If you don't have an account on https://github.com/, create one.

2. If you don't have an account on https://www.heroku.com/, create one.

# Prepare the environment

## For Windows

1. Install Atom

  https://github.com/atom/atom/releases/download/v1.15.0/AtomSetup.exe

2. Install VirtualBox

  http://download.virtualbox.org/virtualbox/5.1.18/VirtualBox-5.1.18-114002-Win.exe

3. Install Vagrant

  https://releases.hashicorp.com/vagrant/1.9.3/vagrant_1.9.3.msi

4. Download following package and unpack it in your Desktop

  https://github.com/marekciupak/ruby-on-rails-starter/archive/master.zip

5. Download Cmder and unpack it in your Desktop

  https://github.com/cmderdev/cmder/releases/download/v1.3.2/cmder_mini.zip

6. Run Cmder and execute following commands

  `cd %UserProfile%\Desktop\`

  `vagrant up`

  `vagrant ssh -c 'cd /vagrant/sample-app && bundle exec rails db:create && bundle exec rails db:migrate && bundle exec rails server --binding=0.0.0.0'`

  Open in the browser: http://192.168.33.10:3000/. You should see "Yay! You’re on Rails!".

  Stop the server by pressing Ctrl+C in Cmder window.

  `vagrant halt`

# Homework

http://tryruby.org/
