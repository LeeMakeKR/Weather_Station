# 필수 참조
다음 문서만 참조하세요.
- https://github.com/LeeMakeKR/ADHD_agent_Instruction/blob/main/skills/i-have-adhd/SKILL.md

# 프로젝트 주의사항
- 기본 기준 하드웨어는 Raspberry Pi Zero 2W입니다.
- 향후 Raspberry Pi 3, Orange Pi 등 다른 보드로 확장될 수 있으므로 특정 보드 전용 구현에 종속되지 않도록 설계하세요.
- GPIO, SPI, I2C, 디스플레이 드라이버, 네트워크 설정 코드는 추상화 계층을 두고 교체 가능한 구조를 우선하세요.
- 보드 모델명 하드코딩, 단일 OS 전용 경로 고정, 특정 벤더 라이브러리 강결합을 피하세요.
