# graalvm-playground
GraalVM Playground

- wget https://github.com/graalvm/graalvm-ce-builds/releases/download/vm-21.0.0.2/graalvm-ce-java11-linux-amd64-21.0.0.2.tar.gz
- tar -xzf graalvm-ce-java11-linux-amd64-21.0.0.2.tar.gz

- sudo vim ~/.bashrc
- export PATH=/home/joellobo/dev/tools/graalvm-ce-java11-21.0.0.2/bin:$PATH


- mvn spring-boot:native-image
