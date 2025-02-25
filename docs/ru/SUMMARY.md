# Содержание

* [Введение](README.md)
* [Глоссарий](glossary.md)
* [Безопасность](safety.md)
* [Сборка](assembly.md)
  * [Клевер 4.2](assemble_4_2.md)
  * [Клевер 4.2 WorldSkills](assemble_4_2_ws.md)
  * [Клевер 4.1](assemble_4_1.md)
  * [Клевер 4](assemble_4.md)
  * [Клевер 3](assemble_3.md)
  * [Клевер 2](assemble_2.md)
* [Настройка](setup.md)
  * [Калибровка датчиков](calibration.md)
  * [Настройка пульта](radio.md)
    * [Работа с FS-A8S](rc_flysky_a8s.md)
  * [Полетные режимы](modes.md)
  * [Настройка питания](power.md)
  * [Настройка failsafe](failsafe.md)
* [Ручной полет](flight.md)
  * [Упражнения](flight_exercises.md)
* [Работа с Raspberry Pi](raspberry.md)
  * [Образ для RPi](image.md)
  * [Подключение по Wi-Fi](wifi.md)
  * [Подключение к Pixracer](connection.md)
  * [QGroundControl по Wi-Fi](gcs_bridge.md)
  * [SSH-доступ](ssh.md)
  * [Командная строка](cli.md)
  * [Автоматическая проверка](selfcheck.md)
  * [Просмотр видеострима с камер](web_video_server.md)
* [Программирование](programming.md)
  * [Настройка камеры](camera_setup.md)
  * [Визуальные маркеры (ArUco)](aruco.md)
    * [Распознавание маркеров](aruco_marker.md)
    * [Навигация по карте маркеров](aruco_map.md)
  * [Навигация по Optical Flow](optical_flow.md)
  * [Автономный полет в OFFBOARD](simple_offboard.md)
  * [Системы координат](frames.md)
  * [Примеры кода](snippets.md)
  * [Лазерный дальномер](laser.md)
  * [Светодиодная лента](leds.md)
  * [Работа с GPIO](gpio.md)
  * [Ультразвуковой дальномер](sonar.md)
  * [Компьютерное зрение](camera.md)
  * [Визуализация с помощью rviz и rqt](rviz.md)
  * [Автозапуск ПО](autolaunch.md)
  * [Использование JavaScript](javascript.md)
  * [Блочное программирование](blocks.md)
  * [Симулятор](simulation.md)
    * [Сборка на собственной машине](simulation_native.md)
    * [Установка виртуальной машины](simulation_vm.md)
    * [Использование симулятора](simulation_usage.md)
  * [ROS](ros.md)
  * [MAVROS](mavros.md)
* [Дополнительные материалы](supplementary.md)
  * [COEX Pix](coex_pix.md)
  * [COEX PDB](coex_pdb.md)
  * [Гид по автономному полету](auto_setup.md)
  * [Имя хоста](hostname.md)
  * [Симулятор](sitl.md)
  * [Настройка PID](pid_tuning.md)
  * [Навигация по настенным маркерам](wall_aruco.md)
  * [CAD-модели Клевера](models.md)
  * [Docker-контейнер с симулятором](sitl_docker.md)
  * [Установка ROS Melodic](ros-install.md)
  * [Калибровка камеры](camera_calibration.md)
  * [Подключение к VPN ZeroTire](zerotire_vpn.md)
  * [Подключение к VPN Hamachi](hamachi_vpn.md)
  * [Управление мультикоптером при помощи 4G связи](4g.md)
  * [Пакеты Клевера на Jetson Nano](jetson_nano.md)
  * [Пилотирование со смартфона](rc.md)
  * [Настройка сети RPi](network.md)
  * [Интерфейс UART](uart.md)
  * [Параметры PX4](px4_parameters.md)
  * [Работа с логами PX4](flight_logs.md)
  * [Прошивка PX4](firmware.md)
  * [Протокол MAVLink](mavlink.md)
  * [Использование мультиметра](test_connection.md)
  * [Неисправности радиоаппаратуры](radioerrors.md)
  * [Прошивка ESC контроллеров](esc_firmware.md)
  * [Взаимодействие с Arduino](arduino.md)
  * [Подключение GPS](gps.md)
  * [Работа с ИК датчиками](ir_sensors.md)
  * [Установка FPV](fpv_clover_4_2.md)
  * [Установка FPV (Клевер 3)](fpv.md)
  * [Магнитный захват](magnetic_grip.md)
  * [Механический захват](mechanical_grip.md)
  * [Сборка шаровой защиты](sphere_guard.md)
  * [Управление в режиме тренера](trainer_mode.md)
  * [Техника лужения](tinning.md)
  * [Подключение PX4FLOW](px4flow.md)
  * [Типы силовых разъемов](connectortypes.md)
  * [Модуль ESP8266](esp8266_bridge.md)
  * [Сборка и модификация образа Клевера](image_building.md)
  * [Подключение регулятора 4 в 1](4in1.md)
  * [Светодиодная лента (legacy)](leds_old.md)
  * [Вклад в Клевер](contributing.md)
  * [Переход на версию 0.20](migrate20.md)
  * [COEX Duocam](duocam.md)
    * [Виртуальная MAVLink-камера](duocam_mavlink.md)
* [Мероприятия](events.md)
  * [CopterHack-2021](copterhack2021.md)
  * [CopterHack-2019](copterhack2019.md)
  * [Олимпиада НТИ 2019](nti2019.md)
  * [Робокросс-2019](robocross2019.md)
  * [CopterHack-2018](copterhack2018.md)
  * [CopterHack-2017](copterhack2017.md)
* [Проекты на базе Клевера](projects.md)
  * [Шоу коптеров](clever-show.md)
  * [Innopolis Open 2020 (L22_ÆRO)](innopolis_open_L22_AERO.md)
  * [Олимпиада НТИ 2020 (P4DF2)](nti2020_p4df2.md)
  * [Генератор ArUco карт](arucogenmap.md)
  * [Модель аэротакси в городе](bigchallenges.md)
  * [Шаровая защита коптера](shield.md)
  * [Дрон для 3D-сканирования человека](3dscan.md)
  * [Распознавание лиц](face_recognition.md)
  * [Управление дроном силой мысли](control_emotions.md)
  * [Подсчет количества объектов c камеры](object_counting.md)
  * [Пульт на Андроид](android.md)
  * [Блочный конструктор полета](clever_blocks.md)
  * [Калибровка камеры (legacy)](camera_calib.md)
  * [Управление дроном для оценки позы человека](human_pose_estimation_drone_control.md)
  * [Распознавание видов агрокультур](agriculture.md)

## Учебник

* [Теория и видеоуроки](lessons.md)
* [Учебно-методическое пособие](metod.md)
* [Контрольные материалы](tests.md)
