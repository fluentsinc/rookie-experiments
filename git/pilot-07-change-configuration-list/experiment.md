# **Change Configuration List**

## Git comes with a default configuration just like any software. For instance, if you had used whatsapp for the first time, you would see a default wallpaper which you can change according to your desire by going to the settings page. Kinda like that, we can also change Git's default configuration. 

# **Experiment**

1. ### To see the current configuration for your Git repository, execute this command: `git config --list` in your Git repository workspace terminal. The command lists out all the configuration that Git currently uses. We are going to change some of the options in that list to _**get a feel for them**_. 

2. ### If you look at the configuration list, you might see two phrases "user.name" and "user.email". For example, the configuration might look like `user.name=John Smith` and `user.email=johnsmith@outlook.com`. Note: the values "John Smith" and "johnsmith@outlook.com" might look different on your computer as this is just an example. 

3. ### Before you create your "initial commit" message for any Git repository, you need to customize these "user.name" and "user.email" options. You can customize your Git repository with `git config` command right after you've initiated your Git repositoy by executing `git init`. This is an important point, you need to `git init` before you can use `git config` command. If you had already executed `git init`, you don't need to do it twice. The workflow goes like this: 

- ### `git init` if you didn't initiate Git repository already 

- ### `git config --list` to see the current configuration list

- ### `git config user.name "your name"` if you want to change your author name in commit messages

- ### `git config user.email "your email"` if you want to change your email in commit messages. 

4. ### For every repository that you create, you need to change your commit name and email to match your name and email in Github. This requirement is not an absolute must since you could have different name and email but nonetheless it is highly recommended that you do so. 

5. ### It's worth reiterating a crucial point though it's already been explained above. The point is, you need to change your configuration(commit name and commit email) right after you've initialized the Git repository and before you create your "initial commit".  