# Custom `motd`
Motd are used to display message after ssh login or before tty login.

## To use the `motd`
- Open the `THEME_FOLDER/etc/motd.d` in this repository.
- Copy the file.
- Paste inside the `/etc/motd.d` folder on your machine.

> The motd is dynamic for only few linux based operating system.

If motd is static, use the `/etc/profile.d/` folder. Add the `.sh` at the last in the filename. 