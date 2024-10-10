# Работа с git и bash
## 1.задание
1. touch bash1.txt
2. cd
3. pwd
4.1 cd BASH 
4.2 mkdir test1
5. cd test1
6. touch 1.txt 2.txt 3.txt
7. ls
8. cd 
9.1 cd BASH
9.2 mkdir test2
10. rmdir test2
11. rm test1/2.txt
12.1 mkdir test3
12.2 cd test3
12.3 touch 3.txt 4.txt
13.1 cd ..
13.2 rm -rf test3
14. mkdir test4
15. cp test1/1.txt test1/3.txt test4
16.1 cd test4
16.2 echo line > 1.txt
16.3 echo line >> 1.txt
16.4 echo line >> 1.txt
17. cat 1.txt
18.1 echo line > 3.txt 
18.2 echo line >> 3.txt
18.3 echo line >> 3.txt
19. cat 1.txt 3.txt
20. nano 1.txt
## 2.задание
1. touch bash2.txt
2. cd
3.1 cd BASH
3.2 mkdir test3
4.1 cd test3
4.2 touch 4.txt 5.txt 6.txt
4.3 nano 4.txt
4.4 nano 5.txt
4.5 nano 6.txt
5. grep -i "row2" 5.txt
6. grep -R "row".
7. grep -c "row" 6.txt
8. find ./test3 -name "5.txt"
9. find . -name "5.txt" -type f -exec rm -f {} +
10.1 cd test3
10.2 echo test >> 4.txt
11. echo fail > 4.txt
12. echo test >> 4.txt
13. ps aux
14. kill 666
15. ping rusau.net
16. ping -c 5 rusau.net
17. curl -X GET https://petstore.swagger.io/v2/pet/findByStatus?status=pending
18. curl -X 'POST' \
  'https://petstore.swagger.io/v2/user' \
  -H 'accept: application/json' \
  -H 'Content-Type: application/json' \
  -d '{
  "id": 0,
  "username": "string",
  "firstName": "string",
  "lastName": "string",
  "email": "string",
  "password": "string",
  "phone": "string",
  "userStatus": 0
}'
