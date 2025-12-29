# DevOpsLab_08 Devops compose

Устанавливаем compose и создаем структуру файлов.
<img width="825" height="257" alt="image" src="https://github.com/user-attachments/assets/14fc1e56-25d7-4831-8699-12f47f5465a5" />
<img width="585" height="148" alt="image" src="https://github.com/user-attachments/assets/0aa9863e-c0a3-43c9-909e-04da3767a1a0" />

Создаем веб-приложение в файле app.py, объявляем зависимости для python в файле requirements.txt".
<img width="731" height="457" alt="image" src="https://github.com/user-attachments/assets/c5b16dab-4bb3-492c-9e55-b5841109f8f5" />
<img width="600" height="248" alt="image" src="https://github.com/user-attachments/assets/164d1248-9985-4b55-8567-2dfff8a1f1b4" />

Запускаем контейнер с redis.
<img width="833" height="325" alt="image" src="https://github.com/user-attachments/assets/bf8510f0-79c8-461e-adb7-9576925a335a" />

Запускаем оба сервис-контейреа Flask+Redis и проверяем стек.
<img width="829" height="263" alt="image" src="https://github.com/user-attachments/assets/2ccaf2fa-5e08-4762-833b-58a5ec40e084" />
<img width="833" height="277" alt="image" src="https://github.com/user-attachments/assets/7ee3dd83-0773-49a3-ae9a-1ab30dd2e7db" />

Проверяем отображение в браузере и через curl.
<img width="733" height="186" alt="image" src="https://github.com/user-attachments/assets/05a5e5fe-3a86-460d-bbac-2c57ee6c13f4" />
<img width="906" height="222" alt="image" src="https://github.com/user-attachments/assets/0dc7330d-bc84-40ae-9daa-0d3fe6caaf2c" />

Добавляем файлы, собраем мониторинг prometheus+grafana и выводим будущую структуру каталогов.
<img width="776" height="449" alt="image" src="https://github.com/user-attachments/assets/0b2af660-9983-4c26-b3a1-abf808647e56" />

Вносим изменения в файлы doker-compose.yml, prometheus.yml, datasours.yml
<img width="644" height="689" alt="image" src="https://github.com/user-attachments/assets/4c3dde5c-6421-4e78-877b-d7598a26a33c" />
<img width="600" height="613" alt="image" src="https://github.com/user-attachments/assets/a01ea392-4452-4e3e-b742-dd57d5cfde85" />
<img width="610" height="342" alt="image" src="https://github.com/user-attachments/assets/1a568136-9112-47cd-b246-0dd71a99f6a8" />

Запускаем оба сервис-контейнера Prometheus+Grafana.
<img width="816" height="683" alt="image" src="https://github.com/user-attachments/assets/013f6ee4-bbc8-49f0-93ee-83b29d2c808a" />

Проверка мониторинга Prometheus+Grafana.
<img width="825" height="186" alt="image" src="https://github.com/user-attachments/assets/cf34a09f-f318-473d-938a-03f1d30c905b" />

Заходим на страницу авторизации в Grafana по адресу localhost:3000
<img width="972" height="990" alt="image" src="https://github.com/user-attachments/assets/e3f985dc-5bd8-4e91-9e80-4290433d892e" />

Для просмотра метрики самого Prometheus необходимо указать ссылку на сам сервис в настройках.
<img width="1280" height="633" alt="image" src="https://github.com/user-attachments/assets/4b69d589-cc83-42f5-9a80-053c7d3021e4" />
<img width="1280" height="612" alt="image" src="https://github.com/user-attachments/assets/3342abc1-a27e-49d6-b0b4-acde230e4cc1" />

Добавляем мониторинг нашего Flask-приложения, пересобираем стек мониторинга и проверяем экспортер.
<img width="523" height="253" alt="image" src="https://github.com/user-attachments/assets/f4da97ce-4d6c-40ad-8d4d-5bf5f97305b3" />
<img width="448" height="405" alt="image" src="https://github.com/user-attachments/assets/6f6279b8-d9e5-4e4d-97ac-be72589a264d" />

<img width="851" height="241" alt="image" src="https://github.com/user-attachments/assets/dc4b9bb9-9e69-496d-82c8-feee1eb8e867" />
<img width="849" height="242" alt="image" src="https://github.com/user-attachments/assets/07f93280-545a-442c-8349-5b58356db5cc" />

Создаем дашборд и проверяем отображение метрик на дашборде.
<img width="991" height="702" alt="image" src="https://github.com/user-attachments/assets/62280c83-f6fa-42d8-960a-b0850d6e6432" />
<img width="1141" height="921" alt="image" src="https://github.com/user-attachments/assets/01abcde0-7a01-48cd-aa83-2e318c213491" />
<img width="1280" height="543" alt="image" src="https://github.com/user-attachments/assets/c86bae39-c6ea-4c8c-b637-29d745e30a41" />

Проверяем, что выводится на сайте.
<img width="1115" height="220" alt="image" src="https://github.com/user-attachments/assets/d91063f7-c3c5-4725-8549-1f4cab1770d4" />
