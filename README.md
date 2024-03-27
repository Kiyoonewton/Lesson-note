# Lesson-note
General settings

#To set both Mkdir and Cd
1. vim ~/.zshrc
2. copy and paste this 
  mkcd() {
    mkdir -p "$1" && cd "$1"
  }
3. source ~/.zshrc
4. Then, you can use mkcd `new_directory` to create and change 
