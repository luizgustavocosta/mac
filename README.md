# mac
Mac commands because I always forget :S

# Export 
```console
export JAVA_HOME=/Library/Java/JavaVirtualMachines/adoptopenjdk-11.jdk/Contents/Home
```

# Add to classpath
```console
export PATH=/Library/Java/JavaVirtualMachines/adoptopenjdk-11.jdk/Contents/Home/bin:"$PATH"
```


# See which Java you have
```console
/usr/libexec/java_home -V
``` 

# Export
```bash
export JAVA_HOME="/Library/Java/JavaVirtualMachines/<java_version>/Contents/Home"
```

# For ZSH
For this type do the following

1. Open the terminal on IntelliJ for instance
2. Type ```open ~/.zshrc``` 
3. This file has the reference to Bash Profile. *B*ourne *A*gain *Sh*ell
4. Open the file using the terminal ``open ~/.bash_profile``
5. Change the JAVA_HOME or other variable and save the file, closing the file is an option.
6. This is how the content looks like 
```bash
export M2_HOME=/usr/local/apache-maven-3.6.3
export M2=$M2_HOME/bin
export JAVA_HOME=/Library/Java/JavaVirtualMachines/adoptopenjdk-11.jdk/Contents/Home
export PATH=$M2:$JAVA_HOME:$PATH
```

Reference [freeCodeCamp](https://www.freecodecamp.org/news/how-to-configure-your-macos-terminal-with-zsh-like-a-pro-c0ab3f3c1156/)

[Stackoverflow](https://stackoverflow.com/questions/21964709/how-to-set-or-change-the-default-java-jdk-version-on-os-x)
