# 다형성 (polymorphism)
 다형성(polymorphism)이란 하나의 객체가 여러 가지 타입을 가질 수 있는 것을 의미한다. 자바에서는 이러한 다형성을 부모 클래스 타입의 참조 변수로 자식 클래스 타입의 인스턴스를 참조할 수 있도록 하여 구현하고 있다. 다형성은 상속, 추상화와 더불어 객체 지향 프로그래밍을 구성하는 중요한 특징 중 하나다.

## 참조변수의 다형성
 자바에서는 다형성을 위해 부모 클래스 타입의 참조 변수로 자식 클래스 타입의 인스턴스를 참조할 수 있도록 하고 있다. 이때 참조 변수가 사용할 수 있는 멤버의 개수가 실제 인스턴스의 멤버 개수보다 같거나 적어야 참조할 수 있다.

# 예외 (Exception)
 예외란 프로그램 실행 중 발생하는 이벤트로 프로그램 명령의 정상적인 흐름을 방해하는 것이다. 예외가 발생하게 될 경우 예외객체를 만들어 런타임 시스템에 전달한다. 예외객체는 오류발생 당시의 프로그램 상태와 오류정보가 포함되어있다. 이러한 과정을 예외 발생이라고 한다.

## 예외 처리하기

### try/catch
 try 문안의 수행할 문장들에서 예외가 발생하지 않는다면 catch문 다음의 문장들은 수행이 되지 않는다. 하지만 try 문안의 문장을 수행하는 도중에 예외가 발생하면 예외에 해당되는 catch문이 수행된다.

### finally
 finally 구문은 try 문장 수행 중 예외발생 여부에 상관없이 무조건 실행된다.

### throws
 현재 메소드에서 자신을 호출한 상위 메소드로 Exception을 발생 시킨다. 즉, throws 키워드는 사용하는 메소드를 호출한 상위 메소드에서 이러한 에러 처리에 대한 책임을 맡게 되는 것이다.

### throw
 억지로 에러를 발생시키고자 할 때 사용되기도 하고 현재 메소드의 에러를 처리한 후에 상위 메소드에 에러 정보를 줌으로써 상위 메소드에서 에러가 발생한 것을 감지할 수 있다.