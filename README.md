# apt-get-update-files-not-found
If some of the aplications you have dowloaded doesn't install properly or is of improper version, then u will see "files not found" when u run the command.
```
sudo apt-get update
```

## Solution

To remove this error
Follow the steps..

* ### Run the update command.
```
sudo apt-get update
```

* ## See the files which were causing errors now we are supposed remove them.
So,now go the /etc/apt/sources.list.d with this command.

```
cd /etc/apt/sources.list.d/
```

* ## Now list the files inside this folder using this command.
```
ls
```

* ## Remove the list which is causing error using this.
```
sudo rm -rf <list_name>
```

#### Tip: Use "sudo" with "rm" carefully it can goof up your installs. :)

