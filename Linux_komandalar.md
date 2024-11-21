# 50 ta eng muhim Linux komandasi

1. ls
```shell
# Fayllar va papkalarni ro'yxatlash.
ls
ls -la  # Barcha fayllarni (yashirinlarini ham) ko'rsatish
```
2. cd
```shell
# Katalogni o'zgartirish.
cd /home/user
cd ..  # Bir darajaga yuqoriga qaytish
```
3. pwd
```shell
# Joriy katalogni ko'rsatish.
pwd
```
4. mkdir
```shell
# Yangi katalog yaratish.
mkdir new_folder
mkdir -p dir1/dir2  # Ichma-ich kataloglar yaratish
```
5. rmdir
```shell
# Bo'sh katalogni o'chirish.
rmdir empty_folder
```
6. rm
```shell
# Fayllar va kataloglarni o'chirish.
rm file.txt
rm -rf folder  # Papkani va uning ichidagilarni o'chirish
```
7. cp
```shell
# Fayllarni yoki kataloglarni nusxalash.
cp file1.txt file2.txt
cp -r folder1 folder2  # Papkani nusxalash
```
8. mv
```shell
# Fayllarni yoki kataloglarni ko'chirish/yangi nomlash.
mv file.txt new_file.txt
mv file.txt /home/user/destination/
```
9. touch
```shell
# Bo'sh fayl yaratish yoki fayl vaqtini yangilash.
touch newfile.txt
```
10. cat
```shell
# Fayl mazmunini ko'rish.
cat file.txt
```
11. less
```shell
# Katta fayllarni sahifalab ko'rish.
less file.txt
```
12. more
```shell
# Fayl mazmunini sahifalab ko'rish (less ga o'xshash).
more file.txt
```
13. head
```shell
# Faylning birinchi qatorlarini ko'rish.
head -n 10 file.txt
```
14. tail
```shell
# Faylning oxirgi qatorlarini ko'rish.
tail -n 10 file.txt
tail -f log.txt  # Fayl o'zgarishini real vaqt rejimida ko'rish
```
15. find
```shell
# Fayllarni yoki kataloglarni qidirish.
find /home/user -name "file.txt"
```
16. grep
```shell
# Matn ichidan qidiruv.
grep "word" file.txt
grep -r "text" /path/to/directory/
```
17. chmod
```shell
# Fayl huquqlarini o'zgartirish.
chmod 755 file.txt
chmod +x script.sh  # Faylni bajariladigan qilish
```
18. chown
```shell
# Fayl egasini o'zgartirish.
chown user:group file.txt
```
19. df
```shell
# Disk bo'sh joyini ko'rish.
df -h
```
20. du
```shell
# Diskdagi fayllar hajmini ko'rish.
du -sh folder/
```
21. ps
```shell
# Joriy jarayonlarni ko'rsatish.
ps aux
```
22. top
```shell
# Tizim yuklanishini real vaqt rejimida kuzatish.
top
```
23. htop
```shell
# top ning qulayroq versiyasi
htop
```
24. kill
```shell
# Jarayonni to'xtatish.
kill PID
kill -9 PID  # Majburiy to'xtatish
```
25. ping
```shell
# Tarmoq ulanishini tekshirish
ping google.com
```
26. wget
```shell
# Fayllarni internetdan yuklash.
wget https://example.com/file.zip
```
27. curl
```shell
# URL orqali ma'lumot olish
curl https://example.com
```
28. scp
```shell
# Masofaviy serverga/nusxalash.
scp file.txt user@remote:/path/to/destination
```
29. rsync
```shell
# Fayllarni samarali nusxalash.
rsync -av file.txt /path/to/destination
```
30. tar
```shell
# Arxivlash yoki arxivni chiqarish.
tar -cvf archive.tar folder/
tar -xvf archive.tar
```
31. zip va unzip
```shell
# Fayllarni siqish va chiqarish.
zip archive.zip file.txt
unzip archive.zip
```
32. ssh
```shell
# Masofaviy serverga ulanish
ssh user@remote_host # IP address
```
33. history
```shell
# Oldingi yozilgan buyruqlarni ko'rish.
history
```
34. alias
```shell
# Qisqa buyruqlar yaratish
alias ll='ls -la'
```
35. nano
```shell
# Matn muharriri.
nano file.txt
```
36. vim
````shell
# Kuchli matn muharriri.
vim file.txt
````
37. awk
```shell
# Matnlarni qayta ishlash vositasi.
awk '{print $1}' file.txt
```
38. sed
```shell
# Matnlarni qidirish va o'zgartirish
sed 's/old/new/g' file.txt
```
39. whoami
```shell
# Joriy foydalanuvchini ko'rish
whoami
```
40. hostname
```shell
# Tizim nomini ko'rish yoki o'zgartirish
hostname
```
41. uptime
```shell
# Tizimning qancha vaqtdan beri ishlayotganini ko'rsatadi.
uptime
```
42. free
```shell
# RAM bo'sh joyini ko'rish.
free -h
```
43. reboot
```shell
# Tizimni qayta yuklashsudo reboot
sudo reboot
```
44. shutdown
```shell
# Tizimni o'chirish.
sudo shutdown now
```
45. adduser
```shell
# Yangi foydalanuvchi qo'shish
sudo adduser new_user
```
46. usermod
```shell
# Foydalanuvchi huquqlarini o'zgartirish.
sudo usermod -aG sudo user
```
47. passwd
```shell
# Parolni o'zgartirish
passwd
```
48. mount va umount
```shell
# Diskni ulash va ajratish.
sudo mount /dev/sdb1 /mnt
sudo umount /mnt
```
49. chmod
```shell
# Fayl yoki katalog huquqlarini o'zgartirish.
chmod 644 file.txt
```
50. env
```shell
# Tizimdagi o'zgaruvchilarni ko'rsatish.
env
```
## Barcha mavjud komandalarni ko'rish:

```shell
# Siz tizimingizda mavjud barcha komandalarni quyidagi buyruq orqali ko'rishingiz mumkin:
compgen -c | wc -l
```
