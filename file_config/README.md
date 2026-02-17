<h3>file_config</h3>
<h4>Библиотека для работы с файлами конфигурации</h4>
<hr>
<p>Содержание:</p>
<hr>
<p>
    <a href="#loadConfig">
        int loadConfig(const char *file_name, config_t *config, size_t size);
    </a>
</p>
<hr>
<p>Описание функций:</p>
<hr>
<p id="loadConfig">
    <b>int loadConfig(const char *file_name, config_t *config, size_t size);</b>
</p>
<p>
    Функция читает файл конфигурации по строчно, разбирает строки и сохраняет
    их значение в полях структуры config_t.<br>
    <li>Описание параметров:
        <ul>const char *file_name - строка с именем файла;</ul>
        <ul>config_t *config - массив структур config_t;</ul>
        <ul>size_t size - размер массива config.</ul>
    </li>
</p>

<hr>
<p>Версия 1.0.0:</p>
<p>- добавлена loadConfig;</p>
