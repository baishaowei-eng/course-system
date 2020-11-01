# java-Experiment-2
## 2020322081   白少伟
## 1. 实验内容
1. 基本要求是完成学生选课系统
2. 通过父类继承子类的方法来实现选课系统;
3. 根据Persons类中的对象和方法让字类中的学生类和老师类来继承Person类中的对象和方法。
4. 尝试通过这次的实验掌握如何通过继承父类中的方法来获取想要输出的值。
## 2. 实验设计

+ 1.设置Personner类中的对象和方法
```
        static String number;
	static String name=null;
	static String sex;
	public Personner(String number,String name,String sex) {
		this.number=number;
		this.name=name;
		this.sex=sex;
		
	}
	
	public String getNumber() {
		return number;
	}
	public void setNumber(String number) {
		this.number = number;
	}
```
 ## 3. 核心方法
 
  1. Student类和Teacher类来继承Personner类中的方法。
  
  ```
          public class Students extends Personner{
	public Students(String number, String name, String sex) {
		super(number, name, sex);	
	}
	public Students() {
		super(number, name, sex);
	}
    String classs;
	public String getClasss() {
		return classs;
	}

	public void setClasss(String classs) {
		this.classs = classs;
	}
	
}
class Teacher extends Personner{
	public Teacher(String number, String name, String sex) {
		super(number, name, sex);
	}
	public Teacher() {
		super(number, name, sex);
	}
	String  instruction;

	public String getInstruction() {
		return instruction;
	}

	public void setInstruction(String instruction) {
		this.instruction = instruction;
	}
	
}
   
	 
   ```
   
   ## 4. 实验结果截图
   
  https://github.com/baishaowei-eng/course-system/blob/main/bbc/course.png
  ## 5.框架图
   https://github.com/baishaowei-eng/course-system/blob/main/bbc/class.png
  ## 5.实验感想

  1. 通过这个实验学习到了子类如何继承父类的方法来进行操作。
  2. 学会了如何进行逻辑判断来进行选课和退课的操作。
  3. 学会了用构造方法来获取自己想要的值。
  4. 学会了如何使用toString构造方法来进行传参，并且输出相应的值。

   
     
