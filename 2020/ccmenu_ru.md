---
created: 2020-05-31
---

# CCMenu

Был такой инструмент «непрерывной сборки» (по-русски – CI) как CruiseControl (2001–2010).
Написанный работниками ThoughtWorks, проект с открытым исходным кодом под BSD-лицензией, видимо, получил большую известность.
http://cruisecontrol.sourceforge.net

Они придумали формат CCTray который стал стандартом де-факто для описания статуса проектов в CI-системах:
https://cctray.org/v1/

Travis, Jenkins, TeamCity, Drone CI, и многие другие предоставляют специальные URL-адреса по которым отдают информацию о состоянии сборок, например:
https://ci.chuhlomin.com/api/badges/chuhlomin/timestamp/cc.xml
В Drone CI ожидаемо это работает только для публичных проектов.

Остается другая сторона вопроса: предоставление этой информации пользователю в удобном виде.
В MacOS с этим справляется программа под названием CCMenu (см. скриншот).

http://ccmenu.org

![CCMenu promo](ccmenu.png "CCMenu promo")

#ci #app #macos