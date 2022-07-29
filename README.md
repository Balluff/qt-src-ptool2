# qt-src-ptool2

Repo für QT-Quellen

Archive splited into 90MB parts due to github filesize limit
UPDATE: GitHub Filesize Limit is 50MB

Command for splitting large files 

split -b 90M file.tar.xz "file.tar.xz.part"

Join parts together

cat home.tar.bz2.parta* >backup.tar.gz.joined
