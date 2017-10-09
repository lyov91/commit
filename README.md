# commit
first commit
test
leva dev support
 SSH

git@github.com:lyov91/commit.git

We recommend every repository include a README, LICENSE, and .gitignore.
…or create a new repository on the command line

echo "# commit" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:lyov91/commit.git
git push -u origin master
…or push an existing repository from the command line

git remote add origin git@github.com:lyov91/commit.git
git push -u origin master
…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.


Import code



one two three
seven eight one eight three
thirteen fourteen fifteen

 sixteen seventeen eighteen seven
sixteen seventeen eighteen
        twenty seven
one 504 one
one 503 one
one     504     one
one     504 one
#comment UP
twentyseven
        #comment down
twenty1
twenty3
twenty5
twenty7
# Запуск сервера в режиме службы

listen=YES



# Работа в фоновом режиме

background=YES



# Имя pam сервиса для vsftpd

pam_service_name=vsftpd



# Входящие соединения контроллируются через tcp_wrappers

tcp_wrappers=YES



# Запрещает подключение анонимных пользователей

anonymous_enable=NO



# Каталог, куда будут попадать анонимные пользователи, если они разрешены

#anon_root=/ftp



# Разрешает вход для локальных пользователей

local_enable=YES



# Разрешены команды на запись и изменение

write_enable=YES



# Указывает исходящим с сервера соединениям использовать 20-й порт

connect_from_port_20=YES



# Логирование всех действий на сервере

xferlog_enable=YES



# Путь к лог-файлу

xferlog_file=/var/log/vsftpd.log



# Включение специальных ftp команд, некоторые клиенты без этого могут зависать

async_abor_enable=YES



# Локальные пользователи по-умолчанию не могут выходить за пределы своего домашнего каталога

chroot_local_user=YES



# Разрешить список пользователей, которые могут выходить за пределы домашнего каталога

chroot_list_enable=YES



# Список пользователей, которым разрешен выход из домашнего каталога

chroot_list_file=/etc/vsftpd/chroot_list



# Разрешить запись в корень chroot каталога пользователя

allow_writeable_chroot=YES



# Контроль доступа к серверу через отдельный список пользователей

userlist_enable=YES



# Файл со списками разрешенных к подключению пользователей

userlist_file=/etc/vsftpd/user_list



# Пользователь будет отклонен, если его нет в user_list

userlist_deny=NO



# Директория с настройками пользователей

user_config_dir=/etc/vsftpd/users



# Показывать файлы, начинающиеся с точки

force_dot_files=YES



# Маска прав доступа к создаваемым файлам

local_umask=022



# Порты для пассивного режима работы

pasv_min_port=49000

pasv_max_port=55000
