## map

리스트에 요소를 지정된 함수로 처리해주는 함수

여러개의 데이터를 한번에 다른 형태로 변환하기 위해 사용

### map 함수 특징

- 원본 리스트를 변경하지 않고 새 리스트 생성
- map 함수는 map 타입으로 결과 리턴하기 때문에 리스트나 튜플 등올 변환

### map (함수, 반복가능한 객체)

- 실수로 저장된 모든 요소를 정수로 변환

~~~
>>> a = [1.2, 2.5, 3.7, 4.6]
>>> a = list(map(int, a)) 
>>> a
[1, 2, 3, 4]
~~~

- 모든 요소에 100을 더해서 반환

~~~
>>> a = [1, 2, 3, 4]

>>> def plus100(n):
	return n + 100
	
>>> list(map(plus100, a))
[101, 102, 103, 104]
~~~

### map 함수에 람다 식 사용

- 모든 요소에 100을 더해서 반환

~~~
>>> list(map(lambda n : n+ 100, a))
[101, 102, 103, 104]
~~~

### input().split() 과 map

- input().split()의 결과는 문자열 리스트

~~~
>>> a = input().split()
10 20 (입력)
>>> a
['10', '20']
~~~

- 그런데 map이용하면 정수형으로 바꿀 수 있다

~~~
>>> a = map(int, input().split())
10 20 (입력)
>>> a
<map object at 0x03DFB0D0> => 맵 객체 만들어짐
>>> list(a)
[10, 20]
~~~

- [10, 20]을 변수 두 개에 저장

  map이 반환하는 맵 객체가 이터레이터라서 변수 여러개에 저장하는 언패킹 가능

~~~
>>> 한 a, b = map(int, input().split())
~~~

