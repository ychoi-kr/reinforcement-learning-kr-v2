# 7장 아타리 브레이크아웃 예제 실습 환경 구성 방법

1. gym 설치

    ```
    conda install -c conda-forge gym=0.19.0
    ```

2. atari_py 설치

    ```
    pip install atari_py
	````

3. http://www.atarimania.com/roms/Roms.rar 다운로드

4. 압축 풀기

5. 압축을 푼 폴더에서 ROM 가져오기

    ```
    python -m atari_py.import_roms <ROM 폴더명>
	````