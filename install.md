# 설치
지니PHP는 라라벨 프레임워크를 기반으로 확장된 웹 응용개발 환경입니다. 

## 1. 패키지 설치
지니PHP는 라라벨과 지니 패키지들을 결합된 컴포저 project를 제공합니다.

```
composer create-project jiny/laravel 프로젝트
```

## 2. 수동설치
순수한 라라벨 프레임워크를 기반으로 추가 패키지를 설치하여 지니PHP를 시작할 수 있습니다.

### 2.1 라라벨 설치
먼저 최신의 라라벨 프레임워크를 설치합니다.
```
composer create-project --prefer-dist laravel/laravel 프로젝트명 버젼
```

### 2.2 모듈설치
지니 모듈관리자를 설치하고 초기화 합니다.
```
composer require jiny/modules
php artisan module:init
```
모듈 기능을 이용하여 지니에서 제공하는 다양한 개발 모듈을 설치할 수 있습니다. 모든 개발 모듈은 `/modules` 폴더 안에 설치 됩니다.

