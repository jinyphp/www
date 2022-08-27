# JinyPHP
`지니PHP`는 기존 라라벨 프레임워크를 기반으로 자체 제작한 몇개의 패키지들을 포함하고 있습니다.


## [설치](install)
지니PHP는 손쉬운 설치를 위하여 자체적인 컴포저 project를 제공합니다. 또한, 라라벨과 지니 패키지를 이용하여 수동으로 개발 환경을 커스텀하여 구축할 수도 있습니다.


## 리소스 컴파일 및 실행

- 지니ERP는 기본적인 UI로 tailwind css를 이용하고 있습니다. nodejs의 npm 명령을 통하여
tailwind css와 리소스를 컴파일 합니다.

```
npm install && npm run build
```

> ui 리소스 컴파일 대신에 개발용 watch 형태로 실행할 수도 있습니다.
```
npm install && npm run dev
```

- php의 내장서버를 통하여 지니ERP를 실행합니다.
```
php artisan serve
```

## 주요기능
지니PHP가 보다 진보된 Laravel 개발환경인 이유는 편리한 추가 개발 모듈들을 설치하여 사용할 수 있다는 것입니다.

* [모듈관리](modules)
