Connect to FTP: lftp ftp://miguelesquirol@miguelesquirol.com

Download a directory with lftp, the wonderful command-line FTP and SFTP client, this is what you want:

mirror <directory>


Here’s how you upload recursively:

mirror -R <directory>


To download a file from your FTP server to your workspace, use the pget command.

$ pget file_from_server.txt
Now I’ll see file_from_server.txt in my workspace.

To upload a file to your FTP server use the put command.

$ put file_from_workspace_file.txt
And now my file_from_workspace_file.txt is accessible on my FTP server. :muscle


Using Bootstrap 4 Boilerplate

More about this project at [BootstrapStarter](https://bootstrapstarter.com/bootstrap-templates/template-basic-bootstrap-html/).


gulp serve
gulp

