1. **Рожнов Андрей**

2. *+7 (775) 000 22 06, [ketron@mail.ru](ketron@mai.ru)*

3. Summary : с целью постоянного самообучение, есть желание пройти обучение и работать в крупной междунаромной IT компании, познакомиться и освоить самые передовые  и востребованные технологии в компьютерной сфере, стать компетентным специалистом с возможностью карьерного роста и высоким уровнем дохода, участвовать в крупных международных проектах: подключиться к уже имеющимся или заниматься созданием новых

4. Skills : 
* TuboPascal 
* Delfi
* assembler(x86, PIC)
* HTML&CSS&PHP&SQL(basic)
* Linux 

5. Примеры кода: вот пример теста скрипта нахождения ссылок на входящем URL :
```
<meta content="text/html; charset=utf-8">
<head>
<link rel="stylesheet" type="text/css" href="lf.css">
<link rel="shortcut icon" href="lf.png" type="image/png">
<body bgcolor="#fFffbF">
</head>
<pre>
<?php
function getmicrotime(){
   list($usec,$sec)=explode(" ",microtime());
return ((float)$usec+(float)$sec);
}
// function getLinks serch link on URL in $tu (**t**arget **U**RL) with preg_match_all function and regular expressions
function getlinks($tu){
$html=file_get_contents("$tu");
preg_match_all("/(?<=href\=\"|href\=\'|url\=\"|src\=\"|src\=\'|action\=\"|img\=\"|xmlns\=\"|profile=\"|url\(\")\S*?(?=\"|\"\>|\')/",$html, $matches1);
return $matches1;
}

$target_url = $_GET[url];
echo "<fieldset><legend>";
echo "<h7>URL = $_GET[url]</h7>";
echo "</legend>";

$path_parts = pathinfo($target_url);
echo "<br>function pathinfo() \n";
print_r ($path_parts);

//echo $path_parts['dirname'], "\n";
//echo $path_parts['basename'], "\n";
//echo $path_parts['extension'], "\n";

echo "function parse_url() \n";
print_r(parse_url($target_url));

$time_start = getmicrotime();

$matches= getlinks($_GET[url]);

print_r (array_unique($matches[0]));
echo "</fieldset>";
$time=getmicrotime()-$time_start;
echo "Все выполнено за $time секунды\n";

?>
</pre>
```
6. Опыт: 

* конец 90х - ведение страницы по музыкальной тематике на сайте провайдера SystemPRO,
* 2007-2009г - опытный проект, в рамках сообщества свободного программного обеспечения,  по созданию свободной распределенной поисковой P2P системы , основанной на релевантности поискового запроса, исключая "стену фильров", основанную на поисковом движке Shpinx, занимался разработкой тестового FrondEnd на PHP , тестирование скриптов, обработка тестовых данных
 
7. **1997-2001 КарГТУ**, электромеханический факультет, кафедра *АПП* автоматизации производственных процессов, присвоена квалификация - *Горный Инженер Электромеханник*; 

8. Уровень английского  - читаю со словарем, понимаю разговорную речь на знакомую тематику, осваивал при чтении документации по компьютерной тематике
