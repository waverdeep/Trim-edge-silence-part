# Trim-edge-silence-part
음원파일 앞 뒤에 존재하는 공백을 제거하는 매뉴얼 스크립트
(주의사항) 음원의 볼륨이 너무 작거나 잡읍이 크게 들어있는 경우 제대로된 공백 제거가 진행되지 않음 

## Libraries
- multiprocessing
- pydub : AudioSegment

## parallel usage
많은 음원들의 빠른 연산 처리를 위해 병렬 연산을 진행
