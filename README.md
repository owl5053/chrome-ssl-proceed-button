# Chrome SSL Override

Small `.reg` files that bring back the **"Proceed"** button on Chrome's SSL warning page.
Небольшие `.reg`-файлы, возвращающие кнопку **«Продолжить»** на странице предупреждения о сертификате в Chrome.

---

## EN

Chrome hides the "Proceed anyway" button for most SSL errors. These files toggle the `SSLErrorOverrideAllowed` policy so the button appears again — e.g. when a site like `rzd.ru` serves a certificate Chrome doesn't trust.

### Files
- `chrome_ssl_override_on.reg` — enables the button
- `chrome_ssl_override_off.reg` — removes the setting (restores default)

### Usage
1. Double-click the `.reg` file.
2. Confirm the registry change.
3. Restart Chrome.

### ⚠️ Warning
This does **not** fix the certificate. It only lets you **choose** whether to proceed.
- The button will appear on **all** sites with SSL errors, not just one.
- HSTS sites will still be blocked (Chrome limitation).
- Phishing / spoofed sites may also have bad certs — check the address bar.
- Don't enter passwords or card details on sites where you bypassed the warning.
- Use at your own risk.

---

## RU

Chrome скрывает кнопку «Продолжить» для большинства ошибок SSL. Эти файлы переключают политику `SSLErrorOverrideAllowed`, и кнопка снова появляется — например, при открытии сайта `rzd.ru`, который отдаёт сертификат, которому Chrome не доверяет.

### Файлы
- `chrome_ssl_override_on.reg` — включает кнопку
- `chrome_ssl_override_off.reg` — удаляет параметр (возвращает дефолт)

### Установка
1. Запустите `.reg`-файл двойным кликом.
2. Подтвердите изменение реестра.
3. Перезапустите Chrome.

### ⚠️ Важно
Это **не исправляет** сертификат. Вы просто получаете возможность **сами решить**, заходить или нет.
- Кнопка появится **на всех** сайтах с ошибками SSL, а не только на одном.
- Сайты с HSTS всё равно будут блокироваться (ограничение Chrome).
- У фишинговых и подменённых сайтов тоже бывают «битые» сертификаты — смотрите на адресную строку.
- Не вводите пароли и данные карт там, где обошли предупреждение.
- Используйте на свой страх и риск.

---

## License / Лицензия
MIT
