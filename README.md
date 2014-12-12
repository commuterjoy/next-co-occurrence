
## Usage

export apikey=`cat ~/.ftapi`; node search 'people:"Xi Jinping"' | sort | uniq -c | sort -nr | head -n 20
