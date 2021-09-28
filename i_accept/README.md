Chapter I

Instructions

To carry out this project, and, consequently, agree with the
content of the attached pdfs, just follow the instructions in that pdf.
The steps contained in this PDF will be essential for you to
deliver all basecamp projects.

After logging into your session at basecamp.42wolfsburg.de, open the terminal and
type:

$> cd ~/.ssh/
$> cat id_rsa.pub

•Take the ssh key that was displayed and copy. You must put it in your intranet
account.
•In your intranet profile, access https://profile.intra.42.fr/gitlab_users/new.
•Paste the ssh key into the field and send.

You will now be able to clone git repositories for your web development area.
After reading the pdf (in the project attachments on the intra),
follow the next steps to agree with them:

•Clone the project’s git repository in your development area.
•Within the project directory, create a new directory called accept.
•Within that last directory, download the attached file called accept.txt using the
tool wget. Don’t worry too much about it for now.
•And then push to your repository and set your project as finished.

$> git clone <URL OF YOUR REPOSITORY> <FOLDER NAME>
$> cd <FOLDER NAME>
$> mkdir accept
$> cd accept
$> wget <ATTACHMENT URL "accept.txt">
