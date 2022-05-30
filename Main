package lottacodr;

import javax.swing.*;

public class Main {
    public void Drawj(){
        JFrame myFrame = new JFrame("Sample");
        JPanel panel = new JPanel();
        JButton clickMe = new JButton ("Click");

        myFrame.add(panel);
        myFrame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
        panel.add(clickMe);
        myFrame.setSize(300,100);
        clickMe.addActionListener(e ->
                System.out.println("Ouch! You clicked me!"));
        myFrame.getContentPane().add(clickMe);
        myFrame.setVisible(true);
    }

    public static void main(String[] args) {
	Main myMain = new Main();
    myMain.Drawj();
    }
}
