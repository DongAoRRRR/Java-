public class ScoreInformation {
    private String stunumber;
    private String name;
    private double mathematicsscore;
    private double englishiscore;
    private double networkscore;
    private double databasescore;
    private double softwarescore;
    //定义 get（）（读取变量信息）和 set（）（设置变量信息）的方法
    public void setStunumber(String stunumber) {
        this.stunumber=stunumber;
    }
    public String getStunumber() {
        return stunumber;
    }
    public void setName(String name) {
        this.name=name;
    }
    public String getName() {
        return name;
    }
    public void setMathematicsscore(double mathematicsscore) {
        this.mathematicsscore=mathematicsscore;
    }
    public double getMathematicsscore() {
        return mathematicsscore;
    }
    public void setEnglishiscore(double englishiscore) {
        this.englishiscore=englishiscore;
    }
    public double getEnglishiscore() {
        return englishiscore;
    }
    public void setNetworkscore(double networkscore) {
        this.networkscore=networkscore;
    }
    public double getNetworkscore() {
        return networkscore;
    }
    public void setDatabasescore(double databasescore) {
        this.databasescore=databasescore;
    }
    public double getDatabasescore() {
        return databasescore;
    }
    public void setSoftwarescore(double softwarescore) {
        this.softwarescore=softwarescore;
    }
    public double getSoftwarescore() {
        return softwarescore;
    }
    public ScoreInformation(String stunumber,String name,double mathematicsscore,double englishiscore,double networkscore,double databasescore,double softwarescore) {
        this.stunumber=stunumber;
        this.name=name;
        this.mathematicsscore=mathematicsscore;
        this.englishiscore=englishiscore;
        this.networkscore=networkscore;
        this.databasescore=databasescore;
        this.softwarescore=softwarescore;
    }
//    public static void main(String[] args) {
//        ScoreInformation text=new ScoreInformation("20183566","董奥",1,2,3,4,5);
//        System.out.println(text.getDatabasescore());
//        System.out.println(text.getEnglishiscore());
//        System.out.println(text.getMathematicsscore());
//        System.out.println(text.getStunumber());
//    }
}



import java.util.Scanner;
public class ScoreManagement {
    static ScoreInformation Score1=new ScoreInformation("20180001","姓名1",0,0,0,0,0);
    static ScoreInformation Score2=new ScoreInformation("20180002","姓名2",0,0,0,0,0);
    static ScoreInformation Score3=new ScoreInformation("20180003","姓名3",0,0,0,0,0);
    static ScoreInformation Score4=new ScoreInformation("20180004","姓名4",0,0,0,0,0);
    static ScoreInformation Score5=new ScoreInformation("20180005","姓名5",0,0,0,0,0);
    static Scanner in=new Scanner(System.in);
    public static void menu(){
        System.out.println("***********************************************************");
        System.out.println("                                      石家庄铁道大学软件工程系");
        System.out.println("                                      学生学籍管理系统 2019 版");
        System.out.println("***********************************************************");
        System.out.println("                1、 学生考试成绩录入");
        System.out.println("                2、 学生考试成绩修改");
        System.out.println("                3、 计算学生成绩绩点");
        System.out.println("                4、退出学籍管理系统");
        System.out.println("**********************************************************");
        System.out.print("请输入：");
    }
    public static void totalMenu() {//总菜单
        int anss=0;
        while(anss!=4) {
            menu();
            anss=in.nextInt();
            if(anss==1) addScore();
            else if(anss==2) modifyScore();
            else if(anss==3) caculateScore();
            else if(anss==4);
            else 
                System.out.println("该选项不存在");
        }
        System.out.println("退出成功");
        System.out.println("***********************************************************\r\n" + 
                "谢谢使用石家庄铁道大学软件工程系学生学籍管理系统 2019 版\r\n" + 
                "制作人：董奥\r\n" + 
                "***********************************************************");
    }
    public static void addMenu() {
        System.out.println("***********************************************************");
        System.out.println("              石家庄铁道大学软件工程系学生学籍管理系统 2019 版");
        System.out.println("                                    学生考试成绩录入");
        System.out.println("***********************************************************");
        System.out.print("                                    请输入学生学号：");
    }
    public static void addInterface(ScoreInformation h) {//录入成绩界面
        System.out.println("***********************************************************");
        System.out.println("                  石家庄铁道大学软件工程系学生学籍管理系统 2019 版");
        System.out.println("                                          学生考试成绩录入界面");
        System.out.println("***********************************************************");
        System.out.println("学生学号："+h.getStunumber());
        System.out.println("学生姓名："+h.getName());
        System.out.println("请输入高等数学成绩：");
        double ans1=in.nextDouble();
        System.out.println("请输入大学英语成绩：");
        double ans2=in.nextDouble();
        System.out.println("请输入计算机网络成绩：");
        double ans3=in.nextDouble();
        System.out.println("请输入数据库成绩：");        
        double ans4=in.nextDouble();
        System.out.println("请输入软件工程成绩：");
        double ans5=in.nextDouble();    
        System.out.println("***********************************************************");
        System.out.println("                  石家庄铁道大学软件工程系学生学籍管理系统 2019 版");
        System.out.println("                                          学生考试成绩录入界面");
        System.out.println("***********************************************************");
        System.out.println("学生学号："+h.getStunumber());
        System.out.println("学生姓名："+h.getName());
        System.out.println("高等数学成绩："+ans1);
        System.out.println("大学英语成绩："+ans2);
        System.out.println("计算机网络成绩："+ans3);
        System.out.println("数据库成绩："+ans4);
        System.out.println("软件工程成绩："+ans5);
        System.out.print("该学生成绩已录入完毕，是否提交（Y/N）");
        String a=in.next();
        char s=a.charAt(0);
        if(s=='Y'||s=='y') {
            h.setMathematicsscore(ans1);        
            h.setEnglishiscore(ans2);    
            h.setNetworkscore(ans3);
            h.setDatabasescore(ans4);
            h.setSoftwarescore(ans5);
        }
        else
            addScore();
    }
    public static void addScore() {//录入成绩
        boolean flag=true;
        while(flag) {
            addMenu();
            String ans=in.next();//将输入的学号存入ans中
            if(ans.equals(Score1.getStunumber())) {//检查ans与那个Score相等
                addInterface(Score1);
                flag=false;
            }
            else if(ans.equals(Score2.getStunumber())) {
                addInterface(Score2);
                flag=false;
            }
            else if(ans.equals(Score3.getStunumber())) {
                addInterface(Score3);
                flag=false;
            }
            else if(ans.equals(Score4.getStunumber())) {
                addInterface(Score4);
                flag=false;
            }
            else if(ans.equals(Score5.getStunumber())) {
                addInterface(Score5);
                flag=false;
            }
            else 
                System.out.println("该学号不存在1");
        }
    }
    public static void modifyMenu() {
        System.out.print("***********************************************************\r\n" + 
                "                        石家庄铁道大学软件工程系学生学籍管理系统 2019 版\r\n" + 
                "                                              学生考试成绩修改界面\r\n" + 
                "***********************************************************\r\n" + 
                "请输入学生学号：");        
    }
    public static void modifyInterface(ScoreInformation h) {
        System.out.print("***********************************************************\r\n" + 
                "                        石家庄铁道大学软件工程系学生学籍管理系统 2019 版\r\n" + 
                "                                             学生考试成绩录入\r\n" + 
                "***********************************************************\r\n" + 
                "学生学号："+h.getStunumber()+"\r\n" + 
                "学生姓名："+h.getName()+"\r\n" + 
                "1、高等数学成绩："+h.getMathematicsscore()+"\r\n" + 
                "2、大学英语成绩："+h.getEnglishiscore()+"\r\n" + 
                "3、计算机网络成绩："+h.getNetworkscore()+"\r\n" + 
                "4、数据库成绩："+h.getDatabasescore()+"\r\n" + 
                "5、软件工程成绩："+h.getSoftwarescore()+"\r\n" + 
                "**********************************************************");
        System.out.println("请选择修改内容：");
        int ans=in.nextInt();//记录序号
        double cmp;//记录接下来输入的成绩
        String s;
        char a;
        switch(ans) {
        case 1:
            System.out.print("***********************************************************\r\n" + 
                    "                         石家庄铁道大学软件工程系学生学籍管理系统 2019 版\r\n" + 
                    "                                              学生考试成绩录入界面\r\n" + 
                    "***********************************************************\r\n" + 
                    "学生学号："+h.getStunumber()+"\r\n" + 
                    "学生姓名："+h.getName()+"\r\n" + 
                    "请输入修改后高等数学成绩：");
            cmp=in.nextDouble();
            System.out.println("***********************************************************\r\n" + 
                    "                         石家庄铁道大学软件工程系学生学籍管理系统 2019 版\r\n" + 
                    "                                              学生考试成绩录入\r\n" + 
                    "***********************************************************\r\n" + 
                    "学生学号："+h.getStunumber()+"\r\n" + 
                    "学生姓名："+h.getName()+"\r\n" + 
                    "1、高等数学成绩："+cmp+"\r\n" + 
                    "2、大学英语成绩："+h.getEnglishiscore()+"\r\n" + 
                    "3、计算机网络成绩："+h.getNetworkscore()+"\r\n" + 
                    "4、数据库成绩："+h.getDatabasescore()+"\r\n" + 
                    "5、软件工程成绩："+h.getSoftwarescore()+"\r\n" + 
                    "该学生成绩已修改完毕，是否提交（Y/N）\r\n" + 
                    "**********************************************************");
            s=in.next();
            a=s.charAt(0);
            if(a=='Y'||a=='y') h.setMathematicsscore(cmp);
            break;
        case 2:
            System.out.print("***********************************************************\r\n" + 
                    "                           石家庄铁道大学软件工程系学生学籍管理系统 2019 版\r\n" + 
                    "                                              学生考试成绩录入界面\r\n" + 
                    "*************1**********************************************\r\n" + 
                    "学生学号："+h.getStunumber()+"\r\n" + 
                    "学生姓名："+h.getName()+"\r\n" + 
                    "请输入修改后大学英语成绩：");
            cmp=in.nextDouble();
            System.out.println("***********************************************************\r\n" + 
                    "                           石家庄铁道大学软件工程系学生学籍管理系统 2019 版\r\n" + 
                    "                                              学生考试成绩录入\r\n" + 
                    "***********************************************************\r\n" + 
                    "学生学号："+h.getStunumber()+"\r\n" + 
                    "学生姓名："+h.getName()+"\r\n" + 
                    "1、高等数学成绩："+h.getMathematicsscore()+"\r\n" + 
                    "2、大学英语成绩："+cmp+"\r\n" + 
                    "3、计算机网络成绩："+h.getNetworkscore()+"\r\n" + 
                    "4、数据库成绩："+h.getDatabasescore()+"\r\n" + 
                    "5、软件工程成绩："+h.getSoftwarescore()+"\r\n" + 
                    "该学生成绩已修改完毕，是否提交（Y/N）\r\n" + 
                    "**********************************************************");
            s=in.next();
            a=s.charAt(0);
            if(a=='Y'||a=='y') h.setEnglishiscore(cmp);
            break;
        case 3:
            System.out.print("***********************************************************\r\n" + 
                    "                          石家庄铁道大学软件工程系学生学籍管理系统 2019 版\r\n" + 
                    "                                              学生考试成绩录入界面\r\n" + 
                    "***********************************************************\r\n" + 
                    "学生学号："+h.getStunumber()+"\r\n" + 
                    "学生姓名："+h.getName()+"\r\n" + 
                    "请输入修改后计算机网络成绩：");
            cmp=in.nextDouble();
            System.out.println("***********************************************************\r\n" + 
                    "                          石家庄铁道大学软件工程系学生学籍管理系统 2019 版\r\n" + 
                    "                                              学生考试成绩录入\r\n" + 
                    "***********************************************************\r\n" + 
                    "学生学号："+h.getStunumber()+"\r\n" + 
                    "学生姓名："+h.getName()+"\r\n" + 
                    "1、高等数学成绩："+h.getMathematicsscore()+"\r\n" + 
                    "2、大学英语成绩："+h.getEnglishiscore()+"\r\n" + 
                    "3、计算机网络成绩："+cmp+"\r\n" + 
                    "4、数据库成绩："+h.getDatabasescore()+"\r\n" + 
                    "5、软件工程成绩："+h.getSoftwarescore()+"\r\n" + 
                    "该学生成绩已修改完毕，是否提交（Y/N）\r\n" + 
                    "**********************************************************");
            s=in.next();
            a=s.charAt(0);
            if(a=='Y'||a=='y') h.setNetworkscore(cmp);
            break;
        case 4:
            System.out.print("***********************************************************\r\n" + 
                    "石家庄铁道大学软件工程系学生学籍管理系统 2019 版\r\n" + 
                    "学生考试成绩录入界面\r\n" + 
                    "***********************************************************\r\n" + 
                    "学生学号："+h.getStunumber()+"\r\n" + 
                    "学生姓名："+h.getName()+"\r\n" + 
                    "请输入修改后数据库成绩：");
            cmp=in.nextDouble();
            System.out.println("***********************************************************\r\n" + 
                    "石家庄铁道大学软件工程系学生学籍管理系统 2019 版\r\n" + 
                    "学生考试成绩录入\r\n" + 
                    "***********************************************************\r\n" + 
                    "学生学号："+h.getStunumber()+"\r\n" + 
                    "学生姓名："+h.getName()+"\r\n" + 
                    "1、高等数学成绩："+h.getMathematicsscore()+"\r\n" + 
                    "2、大学英语成绩："+h.getEnglishiscore()+"\r\n" + 
                    "3、计算机网络成绩："+h.getNetworkscore()+"\r\n" + 
                    "4、数据库成绩："+cmp+"\r\n" + 
                    "5、软件工程成绩："+h.getSoftwarescore()+"\r\n" + 
                    "该学生成绩已修改完毕，是否提交（Y/N）\r\n" + 
                    "**********************************************************");
            s=in.next();
            a=s.charAt(0);
            if(a=='Y'||a=='y') h.setDatabasescore(cmp);
            break;
        case 5:
            System.out.print("***********************************************************\r\n" + 
                    "石家庄铁道大学软件工程系学生学籍管理系统 2019 版\r\n" + 
                    "学生考试成绩录入界面\r\n" + 
                    "***********************************************************\r\n" + 
                    "学生学号："+h.getStunumber()+"\r\n" + 
                    "学生姓名："+h.getName()+"\r\n" + 
                    "请输入修改后软件工程成绩：");
            cmp=in.nextDouble();
            System.out.println("***********************************************************\r\n" + 
                    "石家庄铁道大学软件工程系学生学籍管理系统 2019 版\r\n" + 
                    "学生考试成绩录入\r\n" + 
                    "***********************************************************\r\n" + 
                    "学生学号："+h.getStunumber()+"\r\n" + 
                    "学生姓名："+h.getName()+"\r\n" + 
                    "1、高等数学成绩："+h.getMathematicsscore()+"\r\n" + 
                    "2、大学英语成绩："+h.getEnglishiscore()+"\r\n" + 
                    "3、计算机网络成绩："+h.getNetworkscore()+"\r\n" + 
                    "4、数据库成绩："+h.getDatabasescore()+"\r\n" + 
                    "5、软件工程成绩："+cmp+"\r\n" + 
                    "该学生成绩已修改完毕，是否提交（Y/N）\r\n" + 
                    "**********************************************************");
            s=in.next();
            a=s.charAt(0);
            if(a=='Y'||a=='y') h.setSoftwarescore(cmp);
            break;
        default:
            System.out.println("输入序号错误");
        }
    }
    public static void modifyScore() {//修改成绩
        boolean flag=true;
        while(flag) {
            modifyMenu();
            String ans=in.next();//将输入的学号存入ans中
            if(ans.equals(Score1.getStunumber())) {
                modifyInterface(Score1);
                flag=false;
            }
            else if(ans.equals(Score2.getStunumber())) {
                modifyInterface(Score2);
                flag=false;
            }
            else if(ans.equals(Score3.getStunumber())) {
                modifyInterface(Score3);
                flag=false;
            }
            else if(ans.equals(Score4.getStunumber())) {
                modifyInterface(Score4);
                flag=false;
            }
            else if(ans.equals(Score5.getStunumber())) {
                modifyInterface(Score5);
                flag=false;
            }
            else 
                System.out.println("该学号不存在2");
        }
    }
    public static void caculateMenu() {
        System.out.println("***********************************************************\r\n" + 
                "石家庄铁道大学软件工程系学生学籍管理系统 2019 版\r\n" + 
                "学生考试成绩绩点计算界面\r\n" + 
                "***********************************************************\r\n" + 
                "请输入学生学号：");
    }
    public static void caculateInterface(ScoreInformation h) {
        double [] s=new double[5];//分别存储1--5五门学科成绩
        s[0]=h.getMathematicsscore();
        s[1]=h.getEnglishiscore();
        s[2]=h.getNetworkscore();
        s[3]=h.getDatabasescore();
        s[4]=h.getSoftwarescore();
        double[] result=new double[5];//分别存储1-5学科的绩点
        double [] credit= {4,3,4,3,2};//存储各科学分
        double sum=0;
        for (int i = 0; i < s.length; i++) {
            if(s[i]>=90) result[i]=4.0;
            else if(s[i]>=85&&s[i]<90) result[i]=3.7;
            else if(s[i]>=82&&s[i]<85) result[i]=3.3;
            else if(s[i]>=78&&s[i]<82) result[i]=3.0;
            else if(s[i]>=75&&s[i]<78) result[i]=2.7;
            else if(s[i]>=72&&s[i]<75) result[i]=2.3;
            else if(s[i]>=68&&s[i]<72) result[i]=2.0;
            else if(s[i]>=66&&s[i]<68) result[i]=1.7;
            else if(s[i]>=64&&s[i]<66) result[i]=1.5;
            else if(s[i]>=60&&s[i]<64) result[i]=1.0;
            else  result[i]=0;
            sum+=result[i]*credit[i];
        }
        sum/=5;
        boolean flag=true;
        if(sum<2)
            flag=false;
            System.out.print("***********************************************************\r\n" + 
                "石家庄铁道大学软件工程系学生学籍管理系统 2019 版\r\n" + 
                "学生考试成绩绩点计算界面\r\n" + 
                "***********************************************************\r\n" + 
                "学生学号："+h.getStunumber()+"\r\n" + 
                "学生姓名："+h.getName()+"\r\n" + 
                "1、高等数学成绩绩点："+result[0]+"\r\n" + 
                "2、大学英语成绩绩点："+result[1]+"\r\n" + 
                "3、计算机网络成绩绩点："+result[2]+"\r\n" + 
                "4、数据库成绩绩点："+result[3]+"\r\n" + 
                "5、软件工程成绩绩点："+result[4]+"\r\n" + 
                "你的平均学分绩点为：");
            System.out.println(String.format("%.2f", sum));    //计算结果保留小数点后两位
        if(flag)
                System.out.println("提示信息：你的学分绩点已达到毕业要求！");
        else
            System.out.println("你的学分绩点不满足毕业要求！");

                System.out.println("是否返回系统主界面：（Y/N）");
                String a;
                char c='2';
                while(c!='Y'&&c!='y') {
                    a=in.next();
                    c=a.charAt(0);
                }
    }
    public static void caculateScore() {//计算学分绩点
        boolean flag=true;
        while(flag) {
            caculateMenu();
            String ans=in.next();//将输入的学号存入ans中
            if(ans.equals(Score1.getStunumber())) {
                caculateInterface(Score1);
                flag=false;
            }
            else if(ans.equals(Score2.getStunumber())) {
                caculateInterface(Score2);
                flag=false;
            }
            else if(ans.equals(Score3.getStunumber())) {
                caculateInterface(Score3);
                flag=false;
            }
            else if(ans.equals(Score4.getStunumber())) {
                caculateInterface(Score4);
                flag=false;
            }
            else if(ans.equals(Score5.getStunumber())) {
                caculateInterface(Score5);
                flag=false;
            }
            else 
                System.out.println("该学号不存在3");
        }
    }
    public static void main(String[] args) {
        totalMenu();
    }
}
