 sudo nano  /var/www/devops-hackathon-de03-pthung/nginx/pthung-k24cntt2.conf
34  git add .
35  git commit -m " commit file readme vaf html "
36  git push origin main
37  cd
38  sudo nano /var/www/devops-hackathon-de03-pthung/nginx/pthung-k24cntt2.conf
39  cd /var/www/devops-hackathon-de03-pthung
40  git add .
41  git commit -m "commit file conf"
42  git push origin main
43  cd
44  sudo ln -s /var/www/devops-hackathon-de03-pthung/pthung-k24cntt2/nginx/pthung-k24cntt2.conf /etc/nginx/sites-available/
45  sudo ln -s /etc/nginx/sites-available/pthung-k24cntt2.conf /etc/nginx/sites-enabled/
46  sudo ufw default deny incoming
47  sudo ufw allow 22/tcp
48  sudo ufw allow 8080/tcp
49  sudo ufw allow "Nginx Full"
50  sudo ufw enable
51  sudo ufw status verbose
52  sudo nginx -t
53  sudo systemctl restart nginx
54  sudo nano /var/www/devops-hackathon-de03-pthung/pthung-k24cntt2/nginx/pthung-k24cntt2.conf
55  sudo nano  /var/www/devops-hackathon-de03-pthung/nginx/pthung-k24cntt2.conf
56  sudo nginx -t
57  sudo nano  /var/www/devops-hackathon-de03-pthung/nginx/pthung-k24cntt2.conf
58  sudo nginx -t
59  sudo nano  /var/www/devops-hackathon-de03-pthung/nginx/pthung-k24cntt2.conf
60  sudo nginx -t
61  history
pthung-k24cntt2@lab#Devops hackathon de003 QUản lý công việc ( task)

##1. thông tin sinh viên 

Phạm Tiến Hưng | 242 | CNTT2 | pthung-k24cntt2 | https://github.com/PHAMTIENHUNG772006/PhamTienHung_K24_CNTT2_IT209_De03.git | 8080

2. Môi trường hệ điều hành
Linux | 24.04 | | https://github.com/PHAMTIENHUNG772006/PhamTienHung_K24_CNTT2_IT209_De03.git | Vps

3 cấu trúc dự án 

 src/ 
    index.html
nginx/
    pthung-k24cntt2.conf
screenshort/
  
/gitiginore

README.md
