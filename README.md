# Настройка и проверка базовой работы протокола OSPFv2 для одной области.
## Настройте адреса интерфейса и базового OSPFv2 на каждом маршрутизаторе.
![](https://github.com/iGORnetwork/Lab___Configure_Single_Area_OSPFv2/blob/main/Screenshot_1.png)
![](https://github.com/iGORnetwork/Lab___Configure_Single_Area_OSPFv2/blob/main/imeg/Screenshot_2.png)
# Настраиваем статический идефикатор, включим OSPF на интерфейсах и помещаем в рабочую область 0. Убедимся, что OSPF работает между маршрутизаторами. R2 стал DR т.к id R2 больше чем у R1. Проверим доступность R2 Loopback 1 из R1
![](https://github.com/iGORnetwork/Lab___Configure_Single_Area_OSPFv2/blob/main/imeg/Screenshot_5.png)
![](https://github.com/iGORnetwork/Lab___Configure_Single_Area_OSPFv2/blob/main/imeg/Screenshot_6.png)
# Реализация различных оптимизаций на каждом маршрутизаторе.
## Настроем приоритет на R1 и изменим Hello, Dead интервалы.
![](https://github.com/iGORnetwork/Lab___Configure_Single_Area_OSPFv2/blob/main/imeg/Screenshot_4.png)
![](https://github.com/iGORnetwork/Lab___Configure_Single_Area_OSPFv2/blob/main/imeg/Screenshot_8.png)
# На R1 настроем статический маршрут по умолчанию. Затем распространите маршрут по умолчанию в OSPF. 
![](https://github.com/iGORnetwork/Lab___Configure_Single_Area_OSPFv2/blob/main/imeg/Screenshot_7.png)
# Добавим конфигурацию, необходимую для OSPF для обработки R2 Loopback 1 как сети точка-точка. R2 добавим конфигурацию, необходимую для предотвращения отправки объявлений OSPF в сеть Loopback 1.

