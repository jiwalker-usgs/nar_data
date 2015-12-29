This project requres the git large file storage extension. Before you clone, Install git lfs here:

https://git-lfs.github.com/

When retrieving large files from the server (ex: cloning, pulling), you will be prompted for credentials. You can supply a blank username and password. You only need to supply credentials if you wish to share modified large files.

To perform read-only checkouts of this project without being prompted for credentials run:

git config --global credential.helper 'store --file .anonymous-git-credentials'
