choco install chocolatey.server

choco source add -n=server -s="http://10.0.2.15/chocolatey" -u=choco -p=rocks

Executar script:
https://chocolatey.org/docs/how-to-setup-internal-package-repository


Push dos pacotes
choco push --source "'http://10.0.2.15/chocolatey'" -k="'chocolateyrocks'" --force
