# sit
Testovacie repo pre SIT zadanie.

Tuto zverejnené súbory predpokladajú nainštalovaný základný systém s nainštalovanou základnou sadou programov.
Takisto na pracovnom stroji predpokladajú správne nastavený súbor /etc/ansible/hosts, kde testovací server je v skupine webservers.

V prvom kroku je potrebné stiahnuť si repozitár pomocou "git clone https://github.com/vmarek/sit/".
Následne sa presunúť do priešinka sit pomocou "cd sit".
Potom už stačí spustiť samotný playbook pomocou príkazu "ansible-playbook -kKvvv install.yml", prípadne pre menej výrečnú verziu "ansible-playbook -kK install.yml".
Po zadaní hesla užívateľa a hesla pre sudo zbehne celý proces.
