---
chapters: {"pages":{"de/adapterref/iobroker.admin/README.md":{"title":{"de":"no title"},"content":"de/adapterref/iobroker.admin/README.md"},"de/adapterref/iobroker.admin/admin/tab-adapters.md":{"title":{"de":"Der Reiter Adapter"},"content":"de/adapterref/iobroker.admin/admin/tab-adapters.md"},"de/adapterref/iobroker.admin/admin/tab-instances.md":{"title":{"de":"Der Reiter Instanzen"},"content":"de/adapterref/iobroker.admin/admin/tab-instances.md"},"de/adapterref/iobroker.admin/admin/tab-objects.md":{"title":{"de":"Der Reiter Objekte"},"content":"de/adapterref/iobroker.admin/admin/tab-objects.md"},"de/adapterref/iobroker.admin/admin/tab-states.md":{"title":{"de":"Der Reiter Zustände"},"content":"de/adapterref/iobroker.admin/admin/tab-states.md"},"de/adapterref/iobroker.admin/admin/tab-groups.md":{"title":{"de":"Der Reiter Gruppen"},"content":"de/adapterref/iobroker.admin/admin/tab-groups.md"},"de/adapterref/iobroker.admin/admin/tab-users.md":{"title":{"de":"Der Reiter Benutzer"},"content":"de/adapterref/iobroker.admin/admin/tab-users.md"},"de/adapterref/iobroker.admin/admin/tab-events.md":{"title":{"de":"Der Reiter Ereignisse"},"content":"de/adapterref/iobroker.admin/admin/tab-events.md"},"de/adapterref/iobroker.admin/admin/tab-hosts.md":{"title":{"de":"Der Reiter Hosts"},"content":"de/adapterref/iobroker.admin/admin/tab-hosts.md"},"de/adapterref/iobroker.admin/admin/tab-enums.md":{"title":{"de":"Der Reiter Aufzählungen"},"content":"de/adapterref/iobroker.admin/admin/tab-enums.md"},"de/adapterref/iobroker.admin/admin/tab-log.md":{"title":{"de":"Der Reiter Log"},"content":"de/adapterref/iobroker.admin/admin/tab-log.md"},"de/adapterref/iobroker.admin/admin/tab-system.md":{"title":{"de":"Die Systemeinstellungen"},"content":"de/adapterref/iobroker.admin/admin/tab-system.md"}}}
translatedFrom: de
translatedWarning: Если вы хотите отредактировать этот документ, удалите поле «translationFrom», в противном случае этот документ будет снова автоматически переведен
editLink: https://github.com/ioBroker/ioBroker.docs/edit/master/docs/ru/adapterref/iobroker.admin/tab-instances.md
title: Экземпляры райдера
hash: wBKP7K139TehQSv9mxy6iGcoIz/dj9X8D7lacF88tpw=
---
# Экземпляры на вкладке
Здесь перечислены экземпляры, уже установленные через вкладку Адаптер, и их можно настроить соответствующим образом.

<span style="line-height: 1.5;"></span>

![iobroker_admin_instanzen_inhalt00](../../../de/adapterref/iobroker.admin/img/tab-instances_Inhalt00.jpg)

## Строка заголовка
Строка заголовка содержит значки для наиболее важных процессов. Для каждой иконки есть контекстная помощь.
Просто держите мышь на значке некоторое время. Также есть информация о загрузке сервера

![iobroker_admin_instanzen_headline_icons](../../../de/adapterref/iobroker.admin/img/tab-instances_Icons-e1476803621402.jpg)

### **Значки в деталях:**
### **1.) Включите режим администратора**
Когда выбран этот значок, отображаются дополнительные столбцы для настройки экземпляров (функция переключения).
Смотрите содержание страницы для получения дополнительной информации.

### **2.) Обновить вид**
Если только что созданные экземпляры не отображаются, нажатие на этот значок поможет обновить состояние страницы.

### **3.) Информация о состоянии сервера**
Правая часть строки заголовка содержит информацию о действиях экземпляров, а также об использовании сервера ioBroker.

Первые числа обозначают память, использованную экземплярами, и оставшуюся свободную память в МБ. За этим свободная память в%. Квадратные скобки содержат имя сервера ioBroker и количество запущенных процессов.

## Содержание страницы
![iobroker_admin_instanzen_headline_columns](../../../de/adapterref/iobroker.admin/img/tab-instances_Headline_Columns.jpg)

На странице установленные экземпляры адаптеров представлены в виде таблицы.

Таблица состоит из следующих столбцов:

### **1.) Состояние**
Здесь состояние экземпляра отображается на светофоре. Дальнейшая информация получается при наведении мышкой на сигнал.

![iobroker_admin_instanzen_status](../../../de/adapterref/iobroker.admin/img/tab-instances_Instanzen_Status.jpg)

Не во всех случаях есть этот светофор. Это не повод для паники. Это либо синхронизированные экземпляры, которые подключаются к контроллеру только на короткое время, а затем немедленно отключаются, либо выключаются, например. продолжать работать в фоновом режиме.

### **2.) Значок**
Это покажет значок, используемый ioBroker-широкий для этого адаптера

### **3.) Экземпляр**
Этот столбец содержит имя экземпляра. он состоит из имени адаптера, а также номера, который последовательно нумеруется в порядке установки экземпляров. Первый экземпляр получает 0.
Это имя является основой для именования точек данных в ioBroker.

### 4.) активирован
Здесь экземпляр запускается или останавливается. Зеленый знак паузы указывает, что адаптер работает и его можно приостановить, щелкнув по нему, а красный знак воспроизведения показывает остановленный экземпляр, который можно запустить одним щелчком мыши.

### **5.) Конфигурация**
При щелчке по этому значку открывается меню конфигурации адаптера. Соответствующие меню описаны в соответствующих [адаптеры](http://www.iobroker.net/?page_id=2236&lang=de).

### **6.) Перезагрузка**
Нажмите на этот значок, чтобы перезапустить соответствующий экземпляр

### **7.) Мусорный бак**
Этот значок удаляет соответствующий экземпляр. Другие экземпляры того же адаптера сохраняются.
Даже сам адаптер остается.

### **8.) Веб-ссылка**
За этим значком скрывается ссылка на сайт данного экземпляра. Либо потому, что этот адаптер поставляется с собственным веб-интерфейсом (с другим портом), либо просто с другим путем. Отчасти эта ссылка также ведет на страницы справки.

### **9.) Название**
Здесь дано имя экземпляра. Это имя может быть изменено в соответствии с вашими пожеланиями или потребностями. Это особенно полезно, если есть несколько экземпляров адаптера (в противном случае один и тот же Bezeischnung). Это будет, например, для hm-rpc, если есть один экземпляр для RF, Wired и CuxD.

### **10.) Планирование**
Для адаптеров, которые запускаются по расписанию, вы будете введены здесь, когда этот адаптер должен запуститься.
Это расписание представлено в формате [cronjobs](https://de.wikipedia.org/wiki/Cron#Beispiele).
Для изменения нажмите на кнопку с тремя точками. Он открывает окно ввода с большим количеством дополнительной информации и помощи.

![iobroker_admin_instanzen_cronjob](../../../de/adapterref/iobroker.admin/img/tab-instances_Cronjob.jpg)

### **11.) Перезагрузка**
Если этот флажок установлен, здесь также можно создать расписание, когда этот экземпляр должен быть перезапущен.

### **12.) Уровень логирования**
В этом столбце можно настроить соответствующий уровень журнала для экземпляра. Доступны отладка, информация, предупреждение и ошибка. По умолчанию это значение установлено в info. Если у вас сложилось впечатление, что что-то идет не так, вы можете отладить его. затем в журнале вкладок для этого экземпляра также выводится отладочная информация, которая может помочь найти ошибку. И наоборот, вы можете установить это значение выше, чтобы журнал не был настолько обширным.

### **13.) Ограничение ОЗУ**
Здесь вы можете указать, сколько памяти экземпляра должно быть предоставлено в качестве меры предосторожности.
Этот объем памяти больше не доступен для других задач и не должен быть слишком большим, особенно для систем с нехваткой памяти. Если экземпляру временно требуется больше памяти, он, конечно, будет выделен системой, но будет немедленно возвращен в систему. В то время, когда экземпляру требуется больше памяти, чем было зарезервировано, требуемая память отображается красным цветом.

### 14.) Использование ОЗУ
Это показывает фактическую память, используемую экземпляром. Эти значения регулярно обновляются. После обновления эти значения кратковременно отображаются зеленым цветом.