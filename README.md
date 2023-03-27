The world's first most hackable single-board server should also be the most secure; ansible-zimaboard makes easy work of that. 

About Zimaboard: https://www.zimaboard.com

CasaOS: https://www.casaos.io

Quickstart
------------

- `pip install paramiko ansible`
- edit `production` file, to specify your host ip(s)
- `ssh-keygen -t ed25519 -f files/.ssh/id_ed25519`
- `ansible-playbook -i production -u casaos -k -c paramiko -C casaos_zimaboards.yml -K`

License
-------

MIT

Author Information
------------------

Paige Thompson <paige@paige.bio>
