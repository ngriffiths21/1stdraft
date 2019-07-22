# 1stdraft

A tool that allows you to write a complete draft at the command line without losing focus. It hides all but the last typed character, preventing you from editing or re-reading as you write.

## Usage

1stdraft runs in a Bash shell.

### Install

Download the script, update permissions and `PATH`:
```bash
mkdir ~/.1stdraft && \
curl https://raw.githubusercontent.com/ngriffiths21/1stdraft/master/1stdraft > ~/.1stdraft/1stdraft && \
chmod a+x ~/.1stdraft/1stdraft && \
echo 'export PATH="~/.1stdraft/:$PATH"' >> ~/.bash_profile
```
or if you have a user-specific `bin`:
```bash
curl https://raw.githubusercontent.com/ngriffiths21/1stdraft/master/1stdraft > ~/bin/1stdraft && \
chmod a+x ~/bin/1stdraft
```

### Start writing

```bash
1stdraft [filename]
```

The application will prompt for a filename at the end if none was provided.

## License

MIT