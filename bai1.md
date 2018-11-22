# Sơ ri JAVA CORE : Bài một

`Written by Minh Sacred`

## Lời mở đầu 

Đối với các bạn lần đầu tiên đến với lập trình, việc chọn ngôn ngữ ban đầu để có .... hứng thú học quả là một 
điều vô cùng quan trọng. Java là một trong những ngôn ngữ đã có tuổi đời và theo mình nghĩ là ngôn ngữ rất tốt khi mới 
tiếp xúc với lập trình. Java không quá basic, cũ kĩ như C++, không nhiều chức năng như swift hay các ngôn ngữ hiện đại 
nhưng lại chứa những base cho cả quá trình học sau này.

`Mình sẽ cùng đồng hành cùng các bạn trong chặng đường dài phía trước nhé`

## Hướng đối tượng (OOP)

Ngày còn ngồi ghế đại học, chẳng hẳn các bạn đã nghe cái cụm từ phía trên. Thật là buồn cười khi hồi đó mình còn học lại 
cái môn này. Tin mình đi, hướng đối tượng là một thuật ngữ sẽ được lặp đi lặp lại trong suốt khoảng thời gian bạn gắn bó 
với cái nghề này. Hướng đối tượng đã và đang là xu hướng của lập trình hiện đại, đã qua cái thời mà lập trình hướng 
function rồi và tất nhiên Java là một ngôn ngữ lập trình hướng đối tượng.

## Java Virtual Machine (JVM)  
Java Virtual Machine là nơi mà code java sau khi dc compile ra bytecode sẽ chạy. Nói một cách đơn giản, ngắn gọn là nơi đâu có 
JVM thì java đều có thể chạy được. Điều này dẫn tới một câu nói mang tính thương hiệu của java : Compile once run anywhere. 

## Helloworld 
Chương trình đầu tiên nào:

```
public class Main {
    public static void main(String[] args) {
        System.out.println("Hello World!");
    }
}
```
> Chả hiểu từ khi nào người ta gọi chương trình đầu tiên là HelloWorld nhể ??

Ở đây có thể nhiều bạn thắc mắc là tại sao lại có String[] args, thật ra khi chạy compile java, ta chạy lệnh : $ javac Main.java, file Main.class
sẽ dc tạo ra, sau đó ta chạy lệnh : $ java Main arg1 arg2 thì mảng args sẽ chứa 2 String là "arg1" và "arg2". Chúng ta có thể dùng args để chứa
các option chạy chương trình.

## Lớp và đối tượng


