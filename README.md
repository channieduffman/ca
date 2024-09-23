# ca

*ca* is a minimal, specialized file management tool used from the command line.

Its direct purpose is to facilitate in-class assignments. It attempts to prevent the user from making any serious mistakes (overriding files, say) but should not be considered robust. I intend to improve this script.

## Basic Usage

- Print usage: `ca -h`
- Create and edit a new .cpp file with ID 19: `ca -n 19 cpp`
- Compile and run the file with ID 7: `ca -m 7`
- Clean up the home directory (i.e., delete compiled test files): `ca -c`

## Options

- `-h`: print usage help to the console
- `-l`: list all files in the directory
- `-p`: print the contents of specified file; arguments: integer_id
- `-n`: create and edit a new file; arguments: integer_id, file_type
- `-e`: edit the specified file; arguments: integer_id
- `-d`: delete the specified file; arguments: integer_id
- `-m`: compile and run the specified file; arguments: integer_id
- `-c`: clean up the home directory
