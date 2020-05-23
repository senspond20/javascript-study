## 변수 

+ 변수는, 바뀔수 있는 값을 말한다. 
+ 한번 값을 선언하고 나서 바꿀 수 있다.

    ```javascript
        let value = 1;
        console.log(value);
        value = 2;
        console.log(value);
    ```
## 상수
+ 상수는, 한번 선언하고 값이 바뀌지 않는 값을 의미
+ 값이 고정적.

    ```
    const a = 1;
    a = 2;
    ```
    ==> 오류발생

## var, let, const 차이점

+ https://velog.io/@bathingape/JavaScript-var-let-const-%EC%B0%A8%EC%9D%B4%EC%A0%90

+  ES6 이후 기존의 var은 사용하지 않는다.


    ```javascript
    let value = 1;
    let value = 2;
    ```
    ==> 오류발생

    ```javascript
    var value = 1;
    var value = 2;
    ```
    ==> 오류발생하지 않음


## 데이터 타입
+ 숫자
    ```javascript
    let a = 1;
    const b = 2;
    ```
+ 문자열
    + 큰 따옴표,작은따옴표 둘다 사용가능
    ```javascript
    let text ='hello';
    let name = "헬로우 자바스크립트";
    ```
+ 참/거짓(Boolean)

    ```javascript
    let good = true;
    good = false;
    ```

+  null 과 undefined
    +  null : 값이 비어있다.
    +  undefined : 아직 값이 설정되지 않았다.

    ```javascript
    let somthing = null;
    somthing = undefined;
    ```

    ```javascript
    let cirm;
    console.log(cirm);   
    //  result : undefind;
    ```

# 연산자

※ 연산순서 알고 가기

## 대입 연산자

+ 
    ```javascript
    let value = 1; // 변수 선언,변수 초기화
    value = 2; // 대입 연산자
    ```

## 산술 연산자

+ 더하기/빼기/곱하기/나누기


    ```javascript
    a = 3;
    a++;              
    console.log(--a); // 4 
    console.log(a++); // 3
    console.lgo(a);   // 4
    ```


## 논리 연산자

+  ```javascript
    let value = true;
    value = false;

    // NOT !

    // AMD &&

    // OR !!

    const a = true && false;
    console.log(a);

    ```

## 비교 연산자

+   ```javascript
    const a = 10;
    const b = 15;
    const c = 15;

    console.log(a < b); // true
    console.log(b > a); // true
    console.log(b >= c); // true
    console.log(a <= c); // true
    console.log(b < c); // false
    ```

+  === VS == / !== VS == 차이 고 넘어가기
    +  == , != 는 타입(TYPE) 검사까지는 하지 않는다.
    +  ===, !== 는 값과 타입검사까지 한다.

+  ex1)
    
     ```javascript
    const a = 1;
    const b = "1";
    const equals = a == b;
    console.log(equals);
    // true
    ```

    ```javascript
    const a = 1;
    const b = "1";
    const equals = a === b;
    console.log(equals);
    // flase
    ```

+ ex2)
  
    ```javascript
    const a = 0;
    const b = false;
    const equals = a == b;
    console.log(equals);
    // true
    ```    

   ```javascript
    const a = 0;
    const b = false;
    const equals = a != b;
    console.log(equals);
    // false
    ```

   ```javascript
    const a = 0;
    const b = false;
    const equals = a !== b;
    console.log(equals);
    // true
    ```    

+ ex3)
  
    ```javascript
    const a = 1;
    const b = "1";
    const equals = a === b;
    console.log(equals);
    // flase
    ```

    ```javascript
    const a = null;
    const b = undefined;
    const equals = a == b;
    console.log(equals);
    // true
    ```

    ```javascript
    const a = null;
    const b = undefined;
    const equals = a === b;
    console.log(equals);
    // flase
    ```
