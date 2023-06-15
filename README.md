# test4
#!/bin/bash 

while :             # or while true
do

read -p "Do you like Marvel movies? [yes/no]: " marvel


case $marvel in
  [Yy] | [yY][Ee][sS]) echo "cool";;
  [Nn] | [Nn][oO]) echo "ok";;
  exit | done)  exit    ;;  
   *) echo "Just give your opnion" ;;
esac

done
