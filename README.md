# chef

https://www.digitalocean.com/community/tutorials/how-to-use-roles-and-environments-in-chef-to-control-server-configurations


ruby -c default.rb
  
sudo chef-client -o recipe[spp-deploy::default]

knife bootstrap node02.example.com --ssh-user root --ssh-password 'vagrant' --sudo --use-sudo-password --node-name node02.example.com --run-list 'recipe[sample]’



  
