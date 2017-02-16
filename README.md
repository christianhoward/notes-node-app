# notes-node-app
This is my notes-node application following [Andrew Mead](http://www.mead.io/)'s Complete Node.js Developer Course on Udemy. This repo is used purely for learning exercises and the course content should not be interpreted as something I've created on my own.

The notes app allows you to store notes into a .txt file through the command line using Node.js' File System and the Yargs and Lodash libraries.

## Commands
All of these commands can be passed using the command line interface. Navigate to the project directory and run `npm install` to install the dependencies.

### Add a note
To add a note, use the `add` command. Use `--title` or `-t` to set the title of the note and use `--body` or `-b` to set the body of the note.
`node app.js add -t="Some note" -b="Some text for my note"`

### List all notes
To read all notes, use the `list` command.
`node app.js list`

### Read a note
To read a note, use the `read` command. If the note exists, use `--title` or `-t` to pass in the title of the note you want to read.
`node app.js read -t="Some note"`

### Remove a note
To remove an existing note, use the `remove` command. If the note exists, use `--title` or `-t` to pass in the title of the note you want to remove.
`node app.js remove -t="Some note"`

### Help
If you have questions about what commands are available or how each command works, use the `--help` command.
`node app.js --help`
`node app.js read --help`
