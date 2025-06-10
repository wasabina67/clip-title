# clip-title

WIP

ClipTitle 😎

Quickly copy any webpage title to your clipboard with just one click.

## Install

### chrome web store

https://chromewebstore.google.com/detail/cliptitle/fhjdloooegpencmhkinhoamobgahidkm

### Developer mode

https://github.com/wasabina67/clip-title/raw/refs/heads/main/zip/1.0/cliptitle.zip

## How to use

1. Open any webpage in Google Chrome
2. Right-click on the page and select "ClipTitle"
3. The title will be copied to your clipboard
4. You can paste it anywhere you like

## Developer Dashboard

### Creating a ZIP file

```bash
rm -rf cliptitle.zip && zip -r cliptitle.zip * -x "screenshots/*" -x "zip/*"
```

### Build / listing

- description

```
1. Open any webpage in Google Chrome
2. Right-click on the page and select "ClipTitle"
3. The title will be copied to your clipboard
4. You can paste it anywhere you like
```

- category: Tool
- language: English
- screenshot: `1280x800`, `JPEG`
- Homepage URL

```
https://github.com/wasabina67/clip-title
```

- Support URL

```
https://github.com/wasabina67/clip-title
```

### Build / privacy

#### 単一用途

```
ClipTitleは、現在表示しているウェブページのタイトルを、
ワンクリックでクリップボードにコピーすることを単一の目的とした拡張機能です。
これにより、ユーザーは任意のドキュメントに簡単にタイトルを追加できます。
```

#### 権限が必要な理由

contextMenus

```
この拡張機能は、ウェブページ上で右クリックした際に表示されるコンテキストメニューに、
「ClipTitle」という項目を追加するために、contextMenusの権限を使用しています。
これにより、ユーザーは簡単に拡張機能にアクセスできます。
```

activeTab

```
この拡張機能は、「ClipTitle」を選択した際に、現在開いているタブのタイトルを取得するためにactiveTabの権限を使用しています。

```

scripting

```
この拡張機能は、「ClipTitle」を選択した際に、現在開いているタブ内でスクリプトを実行し、クリップボードへの書き込みや通知表示を行うためにscriptingの権限を使用しています。
これにより、ウェブページのタイトルをクリップボードへ書き込み、通知を表示することができます。
```

clipboardWrite

```
この拡張機能は、ウェブページのタイトルを、ユーザーのクリップボードに書き込むためにclipboardWriteの権限を使用しています。
これにより、ユーザーは簡単にタイトルを、任意の場所に貼り付けることができます。
```

リモートコード を使用していますか？

- [x] いいえ、リモートコード を使用していません
