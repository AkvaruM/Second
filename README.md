# Second

public class Main {
    public static void main(String[] args) {
        Ward w1 = new Ward();
        Ward w2 = new Ward(0,"Гаврилович Владислав", true);
        WriterInfo writer1 = new WriterInfo();
        w1.Print_Name_doctor();
        w1.Print_kolvoMest();
        w1.Print_free_seats();
        w2.Print_Name_doctor();
        w2.Print_kolvoMest();
        w2.Print_free_seats();
        writer1.PrintWriterInfo(w1);
        writer1.PrintWriterInfo(w2);
    }
}
