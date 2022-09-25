
# ** -- build check & 

# build

docker build -t u20zsh:20 -< dockerfile

# run

docker run --rm -it  u20zsh:20 


# shell ckeck

echo $1

# ubuntu version check

cat /etc/issue
