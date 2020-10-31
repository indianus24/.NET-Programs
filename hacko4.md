program for creating form in vb.net

Private Sub Button1_Click(sender As Object, e As EventArgs) Handles Button1.Click
        If ComboBox1.SelectedIndex > -1 Then
            Dim sindex As Integer
            sindex = ComboBox1.SelectedIndex
            Dim sitem As Object
            sitem = ComboBox1.SelectedItem
            ListBox1.Items.Add(sitem)
        End If
    End Sub

    Private Sub Button2_Click(sender As Object, e As EventArgs) Handles Button2.Click
        ComboBox1.Items.Clear()
        ComboBox1.Items.Add("Youtube")
        ComboBox1.Items.Add("Instagram")
        ComboBox1.Items.Add("Twitter")
        ComboBox1.Items.Add("Snapchat")
        ComboBox1.Items.Add("Facebook")
        ComboBox1.Text = "Select from..."
    End Sub
