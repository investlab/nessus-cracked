thanks a lot! 

This project is only for non -profit learning research. Do not use it for illegal purposes. If there is any infringement, please contact it in time to delete it


# Usage
`docker run -itd --name=ramisec_nessus -p 8834:8834 ramisec/nessus`
`docker exec -it ramisec_nessus /bin/bash /nessus/update.sh`

or (not check)
`docker pull heldocker233/nessus-awvs:v2`

# Account & Password

account: `admin`

Password: in container run: /opt/nessus/sbin/nessuscli chpasswd admin

