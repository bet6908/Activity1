# Activity1
# Hello World App
namespace Activity_1._0
{
    public partial class Activity1 : Form
    {
        public Activity1()
        {
            InitializeComponent();
        }

        private void btn_Hello_Click(object sender, EventArgs e)
        {
            lbl_info.Text = "Hello World";
        }

        private void btn_change_Click(object sender, EventArgs e)
        {
            lbl_info.Text = "My name is Roberto GonzalezRamirez";
        }

        private void btn_goodBye_Click(object sender, EventArgs e)
        {
            lbl_info.Text = "...";
            MessageBox.Show("Good Bye!", "Message", MessageBoxButtons.OK, MessageBoxIcon.Information);
        }

        private void btn_instruction_Click(object sender, EventArgs e)
        {
            lbl_info.Text = "Please chack all that apply below. Thank you.";
        }
    }
}
