
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

.. image:: _static/esxi-host-list.png


* Cluster list

Список кластеров под управлением vCenter сервера.

.. image:: _static/cluster-list.png
   :align: left


* Snapshot list

Список снапшотов. При наличии с временем хранения более суток, возникает аварийное сообщение.

.. figure:: _static/snapshot-list.png
   :align: left


* Issue list

Список обнаруженных проблем.

.. figure:: _static/issue-list.png
   :align: left

* Vmware tools status

Состояние vmware tools на виртуальных машинах.

.. figure:: _static/vmware-tools-status.png
   :align: left


vCenter, дополнительные проверки
--------------------------------


Здесь будут доп. проверки.