# Install Apache-Spark 2.4.4
## pre-setting
1. install Java8
- brew cask install homebrew/cask-versions/adoptopenjdk8

2. environment path setting
- vi ~/.bash_profile
- insert contexts below

---

JAVA_HOME=/Library/Java/JavaVirtualMachines/adoptopenjdk-8.jdk/Contents/Home

PATH=$PATH:$JAVA_HOME/bin

export JAVA_HOME

export PATH

---

## setup apache-spark
- brew install apache-spark

## reference
- https://bit.ly/2QKoyM6
