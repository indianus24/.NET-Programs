Registration form of college
 Dim A, B, C As Object
        Dim F As Integer
        Dim D As String


        A = InputBox("Enter your name")
        TextBox1.Text = A
        D = InputBox("Enter your Address")
        TextBox2.Text = D
        C = InputBox("Enter your Phone")
        TextBox3.Text = C
        B = InputBox("Enter Course Name")
        TextBox4.Text = B
        F = InputBox("Enter your Total Marks")

        TextBox6.Text = F / 500 * 100

    End Sub

    Private Sub TextBox5_TextChanged(sender As Object, e As EventArgs)

    End Sub

    Private Sub Button2_Click(sender As Object, e As EventArgs) Handles Button2.Click
        TextBox1.Clear()
        TextBox2.Clear()
        TextBox3.Clear()
        TextBox4.Clear()

        TextBox6.Clear()
