# Jetbrains IDE v2.5.6

0.	{Product} - продукт (clion, idea, и тд)
	{InstallDir} - путь до установленного продукта (CLion, IDEA, и тд) 

1. Копируем Jetbrains.jar to ${InstallDir}/lib

2. Редактируем файл "${Product}.vmoptions" (либо "${Product}${64}.vmoptions") в папке {InstallDir}/lib:
	
	2.1  Добавляем в конце файла (с новой строки): -javaagent:{InstallDir}/lib/Jetbrains.jar

3. Запускаем продукт.

4. Копируем в поле ключа:

ThisLicenseId-{
"licenseId":"ThisLicenseId",
"licenseeName":"Plamen Stilyianov",
"assigneeName":"",
"assigneeEmail":"plamen.stilyianov@yahoo.com",
"licenseRestriction":"For Plamen Stilyianov",
"checkConcurrentUse":false,
"products":[
{"code":"II","paidUpTo":"2019-12-31"},
{"code":"DM","paidUpTo":"2019-12-31"},
{"code":"AC","paidUpTo":"2019-12-31"},
{"code":"RS0","paidUpTo":"2019-12-31"},
{"code":"WS","paidUpTo":"2019-12-31"},
{"code":"DPN","paidUpTo":"2019-12-31"},
{"code":"RC","paidUpTo":"2019-12-31"},
{"code":"PS","paidUpTo":"2019-12-31"},
{"code":"DC","paidUpTo":"2019-12-31"},
{"code":"RM","paidUpTo":"2019-12-31"},
{"code":"CL","paidUpTo":"2019-12-31"},
{"code":"PC","paidUpTo":"2019-12-31"}
],
"hash":"2911276/0",
"gracePeriodDays":7,
"autoProlongated":false}

5. Готово.
