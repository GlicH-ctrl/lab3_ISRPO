# Расширенный Markdown: Дополнительные возможности

## Чекбоксы (списки задач)

### Мини-план на день
- [x] Изучить продвинутые возможности Markdown
- [x] Практиковать создание таблиц и списков
- [ ] Реализовать задание по программированию
- [ ] Оформить документацию
- [x] Сделать скриншоты всех этапов
- [ ] Запушить финальную версию на GitHub

## Сноски

Markdown полезен в разработке[^1].

GitHub поддерживает множество расширений Markdown[^2].

[^1]: Синтаксис Markdown поддерживается на GitHub, GitLab, в большинстве редакторов кода и систем документирования.
[^2]: Начиная с 2022 года GitHub добавляет поддержку алертов, математических формул и других расширений.

## Alert-блоки GitHub

> [!NOTE]
> Это простая заметка. Используется для нейтральной информации.

> [!TIP]
> Совет по использованию: Для экранирования специальных символов в Markdown используйте обратный слэш \.

> [!IMPORTANT]
> Не забывайте делать коммиты после каждого выполненного задания!

> [!WARNING]
> Будьте внимательны при работе с Git — неправильные команды могут удалить изменения.

> [!CAUTION]
> Осторожно! Не путайте команды git push и git pull — они работают в противоположных направлениях.

## Escape-символы (экранирование)

\# Это не заголовок, а просто текст с решёткой

\*это просто звёздочка\*, а не выделение текста

\_и это просто подчёркивание\_

\~\~это не зачёркнутый текст\~\~

## Встроенный HTML

<p style="color: blue; font-size: 18px; background-color: #f0f0f0; padding: 10px; border-radius: 5px;">
Этот текст оформлен с помощью <strong>HTML-тегов</strong> внутри Markdown-документа. Можно использовать любые стили и атрибуты.
</p>

<div style="border: 2px solid green; padding: 15px; margin: 10px 0;">
  <h3 style="color: darkgreen;">Заголовок внутри HTML-блока</h3>
  <p>Этот параграф тоже внутри HTML. Здесь можно делать <span style="color: red;">разноцветный текст</span> и другие интересные вещи.</p>
</div>

<table style="border: 2px solid black; background-color: #e6f7ff; width: 100%;">
  <tr>
    <th style="border: 1px solid black;">Имя</th>
    <th style="border: 1px solid black;">Возраст</th>
    <th style="border: 1px solid black;">Город</th>
  </tr>
  <tr>
    <td style="border: 1px solid black;">Иван</td>
    <td style="border: 1px solid black;">25</td>
    <td style="border: 1px solid black;">Москва</td>
  </tr>
  <tr>
    <td style="border: 1px solid black;">Мария</td>
    <td style="border: 1px solid black;">23</td>
    <td style="border: 1px solid black;">СПб</td>
  </tr>
</table>