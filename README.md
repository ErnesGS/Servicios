# Servicios

FTP mediante vsftpd.
Modificaciones al fichero de configuración vsftpd.conf:
<!-- Conexión anónima -->
- anonymous_enable=YES
- local_enable=YES
- write_enable=YES
- anon_upload_enable=YES
<!-- Enjaulamiento de usuarios -->
- chroot_local_user=YES
- local_root=/home/$USER/ftp
