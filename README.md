# select-reviewer
- 글또 3기의 [지찬규님](https://github.com/JAY-Chan9yu)이 만들어주신 랜덤 리뷰어 생성 스크립트입니다

### Structure

```
├── LICENSE
├── README.md
├── memo
│   └── team.txt
├── random_reviewer.py
└── requirements.txt
```

### Run
- DB 생성
    
    ```
    python random_reviewer.py --initdb True
    ```
    
- 랜덤 리뷰어 선정

    ```
    python random_reviewer.py --initdb False
    ```
    
### ToDo
- 2주간 여러번 스크립트 실행해도 같은 결과가 나오도록 설정