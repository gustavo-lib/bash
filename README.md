# bash

echo "Yesterday=$(date -d "$today 1 day ago" +%A), Tomorrow=$(date -d "$today 1 day" +%A)."
#OneDayAgo=(date +"%Y_%m_%d" --date=" 1 days ago")
Y=`date +'%Y'`
M=`date +'%m'`
D=`date +'%d'`
today=$Y-$M-1
prueba= date +"%Y-%m-%d"
prueba2= date "+%d-%m-%C%y %H:%M:%S" -d "19 Jan 2017 00:05:01"
prueba3= date '+%Y/%m/%d %H:%M:%S'
