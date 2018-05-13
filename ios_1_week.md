Xcode 기본	
컴퓨터 개론
Git / Markdown	
Shell / Terminal 명령어

1.프로그램 : 정적인 개념으로 컴퓨터에 저장된 실행파일들을 지칭 , 실행할수 있는 파일 

2.프로세스 : 동적인 개념으로 실행된 프로그램 , 메모리에 올라와 cpu를 할당받고 프로그램이 실행되고 있는 상태

3.메모리의 구조 : Code , Data , Stack , Heap 

4.Stack : 한 쪽 긑이 막혀있어서 자료를 한 방향으로만 쌓는 자료 구조  , FILO , LIFO  

5.Queue :  먼저 들어온 데이터는 먼저 나감 , FIFO , LILO 

6.Data Unit : bit ,(Niddle), byte , word 

7.진법 

◦2진법
◦10진법
◦16진법
◦10진수 소수점을 2진수로
◦2진수 소수점을 10진수로


#### 고정 소수점(fixed point) 방식

실수는 보통 정수부와 소수부로 나눌 수 있습니다.

따라서 실수를 표현하는 가장 간단한 방식은 소수부의 자릿수를 미리 정하여, 고정된 자릿수의 소수를 표현하는 것입니다.

 32비트 실수를 고정 소수점 방식으로 표현하면 다음과 같습니다.

 ![고정 소수점 방식](http://tcpschool.com/lectures/img_c_fixed_point.png)



하지만 이 방식은 정수부와 소수부의 자릿수가 크지 않으므로, 표현할 수 있는 범위가 매우 적다는 단점이 있습니다.



#### 부동 소수점(floating point) 방식

실수는 보통 정수부와 소수부로 나누지만, 가수부와 지수부로 나누어 표현할 수도 있습니다.

부동 소수점 방식은 이렇게 하나의 실수를 가수부와 지수부로 나누어 표현하는 방식.

 

앞서 살펴본 고정 소수점 방식은 제한된 자릿수로 인해 표현할 수 있는 범위가 매우 작습니다.

하지만 부동 소수점 방식은 다음 수식을 이용하여 매우 큰 실수까지도 표현할 수 있음.

##### 수식

±(1.가수부)×2지수부-127

 현재 대부분의 시스템에서는 부동 소수점 방식으로 실수를 표현

8.음수의 표현 ◦부호비트
◦1의 보수
◦2의 보수

9.비트 연산자 

◦&
◦|
◦^
◦~
◦<<
◦

[![비트연산자에 대한 이미지 검색결과](http://1.bp.blogspot.com/-uZnajkcHeFg/VgS5-6_rfII/AAAAAAAAAc8/bPqKwE3zUow/s1600/1c3565f454cce0d9b084f1f868e43299-731262.jpeg)](http://brickbotblog.blogspot.com/2015/09/c-bitwise-operators.html) 



10.논리 연산자 

◦&&
◦||
◦!

[![논리연산자에 대한 이미지 검색결과](http://cfile21.uf.tistory.com/image/2174FA3857EE8A8D277231)](http://webcooker.tistory.com/41) 



11.Naming Convention ◦Pascal case (upper camel case)
◦Camel case (lower camel case)
◦Hungarian case
◦Snake case
◦Kebab case (Dash case)
◦


2

1.Git :버전 관리 https://backlog.com/git-tutorial/kr/ 


2.GitHub :  버전관리 파일 저장소 https://nolboo.kim/blog/2013/10/06/github-for-beginner/

3.MarkDown :  텍스트 기반 마크업언어 , 특수기호와 문자를 이용한 매우 간단한 구조의 문법을 사용하여 웹에서도 보다 빠르게 컨텐츠를 작성하고 보다 직관적으로 인식할 수 있음                                                                              https://gist.github.com/ihoneymon/652be052a0727ad59601





1.Kernel

[![관련 이미지](https://www.serveradminz.com/blog/wp-content/uploads/2015/01/OS-Kernel.png)](https://www.serveradminz.com/blog/how-to-upgrade-to-a-new-kernel-version-without-crashing-your-server/) 



2.Shell 

- Shell Script 기초문법

https://wiki.kldp.org/wiki.php/ShellProgrammingTutorial>  

3.Command ( Linux 기본 Command)

https://www.mireene.com/webimg/linux_tip1.htm

4.VI

VI(M) 기본 문법 https://www.joinc.co.kr/w/Site/Vim/Documents/UsedVim

