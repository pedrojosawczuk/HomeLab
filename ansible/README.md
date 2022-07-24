<p align="center">
  <h1 align="center">HomeServer - Ansible
  <img alt="Windows 10" src="https://external-content.duckduckgo.com/ip3/docs.ansible.com.ico"/></h1>
  <h3 align="center">Trying to build my own local solutions for my home server. 👨‍💻</h3>
</p>

Command I use to run my ansible playbook

`ansible-playbook run.yml -i hosts --ask-become-pass`

`docker.yml`
`essential.yml`
`podman.yml`
`ssh.yml`

### Containers
<details>
  <summary>
    Deploy Homer
  </summary>
    image: 

`docker.io/b4bz/homer`
</details>

<details>
  <summary>
    Deploy Duplicati
  </summary>
image: 

`lscr.io/linuxserver/duplicati:2.0.6`
</details>

<details>
  <summary>
    Deploy Syncthing
  </summary>
image: 

`lscr.io/linuxserver/syncthing`
</details>
 
<details>
  <summary>
    Deploy Vaultwarden
  </summary>
image: 

`docker.io/vaultwarden/server`
</details>

#### Deploy Security
<details>
  <summary>
    Deploy Endlessh
  </summary>
image:

`lscr.io/linuxserver/endlessh`
</details>
