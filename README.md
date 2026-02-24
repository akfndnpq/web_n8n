# n8n (Docker Compose)

Docker Compose로 n8n을 실행하는 구성입니다.  
SQLite 기반으로 동작하며, 데이터는 Docker Volume에 영구 저장됩니다.

## Requirements

- Docker
- Docker Compose

## Files

- `docker-compose.yml.example` : n8n 서비스 정의 예시
- `.env.example` : 환경변수 예시

## Setup

### 1) 파일 준비

```bash
cp docker-compose.yml.example docker-compose.yml
cp .env.example .env