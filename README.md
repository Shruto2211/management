# management

Frame 1
//for check button

 // import javax.swing.JOptionPane;
        int num;
        num=Integer.parseInt(jTextField1.getText());
        if (num>10)
        JOptionPane.showMessageDialog(null, "enter a valid table num");
        else 
            JOptionPane.showMessageDialog(null,"please proceed");
        
//for next page
new NewJFrame().setVisible(true);
        this.setVisible(false);







Frame2
//for all comboboxes
double NONE = 0.00;
double Corn = 75.00;
double Paneer_Sticks = 90.00;
double Papad = 90.00;
double French_Fries = 120.00;
double Spring_Rolls = 180.00;
double Veg_Bullets = 200.00;
double Chicken_Wings = 250.00;

if(jComboBox1.getSelectedItem().equals("NONE"))
{
String cNONE = String.format("%.2f",NONE);
jLabelstr.setText(cNONE);
 }


if(jComboBox1.getSelectedItem().equals("Corn"))
{
String cCorn = String.format("%.2f",Corn);
jLabelstr.setText(cCorn);
 }


if(jComboBox1.getSelectedItem().equals("Paneer Sticks"))
{
String cPaneer_Sticks = String.format(" %.2f",Paneer_Sticks);
jLabelstr.setText(cPaneer_Sticks);
}

if(jComboBox1.getSelectedItem().equals("Papad"))
{
String cPapad = String.format("%.2f",Papad);
jLabelstr.setText(cPapad);
}

if(jComboBox1.getSelectedItem().equals("French Fries"))
{
String cFrench_Fries = String.format("%.2f",French_Fries);
jLabelstr.setText(cFrench_Fries);
}

if(jComboBox1.getSelectedItem().equals("Spring Rolls"))
{
String cSpring_Rolls = String.format("%.2f",Spring_Rolls);
jLabelstr.setText(cSpring_Rolls);
}


if(jComboBox1.getSelectedItem().equals("Veg Bullets"))
{
String cVeg_Bullets = String.format("%.2f",Veg_Bullets);
jLabelstr.setText(cVeg_Bullets);
}

