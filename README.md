# About

React Tutorial + StoryBook + Storyshot
https://ja.reactjs.org/tutorial/tutorial.html  
https://storybook.js.org/
https://storybook.js.org/docs/react/workflows/snapshot-testing

## スナップショットテストとは
スナップショットのテストはUI が予期せず変更されていないかを確かめるのに用いる
現在の画面のスナップショット（キャプチャみたいなもの）を保存しておいて、テストの時にそのスナップショットと今の画面と比較して変更点を出力してくれる。

## スナップショットテストを用いることで、どのような不具合が防止できるか
 - 修正により、既存の画面に影響が出ないか確認できる
 -
 -

## スナップショットテストでは防止できない不具合
 - テスト実行タイミングに依存する値の場合、期待通りにならない
 - 差分によって表示がどう変化するかわからない
 - 

## Quiz

### スナップショットファイルはコミットする必要があるか

<details>
<summary>解答</summary>
必要ある。
スナップショットはテストの一部とみなされるべきで、他の開発する人にも必要になるため
</details>

### スナップショットテストで単体テストを代替できますか

<details>
<summary>解答</summary>
いいえ
スナップショットテストのねらいは既存の単体テストを代替することではなく、追加のテスト結果を提供してテストにおける作業負担を減らすことです
</details>

### コードカバレッジはスナップショットテストでも機能しますか？

<details>
<summary>解答</summary>
はい
</details>

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `yarn build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
