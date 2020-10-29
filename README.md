# java-Experiment-2
## 1. 实验内容
1. 基本要求是完成学生选课系统
2. 通过父类继承子类的方法来实现选课系统;
3. 根据Persons类中的对象和方法让字类中的学生类和老师类来继承Person类中的对象和方法。
4. 尝试通过这次的实验掌握如何通过继承父类中的方法来获取想要输出的值。
## 2. 实验设计

+ 1.设置Person类中的对象和方法
```
    public class CPU {
    private  int Speed;   
    private  String name; 
    
    
   private int  HardDisk(){
      private amount;
      private price;
  }
```
 ## 3. 核心方法
 
  1. Student类和Teacher类来继承Personsl类中的方法。
  
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
   
         实列话CPU和硬盘对象来进行初始化，在通过show 方法来输出相应的内容。     

          CPU cpu=new CPU();
	  HardDisk HD= new HardDisk();
	 
   ```
   
   ## 4. 实验结果
   
   学生选课系统
Serial number is : 2020322081
Name is : baishaowei
Gerder is :boy
elective is :java
lecture teacher code is :2020322033
lecture teacher is ：阿斌
place location is :java授课老师
The course number :101
Course title :离散数学
Course plance :教学3-206号楼
sclooltime is :2020-10-29 12:11:27
lecture teacher name is :张三
------------------------------------------
学生姓名：阿斌
学生选择的课程 ：java
上课地点：301教室
上课时间：8:00
------------------------------------------
学生姓名：阿斌
你已经退课了，其重新选课


  ## 5.实验感想

  1. 通过这个实验学习到了
     public private 的不同用法
  2. 如何通过构造方法来获取相应的值
  3. 学会了如何导出项目

   
     
