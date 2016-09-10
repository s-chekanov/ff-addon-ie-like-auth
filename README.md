IE Like HTTP-Authentication addon for FireFox
=============================================

RU:  
Страничка аддона: https://addons.mozilla.org/ru/firefox/addon/ie-like-http-authentication/ (с этого линка можно поставить его в браузер). 
Решает проблему логина на IIS сервер с кирилическими логин/пасс через http basic авторизацию (раньше для этого приходилось ставить Internet Explorer).
Меняет кодировку с ISO-8859-1 на Windows-1251 (Cyrylic) в заголовках http пакета . 
  
EN:  
Addon homepage: https://addons.mozilla.org/en-US/firefox/addon/ie-like-http-authentication/ (use this page to install addon on your firefox).
It solves problem with access IIS server with http basic authentication when you use cyrylic login/passw.
It convert http authentication header from ISO-8859-1 to Windows-1251 (Cyrylic) charset. 
Read more about this bug: https://bugzilla.mozilla.org/show_bug.cgi?id=41489  
