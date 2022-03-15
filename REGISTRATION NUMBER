using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace REGISTRATION_NUMBER
{
    public partial class Form1 : Form
    {
        String name, regn_no;
        DateTime iDate;
        char gender;
        Boolean hostel=false;
        public Form1()
        {
            InitializeComponent();
        }

        private void Form1_Load(object sender, EventArgs e)
        {

        }

        private void richTextBox1_TextChanged(object sender, EventArgs e)
        {

        }

        private void textBox1_TextChanged(object sender, EventArgs e)
        {
            name = textBox1.Text;
        }

        private void textBox2_TextChanged(object sender, EventArgs e)
        {
            regn_no = textBox1.Text;
        }

        private void dateTimePicker1_ValueChanged(object sender, EventArgs e)
        {
            iDate = dateTimePicker1.Value;
        }

        private void radioButton1_CheckedChanged(object sender, EventArgs e)
        {
            if (radioButton1.Checked == true)
            {
                gender = 'm';
            }
        }

        private void radioButton2_CheckedChanged(object sender, EventArgs e)
        {
            if (radioButton1.Checked == true)
            {
                gender = 'f';
            }
        }

        private void comboBox1_SelectedIndexChanged(object sender, EventArgs e)
        {
            {
                if(comboBox1.SelectedIndex==0)
                {
                    listBox2.Items.Clear();
                    listBox2.Items.Add("DBS");
                    listBox2.Items.Add("DAA");
                    listBox2.Items.Add("CNP");
                }
                if(comboBox1.SelectedIndex==1)
                {
                    listBox2.Items.Clear();
                    listBox2.Items.Add("DSA");
                    listBox2.Items.Add("DAA");
                    listBox2.Items.Add("MATH");
                }
                if(comboBox1.SelectedIndex==2)
                {
                    listBox2.Items.Clear();
                    listBox2.Items.Add("ASD");
                    listBox2.Items.Add("DSD");
                    listBox2.Items.Add("EM");
                }
            }
        }

        private void checkBox1_CheckedChanged(object sender, EventArgs e)
        {
            if (checkBox1.ThreeState == true)
            {
                hostel = true;
            }
        }

        private void listBox2_SelectedIndexChanged(object sender, EventArgs e)
        {

        }
    }
}
