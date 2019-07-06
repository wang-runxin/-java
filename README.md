        import javax.swing.JFrame;
        import java.awt.*;

public class window extends JFrame{
    public window(){
        this.setTitle("窗口");
        this.setBounds(300,200,580,600);
        /*this.setSize(580,600);
        this.setLocation(300,200);*/
        this.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
        this.setVisible(true);
    }
    public static void main(String[]args){
        new window();
    }

}
