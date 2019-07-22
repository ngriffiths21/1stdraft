# 1stdraft

1stdraft allows you to write a complete draft without losing focus. It is a command-line tool that hides all but the last typed character, preventing you from editing or re-reading as you write.

## Usage

### Install

Download the Bash script and update `PATH`:
```bash
curl https://raw.githubusercontent.com/ngriffiths21/1stdraft/master/1stdraft > ~/.1stdraft/1stdraft
chmod a+x ~/.1stdraft/1stdraft
echo 'export PATH="~/.1stdraft/:$PATH"' >> ~/.bash_profile
```
or if you have a user-specific `bin`:
```bash
curl https://raw.githubusercontent.com/ngriffiths21/1stdraft/master/1stdraft > ~/bin/1stdraft
chmod a+x ~/bin/1stdraft
```

### Start writing

```bash
1stdraft [filename]
```

The application will prompt for a filename at the end if none was provided.

## License

MIT