# shared/assets

이 폴더는 프로젝트 전역에서 사용하는 이미지, 폰트, 아이콘 등 정적 에셋 파일을 관리합니다.

## 주요 역할

- 이미지, 폰트, 아이콘 등 정적 리소스 관리
- 프로젝트 전체에서 참조되는 에셋 파일 제공

## 개발 가이드

- 에셋 파일은 논리적으로 구분하여 하위 폴더로 관리하세요.
- 불필요한 대용량 파일은 저장소에 포함하지 마세요.

## 샘플 코드

```tsx
// 예시: public 경로에서 에셋 사용
<img src={require('@/shared/assets/logo.svg')} alt="로고" />
```
