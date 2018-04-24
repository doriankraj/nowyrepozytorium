# nowyrepozytorium
nowybranch
import java.applet.Applet;
=======
import java.applet.Applet zmiana w drugiej linijce;
import java.awt.BorderLayout;    to już zmieniam i znowu zmieniam
import java.awt.Button;
import java.awt.Color;
import java.awt.Event;
import java.awt.Graphics;
import java.awt.GridLayout;
import java.awt.Label;
import java.awt.Panel;
import java.awt.TextField;
 
public class Gwiazda extends Applet 
{
    int bok;
    Label Bok = new Label("Bok: ");
    TextField Bokt = new TextField(5);
    Button wykonaj = new Button("Wykonaj");
     
    public void init(){
        setBackground(new Color(100,200,100));
        Panel panel = new Panel();
        panel.setLayout(new GridLayout(3, 1));
        panel.add(Bok);
        panel.add(Bokt);
        panel.add(wykonaj);
        setLayout(new BorderLayout());
        add(BorderLayout.NORTH, panel);
    }
    public boolean action(Event evt, Object arg) 
    {
 master
