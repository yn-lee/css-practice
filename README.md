# css-practice
css-practice🌹


### float project 
----
#### 1.  구조 ( 7-1 Pattern )  (7 folders, 1 file)

Sass 연습겸, 프로젝트 구조 7개 중 5개 사용 
```
sass  
|  
|– abstracts/ (or utilities/)  
| |– _variables.scss   
| |– _functions.scss   
| |– _mixins.scss  
|  
|– base/  
| |– _animation.scss 
| |– _base.scss 
| |– _typography.scss 
| |– _utilities.scss
|
|  
|– components/ (or modules/)  
| |– _bg-video.scss 	// 비디오 배경
| |– _buttons.scss 		// 버튼
| |– _card.scss 		// 카드형
| |– _composition.scss 	// 첫번째세션 사진
| |– _feature-box.scss	// 두번째 세션 카드형  
| |– _form.scss 		// Form 
| |– _popup.scss 		// Carousel  
| |– _story.scss		// 네번째 세션   
|  
|– layout/  
| |– _grid.scssn  		// Gird (float용 연습)
| |– _header.scss 		//   
| |– _footer.scss 		// 
| |– _navigation.scss 
|  
|– pages/  
| |– _home.scss 		// Home specific styles   
`– main.scss 			// Main Sass file
```
참고 : [7-1 Pattern](https://sass-guidelin.es/ko/#section-37)

#####  ▶ scss 파일을 수정할 때마다  자동으로  컴파일 위해 추가
```
npm run compile:sass
```
##### ▶ VSCODE - Live Server 설치

##### 수정할 때마다 자동으로 서버 실행시켜줍니당.  바로바로 확인가능. 
 　
　
 
 　
 
👀 Popup 두번째 이미지 하단 여백 왜그런지 찾아서 수정해보기 .. 왜 생길깡..

