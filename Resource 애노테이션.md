# Resource 애노테이션  
1.필드나 메서드에만 적용할 수 있다.  
2.생성자에 적용할 수 없다. 그러므로, 생성자가 하나면서 인자를 받아 초기화를 하는 경우, 초기화대상 변수선언부에 Resource 애노테이션을 직접 사용해서 의존주입해야하고, 인자를 받지 않는 생성자를 하나 추가해야함.
