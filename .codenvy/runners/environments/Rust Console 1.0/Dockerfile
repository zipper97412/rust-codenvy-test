FROM jimmycuadra/rust

ENV CODENVY_APP_BIND_DIR /home/user/application/src
VOLUME ["/home/user/application/src"]
WORKDIR /home/user/application/src

# 1. Get dependencies from source code of application
# 2. Start application
CMD cargo run