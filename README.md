### 실종 API

## 1. 실종 신고

Request URL : https://www.safe182.go.kr/api/lcm/missChild.do

## 2. 실종 경보

Request URL : https://www.safe182.go.kr/api/lcm/amberList.do

## 3. 실종 검색

`Request URL` : https://www.safe182.go.kr/api/lcm/findChildList.do

`Request Parameter`
|필수|파라미터명|파라미터설명|코드값|비고|길이|
|----|---------|-----------|-----|----|----|
|Y|esntlId|고유아이디|
|Y|authKey|인증키|
|Y|rowSize|게시물 수(숫자만 100개까지)|
|N|page|페이지(숫자만)|
|N|writngTrgetDscds[]|대상(정상아동(18세미만) : 010, 지적장애인 : 060 ,치매질환자 : 070 )|
|N|sexdstnDscd|성별(남자1, 여자2)|
|N|nm|이름|
|N|detailDate1|시작 발생일(2012-08-17) 10|
|N|detailDate2|종료 발생일(2012-08-18) 10|
|N|age1|시작 당시나이(숫자만)|
|N|age2|종료 당시나이(숫자만) |
|N|file2|실종아동사진(200K미만)|
|N|etcSpfeatr|신체특징|
|N|occrAdres|발생장소|
|N|xmlUseYN|xml사용여부|

## 4. 안전지도 정보

Request URL : https://www.safe182.go.kr/api/lcm/safeMap.do

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

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

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
