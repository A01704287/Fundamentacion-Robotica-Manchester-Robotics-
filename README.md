# Fundamentacion-Robotica-Manchester-Robotics-
En este repositorio se encontraran los entregablesa los mini challenges y al reto impartidos por manchester robotics durante el primer periodo de clases Feb-Jun 2024.
En el repositorio se podran encontrar los videos demostrativos de los mini retos ejecutados y corriendo al igual que su codigo.
Todos las carpetas encontradas en este repositorio son las pertenecientes a la carpeta src/ros2_ws de nuestro workspace creado en ros2. De la misma mnera encontraras un video del funcionamiento de cada uno de los challenges. 

A continuacion anexo algunos de los comandos utilizados para correr dichos mini retos desde la terminal.
Comandos desde la terminal:
mor20mcr2-virtual-machine:-$ colcon build
mor2@mcr2-virtual-machine:~$ source install/setup.bash
mcr2@mcr2-virtual-machine:~$ ros2 launch signal decomposition signal_decomposition launch.py
mcr2@mcr2-virtual-machine:-$ ros2 param set /signal_generator_ node square. amplitude 2.5
mcr2@mor2-virtual-machine:~$ ros2 param set /signal generator_ node signal_type 2
mcr2@mor2-virtual-machine:r$ ros2 run basic_comms_signal process
mcr2@mor2-virtual-machine:r$ ros2 run basic_comms_signal talker
mcr2@mor2-virtual-machine:r$ ros2 run basic_comms_signal listener
mcr2@mor2-virtual-machine:r$ ros2 run basic_comms_signal signal generator
mcr2@mor2-virtual-machine:r$ ros2 run rqt_plot rqt_plot
