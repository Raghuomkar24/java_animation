import java.applet.Applet;
import java.awt.*;
import java.io.*;
public class Doremon extends Applet implements Runnable{
	int i=0;
	public void start()
	{
		Thread t=new Thread(this);
		t.start();
	}
	public void run()
	{
		while(true)
		{
			repaint();
			try
			{
				if(i==400)
				{
					wait();
				}
				i=i+10;
				Thread.sleep(100);
			}
			catch(InterruptedException e){
		}
	}
	}
	public void paint(Graphics g)
	{
		this.setSize(1200, 500);
		g.drawString("Happy Ganesh Chaturti", 100, 1000);
		setBackground(Color.orange);
		g.setColor(Color.cyan);
		g.fillOval(i+500, 100, 150, 160);
		g.setColor(Color.white);
		g.fillOval(i+510, 120, 130, 140);
		g.setColor(Color.red);
		g.fillOval(i+568, 133, 15, 15);
		g.setColor(Color.white);
		g.fillOval(i+569, 137, 7,7);
		g.setColor(Color.black);
		g.drawOval(i+550, 110, 25, 30);
		g.setColor(Color.black);
		g.fillOval(i+562, 122, 10, 13);
		g.setColor(Color.white);
		g.fillOval(i+580, 128, 5, 5);
		
		g.setColor(Color.black);
		g.drawOval(i+574, 110, 25, 30);
		g.setColor(Color.black);
		g.fillOval(i+568, 122, 10, 13);
		g.drawLine(i+575, 175, i+575, 148);
		g.setColor(Color.white);
		g.fillOval(i+580, 128, 5, 5);
		
		g.setColor(Color.black);
		g.drawArc(i+512, 150, 80, 30, 130, 150);
		g.setColor(Color.black);
		g.drawArc(i+577, 150, 58, 28, 260, 160);
		
		g.setColor(Color.red);
		g.fillArc(i+540, 148,65,70,170,200);
		g.setColor(Color.orange);
		g.fillOval(i+558, 200, 33, 20);
		g.setColor(Color.black);
		g.drawLine(i+560, 150, i+510, 140);
		g.drawLine(i+560, 160, i+510, 160);
		g.drawLine(i+560, 170, i+510, 180);
		g.drawLine(i+640, 140, i+590, 150);
		g.drawLine(i+640, 160, i+590, 160);
		g.drawLine(i+640, 180, i+590, 170);
		g.setColor(Color.cyan);
		g.fillRoundRect(i+510, 255, 120, 130, 40, 40);
		g.setColor(Color.white);
		g.fillOval(i+520, 230, 100, 120);
		g.setColor(Color.red);
		g.fillOval(i+529, 248, 80, 8);
		g.setColor(Color.yellow);
		g.fillOval(i+557, 253, 30, 30);
		g.setColor(Color.cyan);
		g.drawLine(i+520, 257, i+450,300);
		g.drawLine(i+520, 258, i+450,301);
		g.drawLine(i+520, 259, i+450,302);
		g.drawLine(i+520, 260, i+450,303);
		g.drawLine(i+520, 261, i+450,304);
		g.drawLine(i+520, 262, i+450,305);
		g.drawLine(i+520, 263, i+450,306);
		g.drawLine(i+520, 264, i+450,307);
		g.drawLine(i+520, 265, i+450,308);
		g.drawLine(i+520, 266, i+450,309);
		g.drawLine(i+520, 267, i+450,310);
		g.drawLine(i+520, 268, i+450,311);
		g.drawLine(i+520, 269, i+450,312);
		g.drawLine(i+520, 270, i+450,313);
		g.drawLine(i+520, 271, i+450,314);
		g.drawLine(i+520, 272, i+450,315);
		g.drawLine(i+520, 273, i+450,316);
		g.drawLine(i+520, 274, i+450,317);
		g.drawLine(i+520, 275, i+450,318);
		g.drawLine(i+520, 276, i+450,319);
		g.drawLine(i+520, 277, i+450,320);
		g.setColor(Color.white);
		g.fillOval(i+435, 295, 26, 35);
		g.setColor(Color.cyan);
		g.drawLine(i+700, 210, i+621,257);
		g.drawLine(i+700, 211, i+621,258);
		g.drawLine(i+700, 212, i+621,259);
		g.drawLine(i+700, 213, i+621,260);
		g.drawLine(i+700, 214, i+621,261);
		g.drawLine(i+700, 215, i+621,262);
		g.drawLine(i+700, 216, i+621,263);
		g.drawLine(i+700, 217, i+621,264);
		g.drawLine(i+700, 218, i+621,265);
		g.drawLine(i+700, 219, i+621,266);
		g.drawLine(i+700, 220, i+621,267);
		g.drawLine(i+700, 221, i+621,268);
		g.drawLine(i+700, 222, i+621,269);
		g.drawLine(i+700, 223, i+621,270);
		g.drawLine(i+700, 224, i+621,271);
		g.drawLine(i+700, 225, i+621,272);
		g.drawLine(i+700, 226, i+621,273);
		g.drawLine(i+700, 227, i+621,274);
		g.drawLine(i+700, 228, i+621,275);
		g.drawLine(i+700, 229, i+621,276);
		g.drawLine(i+700, 224, i+621,271);
		g.setColor(Color.white);
		g.fillOval(i+680, 208, 26, 35);
		g.setColor(Color.black);
		g.drawArc(i+555,260, 50, 20, 80,80);
		g.drawArc(i+555,263, 50, 20, 80,80);
		g.setColor(Color.red);
		g.fillOval(i+570, 267, 7, 7);
		g.setColor(Color.black);
		g.drawArc(i+570,272, 5, 25, 5, 70);
		g.drawLine(i+540, 288, i+605, 290);
		
		g.setColor(Color.orange);
		g.fillArc(i+540, 337,60,50,250,50);
		
		g.setColor(Color.white);
		g.fillOval(i+510, 375, 50,30);
		g.fillOval(i+580, 375, 50,30);
		
	}
}
