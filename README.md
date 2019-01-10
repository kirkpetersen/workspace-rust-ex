# workspace-rust-ex

This is an experiment in creating a "shell" or "workspace". I like working
in command-line shells, but bash is pretty old and crufty.

Also, having a shell work on a single computer is not very "cloud-like".
I'd prefer that the shell provide easy mechanisms for manipulating data
that lives in various places, and automatically storing data in places
where it can be retrieved from other computers.

Since I know AWS, I'm going to use various AWS resources.

I'm learning Rust, so that will be the language.

# Goals, tenets, etc

* It should be easy to manipulate, store, recall, organize, pipe data.
* Data should not be stored locally, at least for any period of time.
* Ideally, this code should be possible to run as a command line app or
  as a web service
* This should focus on interactive use cases, not shell scripting

# Misc

There is another library here: https://github.com/shaleh/rust-readline

# Use cases

This isn't the best set of use cases, but it is the use cases that I think
of when I think of using a UNIX command-line shell.

* Listing local files
* Looking at text files (head, tail, sort, uniq, grep, etc)
* Looking at local processes and kernel resources (ps, top, uptime, etc)
* Fetching files via scp or curl
* Manipulate data and store the results in intermediate files
* Temporarily storing data in files or in variables
* Install, update, configure, or remove applications
* Write short scripts to process data
