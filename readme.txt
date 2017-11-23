git clone --depth 1 --recurse-submodules https://github.com/grpc/grpc.git
find . -type d -name ".git"       -exec rm -f {} \;

# forked on 2017.11.23
