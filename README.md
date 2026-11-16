# Degrees of Lewdity 한국어 번역판 (DoL-KR)

[Degrees of Lewdity](https://vrelnir.blogspot.com/) **0.5.13.8**의 한국어 번역본입니다.

[아카라이브 DOL 채널](https://arca.live/b/dolgame)에서 만들어 온 번역본([Ooo-eee/DoL_KrTranslation](https://github.com/Ooo-eee/DoL_KrTranslation), 게임 버전 0.5.12.13)을 이어받아, 원작 0.5.13.8에 맞춰 갱신하고 문체와 용어를 정리했습니다.

> 이 게임은 성인용입니다. 성적·폭력적인 내용을 담고 있으며 미성년자에게 적합하지 않습니다.

## 이전 번역본과 달라진 점

- **0.5.13.8 반영**: 원작에서 새로 생기거나 바뀐 문장 약 7,000줄과 선택지 문구 약 1,000개를 번역했습니다. 기존 번역문은 원문이 바뀌지 않은 한 그대로 두었습니다.
- **고유 명사 통일**: 같은 대상을 여러 가지로 적던 표기를 하나로 맞췄습니다(약 470곳). 거리 이름은 "○○ 가"(하이 가, 다뉴브 가…), 인물·장소는 용어집의 표준 표기를 따릅니다.
- **문체 통일**: 번역 안에서 갈리던 관례를 다수 쪽으로 정리했습니다.
  - 서술은 현재형 한다체, 선택지는 "~한다" 꼴("~하기" 1,400여 곳 변경)
  - 대사 뒤에 화자 표시가 이어지면 대사를 마침표로 끝냄(`"집에 가자." 로빈이 말한다.`)
  - 말더듬은 `"고-고마워."` 꼴
- **인물 말투 정리**: 이름 있는 인물 34명의 성격과 말투를 정리한 가이드를 만들고, 그에 맞춰 대사 약 1,400줄을 다듬었습니다(화계·호칭·1인칭이 장면마다 흔들리던 곳 위주).
- **원작과 어긋나 있던 수치 정리**: 기존 번역본에는 원작의 밸런스 변경(절도 수입, 과외 보수, 농장 시설 비용 등. 일부는 0.5.11.4에서 바뀐 것)이 반영되지 않은 줄이 남아 있었습니다. 매크로 인자와 본문에 적힌 금액 등 약 120곳을 원작 0.5.13.8의 값으로 맞췄습니다.
- 원작 갱신으로 구조가 바뀐 패시지의 코드를 원문과 맞추고, 그 과정에서 발견한 기존 오류(없는 함수를 부르던 출산 장면, 오타 난 식별자 등)를 고쳤습니다.

정리 기준은 [`docs/kr-translation/`](docs/kr-translation/)에 있습니다.

| 문서 | 내용 |
| --- | --- |
| [`STYLE.md`](docs/kr-translation/STYLE.md) | 문체·표기 규칙 |
| [`GLOSSARY-propernouns.md`](docs/kr-translation/GLOSSARY-propernouns.md) | 고유 명사 표준 표기 |
| `GLOSSARY-system.md` · `GLOSSARY-world.md` · `GLOSSARY-body-combat.md` | 시스템·세계·신체/전투 용어 |
| [`CONVENTIONS.md`](docs/kr-translation/CONVENTIONS.md) | 조사 마커, 한글화 사전(`game/kr_js/`) 등 기술 관례 |
| [`characters/`](docs/kr-translation/characters/) | 인물별 말투 가이드 |

### 알아 둘 점

이번 갱신분의 번역과 통일 작업은 AI(Claude)의 도움을 받아 진행했습니다. 원문과의 구조 비교, 빌드, 브라우저에서의 실행 점검은 자동으로 거쳤지만 사람이 모든 문장을 하나하나 검수한 것은 아닙니다. 어색한 문장이나 오역, 표기가 어긋난 곳을 발견하면 Issue나 Pull Request로 알려 주세요.

## 이용 방법

컴파일된 파일은 [Releases](https://github.com/Instplace/DoL-KR/releases)에서 받을 수 있습니다: PC용 zip(HTML과 `img` 폴더)과 안드로이드용 APK. 안드로이드판은 이 저장소의 키로 서명한 별도의 앱이라 원작의 공식 앱과 나란히 설치됩니다. 버전 태그를 올리면 GitHub Actions([`.github/workflows/release.yml`](.github/workflows/release.yml))가 컴파일해 게시합니다.

직접 빌드하는 방법은 원작과 같습니다. 아래에 이어지는 원문 README의 "How to build"를 참고하세요(`compile.bat` 또는 `compile.sh`를 실행하면 `Degrees of Lewdity.html`이 만들어집니다).

## 원작과 출처

- **원작**: Vrelnir의 [Degrees of Lewdity](https://vrelnir.blogspot.com/) ([소스 저장소](https://gitgud.io/Vrelnir/degrees-of-lewdity))
- **한국어 번역**: [아카라이브 DOL 채널](https://arca.live/b/dolgame)의 번역 참여자들, 그리고 그 결과물을 공개한 [Ooo-eee/DoL_KrTranslation](https://github.com/Ooo-eee/DoL_KrTranslation). 이 저장소의 첫 커밋이 그 번역본(0.5.12.13)입니다.

기존 번역에는 여러 참여자가 관여했으므로 개별 번역문의 저작자를 여기서 모두 특정하지는 않습니다.

## 라이선스

원작과 기존 번역본에 적용된 **CC BY-NC-SA 4.0**을 그대로 따릅니다. 이 저장소에서 더한 변경도 같은 조건으로 공개합니다.

- **BY (저작자표시)**: 원작과 번역본의 저작자 및 출처를 밝혀야 합니다.
- **NC (비영리)**: 영리 목적으로 이용할 수 없습니다.
- **SA (동일조건변경허락)**: 이 번역본을 고치거나 바탕으로 삼은 2차 저작물에도 같은 라이선스를 적용해야 합니다.

자세한 내용은 [`LICENSE`](LICENSE) 파일과 [라이선스 한글 요약](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.ko)을 참고하세요. 조건을 지키는 한 자유롭게 Fork하여 번역을 이어가거나 재배포할 수 있습니다.

아래로는 원작의 `README.md`가 이어집니다.

---

# Degrees of Lewdity

## Lexicon of Lewdity

Looking to contribute to Degrees of Lewdity? Read the [Lexicon of Lewdity](https://gitgud.io/Vrelnir/degrees-of-lewdity/-/wikis/home).

_Failure to do so can lead to your work being denied._

## How to build

### Changing the build version and type

1. Open `01-config\sugarcubeConfig.js`.
2. Edit the `window.StartConfig` object to the relevant config type.
    - Normal Build - `enableImages` needs to be `true` and `enableLinkNumberify` needs to be `true`.
    - Text Only Build - `enableImages` needs to be `false` and `enableLinkNumberify` needs to be `true`.
    - Android Build - `enableImages` needs to be `true` and `enableLinkNumberify` needs to be `false`.
3. `version` is optional between release versions but will be displayed on screen in several places and stored in the saves made.
4. `debug` is optional and will only effect new games.

### Compiling the html

1. On Windows: Run `compile.bat` or `compile-watch.bat`.
2. On Linux: Run `compile.sh`
3. Open `Degrees of Lewdity VERSION.html`.

### Build Android version (.apk)

See [README in devTools/apkbuilder](devTools/apkbuilder/README-windows.txt)

## Development

### Prerequisites

-   Read [Coder's-Guide](https://gitgud.io/Vrelnir/degrees-of-lewdity/-/wikis/Programming/Coder's-Guide)
-   [Node.js 16 or later](https://nodejs.org/en/).

### Optional Prerequisites

1. Install [Tweego](http://www.motoslave.net/tweego/) and remember the path where it was installed.
2. Add path to `tweego.exe` (e.g. `C:\Program Files\Twine\tweego-2.1.0-windows-x64`) to Windows `Path` environment variable.

### Initial setup

1. Install project dependencies:

    ```bash
    npm i
    ```

2. If you use Visual Studio Code:

    1. Install [Twee 3 Language Tools extension](https://marketplace.visualstudio.com/items?itemName=cyrusfirheir.twee3-language-tools)
    2. Install [ESLint extension](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint).
    3. Install [Stylelint extension](https://marketplace.visualstudio.com/items?itemName=stylelint.vscode-stylelint)
    4. Install and optionally configure [Code Spell Checker extension](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker):
        1. Use "English - United Kingdom" and "English - United States" dictionaries
        2. Enable spellchecking for `html`, `css`, `javascript` and other relevant programming languages and dictionaries
           The extension should automatically use these settings for the project via `.cspell.json`, including the custom dictionary in `.cspell-project-words.txt`, so manual configuration should not be necessary. If running `npx cspell .` yields an absurd amount of results (including words that are in the custom dictionary), then the settings may not be automatically set or recognised, so you should set them yourself. Make sure the custom dictionary is recognised, or the extension won't be very useful!
    5. Optionally enable fixing js/css on save. In `settings.json` set:

        ```json
        // This disables built-in formatting
        "[javascript]": {
          "editor.formatOnSave": false
        },
        "[css]": {
          "editor.formatOnSave": false
        },
        // This enables running ESLint, Prettier, Stylelint formatting on file save
        "editor.codeActionsOnSave": {
          "source.fixAll.eslint": true,
          "source.fixAll.stylelint": true
        },

        ```

### Linting

#### JavaScript

JavaScript code linting is handled by [`ESLint`](https://eslint.org/).

ESLint is [configured](./.eslintrc.cjs) to follow some of best practices ([ESLint Recommended Rules](https://eslint.org/docs/latest/rules/), [JavaScript Standard Style](https://standardjs.com/rules.html)) with formatting handled by Prettier (`eslint --fix` formats code with Prettier). You don't need to use `Prettier` VS Code extension to format `.js` files.

To run ESLint for single file:

```bash
npx eslint "game/03-JavaScript/02-Helpers/Utils.js"
```

or for all files inside `game` directory:

```bash
npx eslint "game/**"
```

##### Resolving issues

Some issues are fixable and can be auto-fixed when you save a file (provided ESLint extension is configured to run fix on save) or by running `eslint --fix file_relative_path`

If you find a rule that doesn't make sense for the project you can disable it inside `rules` section inside `.eslintrc.cjs`:

```json
rules: {
  ...
  // SugarCube extends native objects and we follow it
  "no-extend-native": "off",
  ...
}
```

Please discuss the reasons with the team before disabling the rule. Add a comment explaining why the rule was disabled

If ESLint reports a lot of issues for particular file and you cannot fix them all at once feel free to [disable particular rule](https://eslint.org/docs/latest/user-guide/configuring/rules#disabling-rules) for the file (there is quick actions menu when code with error is hovered):

```js
/* eslint-disable camelcase -- TODO: Fix variables' names */
...
let demo_rainbow_colors = [
...
```

Add a TODO comment explaining that this will be fixed someday

##### Global variables

ESLint may report an issue like `'myVariable' is not defined`. It means ESLint cannot figure out where the variable is defined. If you really meant to make variable global add the new variable to `.eslintrc.cjs` `globals` section inside corresponding group:

```json
myVariable: "readonly"
```

If the variable is suppose to be writable set `myVariable: "writable"` instead.

### CSS

CSS linting is handled by [`Stylelint`](https://stylelint.io/).

Stylelint is [configured](./stylelint.config.cjs) to follow [common conventions](https://github.com/stylelint/stylelint-config-standard) along with [rules for properties order](https://github.com/cahamilton/stylelint-config-property-sort-order-smacss) and formatting handled by Prettier (`stylelint --fix` formats code with Prettier). You don't need to use `Prettier` VS Code extension to format `.css` files.

To run Stylelint for the file:

```bash
npx stylelint "game/02-CSS/pillsInventory.css"
```

or for all CSS file inside `game` directory:

```bash
npx stylelint "game/**/*.css"
```

#### Resolving issues

Some issues are fixable and can be auto-fixed when you save a file (provided Stylelint extension is configured to run fix on save) or by running `stylelint --fix file_relative_path`.

Sometimes all issues cannot be fixed within single "fix" run (e.g. properties order). Simply run fix command several time until all auto-fixable issues are resolved.

If you find a rule that doesn't make sense for the project you can disable it inside `rules` section inside `stylelint.config.cjs`:

```js
rules: {
  // Class and ID patterns disabled for now due to the large amounts of classes and IDs that break this rule
  "selector-class-pattern": null,
  "selector-id-pattern": null,
  ...
}
```

Please discuss the reasons with the team before disabling the rule. Add a comment explaining why the rule was disabled

### Formatting

Formatting CSS and other non-JavaScript file is handled by `Prettier`. Formatting rules are set in `.prettierrc.json`

### Pre-commit hook

On pre-commit [`lint-staged`](https://github.com/okonet/lint-staged) using [`husky`](https://typicode.github.io/husky) lints/formats `.js`, `.css` with ESLint, Stylelint and formats other supported files with Prettier.

Pre-commit hook is the last quality gate to avoid "bad" code getting into the repository. It's better to make sure you aren't committing files with issues beforehand - you can run command `npm run lint-staged` when you've staged the files to check if there are issues.

If for some reason you really want to commit the code that fails linting add `--no-verify` parameter to `commit` call

```bash
commit --no-verify
```
