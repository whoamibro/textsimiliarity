"텍스트 기반 상담시스템의 효율성 제고를 위한 합성곱신경망을 이용한 자동답변추천 시스템"의 성능비교에 사용되는 알고리즘들 구현 

2017 한글 및 한국어 정보처리 학술대회 논문집에 투고

MLAlgotithms (텍스트 유사도를 계산하는 함수들)
    - pearson coefficient
    - cosine coefficient
    - levenshtein distance
    - tanimoto
    - jaccard

문장 => onehot vector 변환하여 연산하였음

levenshtein distance는 본래 단어 간 비교를 위해 사용되는 알고리즘이었으나 문장을 onehot vector로 처리하여 계산함으로써
문장 간 비교로 알고리즘 적용이 가능했다. 하지만 성능면에서 다른 알고리즘들에 비하여 연산속도가 현저하게 느려 levenshtein dis
tance는 문장 간 비교연산으로 사용하지 않을것을 추천한다.
