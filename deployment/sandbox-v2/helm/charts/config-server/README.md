Config server Helm chart assumes that git repo with properties exists and is mounted on pvHostName. So this Helm works only in combination with Ansible scripts that first create the folder repoUri on pvHostName and then checks-in all property files over there.


