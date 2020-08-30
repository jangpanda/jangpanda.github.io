# 삽입정렬

### 특징 : 

### 원리

### 성능 : O(n^2)

### 예제 : 

```java

void insertionSort(int[] arr) {

   for(int i=1; i<arr.length; i++){

      // 순회하기전 현재 값과 인덱스를 임시 변수에 저장
      int temp = arr[i];
      int aux = i - 1;

      while(aux >= 0 && arr[aux] > temp) {
         arr[aux+1] = arr[aux];
         aux--;
      }
      arr[aux + 1] = temp;
   }
}
