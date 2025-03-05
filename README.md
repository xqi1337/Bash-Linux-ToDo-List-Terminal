# -Bash-Linux-ToDo-Liste-Terminal-

nano ~/todo_manager.sh


chmod +x ~/todo_manager.sh
 

nano ~/.bashrc
 

Jetzt ganz am Ende folgendes einfügen (damit ihr immer wenn ihr den Terminal öffnet ein überblick über die Todo Liste habt.

 

~/todo_manager.sh list
Speichern

 

source ~/.bashrc
 

jetzt könnt ihr entweder hinzufügen, auflisten oder löschen

 

Usage: ./todo_manager.sh {add|list|delete}
