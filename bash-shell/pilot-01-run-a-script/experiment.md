# **Run A Bash Shell Script**

## Just like a movie script that tells the actors what dialogues to say on what scene, programming tasks could be scripted so as to tell a computer what to do on what situations. When you write a movie script and record the scenes and play it, you have a movie. When you write a programming script and run it, you have a programming task that gets completed by a computer.

# **Experiment**

1. ### Create a folder named **"scripts"** inside your master project folder. Open "scripts" folder in visual code as shown in `vs-code/pilot-02`. 

2. ### Create a new file in **scripts** folder and name it "script.sh". What you just did was, you created a shell script file so that you could write your script. Shell script files are kinda like text files but instead of writing words and phrases, we write programming commands. Programming commands tell the computer what to do in the order that they appear in the shell script file. So if you wrote, "drive the car. put the key in. open the car door". The computer would start to do things in the order that the command appears in the shell script. Of course, the example car driving command that you just wrote would fail in real life but the point is, the computer always does what you tell it to do. 

3. ### Inside the "script.sh", write this command: `date` and save what you wrote.

4. ### Now open up the integrated terminal in visual code as in `vs-code/pilot-01`, type this command to execute the shell script that you just wrote: `bash script.sh`. There should be a space between bash and script.sh. You should get the current date when you execute the command. 

5. ### Rename "script.sh" to "noscript.sh". Follow `experiment-#4` again but this time the command should be `bash noscript.sh`. You should get the same results nonetheless. The point is, it doesn't matter what name you give to the script file. What you've written inside the script file and in what order the commands appear are what the computer cares about.  

6. ### You can directly enter commands into the integrated terminal instead of writing commands in a shell script file and execute it. It's usually a convenience thing whether you choose to run a script file or type commands directly into terminal. If you need to execute multiple lines commands, you would run a script file. But if you want to just execute a single line or so, you would type directly into the terminal. For instance, open up the integrated terminal as in `vs-code/pilot-01` and enter this command `whoami`. This command should output the username of your local computer. Type: `date` to get the current date. Type: `date -R` to get the current date and time in a different format. Type: `git --version` to see your Git's version. 