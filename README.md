# version

**v.1.1** object entity와 subject entity가 바뀌지 않는 버그 수정


# Annotator 사용법

> 주의사항 : 주황색 부분만이 수정이 가능한 부분입니다. 주황색 부분 외의 다른 부분을 수정할 시 함수가 손상될 수 있습니다.

1.`Annotator_v.1.1.xlsm`파일을 다운로드 받습니다.

2. text-entity pair를 맞춘 구글 스프레드 시트(For Relation Tagging)에서 데이터를 긁어와 `Annotator.xltm` 파일의 `DataBase` sheet에 붙여넣기 해줍니다.

3. 우측 상단의 id 오른쪽 주황색 부분에 숫자를 입력해준 후, `refresh` 버튼을 누릅니다.

4. 우측 하단의 `relation`을 숫자로 입력해 준 후, 좌측에서 `sum`을 통해 관계가 맞는지 확인해줍니다.

- 만약 관계가 맞지 않다면 subject와 object의 주황색 부분을 올바르게 수정해줍니다.
- 그런 후, `remark`를 통해 에러코드를 입력해줍니다.

5. 수정이 완료되면 `save` 버튼을 눌러줍니다.
