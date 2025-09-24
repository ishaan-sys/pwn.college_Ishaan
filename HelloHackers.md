# 1. Intro to Commands
The challenge prompted me to use my first command on the terminal,
The command `whoami` was introduced.
Second command 'hello' was introduced

## My Solve
**Flag:** `pwn.college{ILzbCQXKuFpv4XgA6z3k49DEi7l.QX3YjM1wiN0EzNzEzW}`

In the problem statement, it was provided that, using the 'hello' command would provide the flag
```
hacker@hello~intro-to-commands:~$ whoami
hacker
hacker@hello~intro-to-commands:~$ hello
Success! Here is your flag:
pwn.college{ILzbCQXKuFpv4XgA6z3k49DEi7l.QX3YjM1wiN0EzNzEzW}
```

## What I learned
I learnt to use my first command,
I learnt to use `whoami`,
The problem required me to run the command 'hello', which prompted me to the flag.
whoami command told me the name of the user.
I also learned that commands are case-sensitive in Linux.

## References
The problem statement was the reference used.
```
Here, the user executed the whoami command, which simply prints the username (hacker) to the terminal. When the command terminates, the shell once again displays the prompt, ready for the next command.

In this level, use the hello command to get the flag! One should also keep in mind that commands in Linux are case sensitive: hello is different from HELLO.
```


# 2. Intro to Arguments
The challenge prompted me to use arguments with commands,
The command "echo" was introduced.

## My solve
**Flag:** `pwn.college{kCUcH_iQE7LJUP9cJymvsZ3Ph9m.QX4YjM1wiN0EzNzEzW}`

I was provided in the problem statement that using the `hackers` argument with the `hello` command would prompt the flag.

```
hacker@hello~intro-to-arguments:~$ echo Hello
Hello
hacker@hello~intro-to-arguments:~$ hello hackers
Success! Here is your flag:
pwn.college{kCUcH_iQE7LJUP9cJymvsZ3Ph9m.QX4YjM1wiN0EzNzEzW}

```

## What I learned
In this case, the command was echo, and the argument was Hello. echo is a simple command that "echoes" all of its arguments back out onto the terminal.
A command with arguments, which is what we call additional data passed to the command. 

## References
The problem statement provided was used as the reference
```
Let's look at echo with multiple arguments:

hacker@dojo:~$ echo Hello Hackers!
Hello Hackers!
hacker@dojo:~$

In this case, the command was echo, and Hello and Hackers! were the two arguments to echo. Simple!

In this challenge, to get the flag, you must run the hello command (NOT the echo command) with a single argument of hackers. Try it now!
```


# 3. Command History
The challenge prompted me to check the command history. 

## My Solve
**Flag:** `pwn.college{sZFQFzhpSw7oMd0NlYmPNR7-Ow4.0lNzEzNxwiN0EzNzEzW}`

```
hacker@hello~command-history:~$ the flag is pwn.college{sZFQFzhpSw7oMd0NlYmPNR7-Ow4.0lNzEzNxwiN0EzNzEzW}
```

The flag was revealed after pressing `up arrow` key once.

## What I learned
I learned how to check command history,
By pressing, the `up` and `down` keys, I can jump back and forward between the already used commands.
In other challenges, the history will contain the log of the commands I've run, so if I need to run a similar command again, you I use the arrow keys to scroll through and find it!

## References
The problem statement was used as the reference
```
You're going to type a lot of commands, and typing everything from scratch can be annoying. Luckily, the shell saves a _history_ of every command you invoke.

You can scroll through those saved commands with the up/down arrow keys, and we'll practice that in this challenge. This challenge will inject the flag into your history. Bring up a terminal, hit the up arrow, and grab it! In other challenges, the history will contain the log of the commands you've run, so if you need to run a similar command again, you can use the arrow keys to scroll through and find it!
```
