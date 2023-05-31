# SI_2023_lab2_202025
Ивана Милевска, бр. на индекс 202025 ИМБ

`Control Flow Graph`

![Screenshot (308)](https://github.com/milevska2/SI_2023_lab2_202025/assets/129631492/c104abf5-76cb-4329-96ed-c502a3131367)

<b>Цикломатска комплексност</b> P=2+1 Цикломатската комплексност е 3 Ја искористив формулата за предикатни јазли P+1.

`Објаснување на напишаните unit tests`

Tест случаеви кои поминуваат низ сите патеки се следниве:" " , " " , " " " " , "ivana" , ivana@googlecom "ivana","#haker123","ivana@google.com  Unit тестовите ми се подетални и тоа се следниве:

  1. User user=null;
  2. User user = new User(null, "password", "email@example.com");
  3. User user = new User("username", "password", "email@example.com"); List allUsers = new ArrayList<>(); allUsers.add(new User("another", "anotherPassword", "email@example.com"));  
  4. User user = new User("username", "password", "email@example.com"); List allUsers = new ArrayList<>();
  5. User user = new User("username", "pass", "email@example.com"); List allUsers = new ArrayList<>();
  6. User user = new User("username", "password!", "email@example.com"); List allUsers = new ArrayList<>();
  7. User user = new User("username", "!#password", "email@example.com"); List allUsers = new ArrayList<>();

