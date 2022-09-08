
# CLI Weather-Report Script

The script contains a basic command curl, that fetch or request the data from wttr.in.
Created just for fun.



## Deployment

To deploy this project run

```bash
  bash weather
```
OR
```bash
  chmod +x weather
```
```bash
  ./weather 
```
(filename without any parameters or argument will give report for 1 day)




## Appendix

If you want to execute the file directly like a command you have to 1st create
create a bin folder in your home directory,move the file there. Type "source .profile"
(This command will run the .profile file and add the weather file to the PATH in environmet variable)


Note: some linux distro don't add the /home/user/bin directory to the PATH. In order to do that open the ".bashrc"
,locate the PATH variable or paste the following command in the file:
PATH="$HOME:$PATH"


## Documentation

[For more info visit the creator's repo]https://github.com/chubin/wttr.in

