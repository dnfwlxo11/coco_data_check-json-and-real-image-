# coco_data_check-json-and-real-image-  
coco 데이터셋의 json 파일 내의 이미지와 실제 존재 이미지가 쌍으로 같은지 검사  
  
Json 파일에는 이미지가 존재하지만 실제로는 이미지가 없어 에러가 발생하는 경우를 방지하기 위해 검사하는 기능을 수행  
그 반대의 경우도 가능  
  
다음과 같은 폴더 구조를 가지고 있어야함  

CVAT를 라벨링 툴로 사용하는 경우 유용함
  
parents - data(or task) - images - image file  
                        - annotations - json file  
        - data(or task) - images - image file  
                        - annotations - json file  
        - repeat ......  
  
