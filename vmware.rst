
Мониторинг vmware
=================

Перед загрузкой объектов vmware в icinga необходимо создать учётную запись, предоставить права на чтение и прописать параметры этой учётной записи в настройках icinga.

ESXi
----

На всех серверах ESXi собирается информация о загрузке процессора, памяти и дисковой системы. 



vCenter, базовые проверки
-------------------------

* ESXi host list

Список ESXi серверов под управлением vCenter сервера.

.. figure:: _static/esxi-host-list.png
   :scale: 50 %
   :align: center


* Cluster list

Список кластеров под управлением vCenter сервера.

.. figure:: _static/cluster-list.png
   :scale: 50 %
   :align: center

* Snapshot list

Список снапшотов. При наличии с временем хранения более суток, возникает аварийное сообщение.

.. figure:: _static/snapshot-list.png
   :scale: 50 %
   :align: center

* Issue list

Список обнаруженных проблем.

.. figure:: _static/issue-list.png
   :scale: 50 %
   :align: center

* Vmware tools status

Состояние vmware tools на виртуальных машинах.

.. figure:: _static/vmware-tools-status.png
   :scale: 50 %
   :align: center


vCenter, дополнительные проверки
--------------------------------


Здесь будут доп. проверки.