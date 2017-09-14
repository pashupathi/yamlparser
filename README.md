# yamlparser
Bash script to parse yaml file into structure that can be grouped and analyzed


How to use -
1. place the yaml.sh in your home dir
2. cd to the folder which contains the yml files
3. execute the command 
     $for i in $(find . -name '*.yml');  do  echo "In template file ${i} >>>>>>>>>>" >> report.txt;  ~/yaml.sh $i|grep "LoadBalancer"  >> report.txt;  done
