# Toycore SEO Module

Toycore의 SEO 설정, `robots.txt`, `sitemap.xml` 출력을 담당하는 선택 모듈입니다.

## 설치

1. 릴리스 zip을 다운로드합니다.
2. 압축을 풀어 `seo/` 디렉터리를 Toycore의 `modules/seo/`에 업로드합니다.
3. Toycore 관리자 `/admin/modules`에서 설치하고 활성화합니다.

Git, Composer, SSH 없이도 zip 업로드 방식으로 설치할 수 있어야 합니다.

## 개발 구조

```text
module/ -> Toycore 설치본의 modules/seo/
```

릴리스 zip은 `module/` 내부가 아니라 `seo/` 디렉터리가 최상위에 오도록 패키징합니다.

## 의존성

- Toycore `2026.04.005` 이상
- `admin` 모듈

## 업데이트

새 버전 파일을 `modules/seo/`에 덮어쓴 뒤 Toycore 관리자 `/admin/updates`에서 미적용 SQL을 확인하고 실행합니다.
