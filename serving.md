## paddleserving

# 1. Serving Framework 지정
## 1-1) paddleserving
cudatoolkit=11.2
(여기)[https://github.com/PaddlePaddle/Serving/blob/v0.8.3/doc/Latest_Packages_CN.md]에서 알맞는 .whl 파일 설치

(2023/12/08)
- paddle_serving_server_gpu 빌드 중에 `grpcio` 빌드 에러 발생

## 1-2) Triton Inference Server
1-2-1) paddleocr 모델 onnx 변환 (paddle2onnx)
1-2-2) 전처리, 후처리 로직 적용
