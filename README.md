# Minetest Management Console (1.12.0)
Allows you to manage your Minetest server with a text based GUI -  Official support sites: [Official Github Repo](https://github.com/fstltna/MinetestManagementConsole) - [Official Forum](https://minecity.online/index.php/forum/management-console)

---

You will need to run cpan and install these modules:

- cpan -i UI::Dialog
- cpan -i Term::ReadKey
- cpan -i Term::ANSIScreen
- cpan -i POSIX
- cpan -i Number::Bytes::Human

Run "mmc". If you need to change any settings after this, edit "~/.mmcrc" and make the desired changes. This can be done within mmc itself.

You also need to have my Minetest Startup Script and Minetest Backup Script installed.

I then suggest you add this directory (MinetestManagementConsole) into your path, so that you can just run "git pull" to upgrade to the latest version of mmc as updates come out.
