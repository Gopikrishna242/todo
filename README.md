

      git clone https://github.com/zelar-soft-todoapp/todo.git
    
      cd todo/
      
     apt update
      apt install nginx
      curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -
      apt install -y nodejs
     
     apt install npm
     cd /var/www/html/
     
     mv todo /var/www/html/
    cd /var/www/html/todo
    npm run build
     npm install
     cd /etc/nginx/
     cd sites-available/
     vi default
     nginx -t
     npm run build
     service nginx restart
![Screenshot (27)](https://user-images.githubusercontent.com/82368153/115695500-80158480-a37f-11eb-8f8b-33b69d8225bd.png)
