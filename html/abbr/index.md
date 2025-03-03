---
title: "`<abbr>`"
authors:
  - xpleesid
keywords:
  - аббревиатура
  - акроним
tags:
  - doka
---

## Кратко

Тег `<abbr>` используется для вывода аббревиатур или акронимов.

## Пример

Тегу `<abbr>` можно задать атрибут `title`, где будет раскрыта аббревиатура. В `title` допускается писать только расшифровку аббревиатуры и ничего больше. Также можно использовать [`глобальные атрибуты`](/html/global-attrs/).

Некоторые браузеры подчёркивают текст внутри `<abbr>` пунктирной линией, а при наведении выводят всплывающую подсказку, в которой будет содержимое атрибута `title`. Но не все 🤔

```html
<p>
  <abbr title="Организация объединённых наций">ООН</abbr>
  — международная  организация, созданная для
  поддержания и укрепления международного
  мира и безопасности, а также развития
  сотрудничества между государствами
</p>
```

<iframe title="Пример с ЮНЕСКО" src="demos/un/" height="200"></iframe>

## Как пишется

`<abbr>` можно использовать вместе с [`<dfn>`](/html/dfn/) для более формального описания определения:

```html
<p>
  <dfn>
    Организация объединённых наций
    (<abbr title="Организация объединённых наций">ООН</abbr>)
    — международная  организация, созданная для
    поддержания и укрепления международного мира и безопасности,
    а также развития сотрудничества между государствами
  </dfn>
</p>
```

<iframe title="Пример с тегом dfn" src="demos/with-dfn/" height="200"></iframe>
