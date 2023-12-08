Kod za virtual host:

    <VirtualHost *:80>
    ServerName test.local
    DocumentRoot "C:/xampp/htdocs/ParcijalniIspit"
    DirectoryIndex index.html
    <Directory "C:/xampp/htdocs/ParcijalniIspit">
        Options all
        AllowOverride All
        Require all granted
    </Directory>
    </VirtualHost>