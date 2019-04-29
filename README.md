# zipgit
Zip the files and directory structure within a range of git commits

## Instructions:
- Install file to `/usr/local/bin`
- then run `chmod +x /usr/local/bin/zipgit`

You should now be able to run `zipgit` and see the following:

```

=================
Welcome to ZipGit
=================

Instructions:
-------------
• First argument is required - Enter the name of the first commit (eg. 0793006ca94d0415a6345fd0f6efc22ca693d5ab)
• Second argument is required - Enter the name of the second commit (eg. 0afad0cebff0907bd1060d25bf0436c31375c8b5)
• Third argument is required - Enter the location and name of the zip file: ~/Desktop/myzip.zip

```

## Example usage:

- Get the first commit name (eg. fdec9cf6e0766d2e97b2bd71e04a5689ca457651, this will be a past commit)
- Get the second commit name (eg. 7061d78ca302aa7c999b98ac16765acf372abdaa, this could be the latest commit)

So all files that have changed between `fdec9c...` and `7061d7...` will be saved into the zip in the directory structure they should be.

**Next...**
- Decide where you're going to save it (eg. `~/Desktop/latest-commits-for-client-to-upload.zip`)
- Then run the script (note that commit name must be full name, it is shortened here for clarity `zipgit fdec9c... 7061d7... ~/Desktop/latest-commits-for-client-to-upload.zip`

**Result—once unzipped—should be something like:**

![Screenshot 2019-04-29 at 10 57 28](https://user-images.githubusercontent.com/811806/56889263-d0e29300-6a6d-11e9-82c5-00262cf4b100.png)




