# Qiskit Study Notes

이 저장소는 IBM Qiskit을 활용하여 양자 컴퓨팅을 학습한 내용을 정리한 개인 스터디용 저장소입니다.  
대표적인 양자 알고리즘을 직접 구현하고 실험하며 이해를 돕기 위해 작성되었습니다.

## 학습한 알고리즘

- `Deutsch_Jozsa.ipynb`  
  → 어떤 이진 함수가 **상수 함수인지** 또는 **균형 함수인지**를 한 번의 양자 연산으로 판별하는 알고리즘  
  (고전적으로는 최대 2ⁿ⁻¹+1번의 호출이 필요한 문제를 단 1번으로 해결)

- `Grover.ipynb`  
  → **비정렬 데이터베이스에서 원하는 항목을 더 빠르게 찾기 위한** 양자 검색 알고리즘  
  (고전적으로는 O(N)이 필요한 검색을 O(√N)으로 단축)

- `phase_estimation.ipynb`  
  → **주어진 유니터리 연산자의 고유값(위상)** 을 정밀하게 추정하는 알고리즘  
  (Shor 알고리즘이나 양자 시뮬레이션 등 다양한 알고리즘의 핵심 구성 요소로 사용됨)

## 진행 중인 작업

- `Shor's Algorithm`  
  → 현재 Qiskit 버전 이슈로 실행 오류 발생  
  → 향후 Qiskit 업데이트 및 환경 설정 후 업로드 예정

## 앞으로 추가할 계획인 알고리즘

- Quantum Fourier Transform (QFT)
- Variational Quantum Eigensolver (VQE)
- Quantum Approximate Optimization Algorithm (QAOA)
- Shor's Algorithm (정상 작동 환경에서 재구현 예정)

## 실행 환경

- Python 3.7+
- Qiskit
- Jupyter Notebook
