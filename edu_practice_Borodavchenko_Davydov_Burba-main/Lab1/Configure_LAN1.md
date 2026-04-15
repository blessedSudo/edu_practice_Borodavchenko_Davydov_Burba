
# Часть 1
## Шаг 1 - Схема сети
Создаём топологию сети, в которую входят 2 города
<img width="1947" height="760" alt="image" src="https://github.com/user-attachments/assets/b97ffbdf-ba91-46ad-8949-521aaada4637" />
*Рис.1 топология сети*

## Шаг 2 - Создание сообщения на роутерах
rus-msk-r1: 

<img width="631" height="75" alt="image" src="https://github.com/user-attachments/assets/c0fa5cb7-6e29-493f-8245-526574e5350b" />

*Рис.2 Настройка сообщения на первом роутере в Мск*

rus-msk-r2:

<img width="631" height="75" alt="image" src="https://github.com/user-attachments/assets/642a47e4-ee76-46f9-9a15-1679613ac40b" />

*Рис.3 Настройка сообщения на втором роутере в Мск*

rus-nsk-r1:

<img width="631" height="75" alt="image" src="https://github.com/user-attachments/assets/7976c42f-7e57-4ffe-a20c-441b6b4aa339" />

*Рис.4 Настройка сообщения на первом роутере в Нск*

## Шаг 3 - Переименовывание устройств
#### Таблица названий устройств
<table>
<tr>
<td>

<h3>Москва</h3>
<table>
<tr><th>Первичная</th><th>Измененная</th></tr>
<tr><td>server0</td><td>rus-msk-serv1</td></tr>
<tr><td>switch0</td><td>rus-msk-sw1</td></tr>
<tr><td>router0</td><td>rus-msk-r1</td></tr>
<tr><td>router1</td><td>rus-msk-r2</td></tr>
<tr><td>Multilayer switch1</td><td>rus-msk-multisw1</td></tr>
<tr><td>PC0</td><td>rus-msk-pc1</td></tr>
<tr><td>PC1</td><td>rus-msk-pc2</td></tr>
</table>

</td>
<td>

<h3>Новосибирск</h3>
<table>
<tr><th>Первичная</th><th>Измененная</th></tr>
<tr><td>router0</td><td>rus-nsk-r1</td></tr>
<tr><td>switch0</td><td>rus-nsk-sw1</td></tr>
<tr><td>switch1</td><td>rus-nsk-sw2</td></tr>
<tr><td>PC0</td><td>rus-nsk-pc1</td></tr>
<tr><td>PC1</td><td>rus-nsk-pc2</td></tr>
<tr><td>PC2</td><td>rus-nsk-pc3</td></tr>
<tr><td>PC3</td><td>rus-nsk-pc4</td></tr>
<tr><td>PC4</td><td>rus-nsk-pc5</td></tr>
<tr><td>PC5</td><td>rus-nsk-pc6</td></tr>
</table>

</td>
</tr>
</table>






