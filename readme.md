namespace DemoApplication
{  
	public partial class Demo  System.Web.UI.Page  
    {  
	  protected void Page_Load(object sender, EventArgs e)  
	  {  
		string connetionString;
		SqlConnection cnn;
            
		connetionString = @"Data Source=WIN-50GP30FGO75;Initial Catalog=Demodb ;User ID=sa;Password=demol23";
			
		cnn = new SqlConnection(connetionString);
			
		cnn.Open();  
			
		Response.Write("Connection MAde");    
		conn.Close();  
			
	  }
	}
}
