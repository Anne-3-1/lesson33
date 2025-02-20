# lesson33
Анна

1-настройки конкретного компьютера необходимо точно знать марки и параметры его устройств. Определить эти данные можно с помощью специального программного обеспечения

2-Изучение функционального устройства компьютера более полезно, так как оно позволяет понять, как различные элементы системы взаимодействуют друг с другом, а не только их физические аспекты

3-Устройства компьютера обмениваются данными через шину — совокупность проводников, по которым передаются сигналы между процессором, памятью и периферийными устройствами

4-Шина — это электрическая схема, состоящая из проводников, по которым передаются данные, адреса и управляющие сигналы. Шина позволяет сократить количество проводов, необходимых для соединения всех устройств, упрощая дизайн и уменьшая стоимость

5-Шина состоит из трех основных частей:

- Данные: передает информацию между устройствам
  
- Адрес: определяет, к какому устройству или памяти направляются данные
  
- Управление: передает управляющие сигналы, которые координируют действия устройств

6-Магистрально-модульная архитектура — это схема, в которой компоненты компьютера соединяются через общую шину. Главное достоинство — модульность, позволяющая легко добавлять или заменять устройства

7-Принцип открытой архитектуры подразумевает, что архитектура системы должна быть стандартной и доступной для расширения, что позволяет разрабатывать совместимые компоненты сторонним производителям

8-Считывание данных происходит следующим образом:

1. Процессор отправляет адрес нужной ячейки по адресу шины.
   
2. Контроллер памяти принимает адрес и перемещает соответствующее содержимое в буфер.
   
3. Данные передаются обратно через шину в процессор.

9-Контроллер — это устройство, которое управляет передачей данных между процессором и внешними устройствами. Он необходим для обеспечения корректного взаимодействия и оптимизации скорости обмена

10-Контроллеры позволяют выполнять операции параллельно, разгружая процессор от управления устройствами и увеличивая общую скорость обработки данных

11-В классической архитектуре существует отдельная связь между каждым устройством, что может привести к перегрузке шины. В магистрально-модульной архитектуре наиболее перегруженный блок — это шина данных, так как она используется всеми устройствами одновременно

12-Несколько шин используются для повышения пропускной способности и уменьшения задержек, позволяя одновременно обмениваться данными нескольким устройствам

13-Для успешного присоединения требуется: 

- Соответствующий интерфейс для подключения устройства
  
- Совместимость с драйверами
  
- Возможность системы распознать устройство при запуске

14-ПДП расшифровывается как Прямой Доступ к Памяти. Это метод, позволяющий устройству обмениваться данными с оперативной памятью без участия процессора

15-В режиме ПДП контроллер передачи данных самостоятельно управляет процессом переписывания данных между памятью и устройствами, освобождая процессор для выполнения других задач

16-Основные режимы обмена:

- Синхронный: операции выполняются с жесткой синхронизацией
  
- Асинхронный: нет строгой привязки к времени, данные могут передаваться, когда это удобно
  
- Прерывание: устройство отправляет сигнал, когда готово передать данные

17-Асинхронный режим является наиболее подходящим для клавиатуры, так как она генерирует ввод по мере нажатия клавиш

18-Для обмена данными с жёстким диском лучше использовать ПДП, так как это позволяет значительно ускорить передачу данных, освобождая процессор

19-Принципы обработки прерываний применяются в операционных системах для управления аппаратными событиями. Примеры включают обработку нажатий клавиш, сигналов от сетевых интерфейсов или поступление данных от жесткого диска
