# GoamaAIServer
GoamaAI Cracked by SkiderKiller,Lol

# Easy to use
To upload the GoamaAIServer program to a Linux server, you need to grant the program permission to run (I believe you all will). After completing the above steps, enter ./GoamaAIServer command can be run.

# Nginx config
location / {
        client_max_body_size  64m;
        proxy_http_version 1.1;
        proxy_pass http://localhost:54188;  # Please modify your port according to the actual situation
        proxy_set_header Host $host;
        proxy_set_header X-Forwarded-For $remote_addr;
        proxy_cache_bypass $http_upgrade;
        proxy_set_header Accept-Encoding gzip;
        proxy_read_timeout 300s;
    }

# Bind Domain
ai.luren.best

# What is in the Client folder?
It is the AI system that we removed all hidden piles and replaced Domain.
