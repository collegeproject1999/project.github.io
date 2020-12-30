<?php
 include('connection1.php');
 session_start();
 ?>
<!DOCTYPE html>
<html>
<head>
	<title> Exchange List</title>
	<style type="text/css">
		body{
	background-image: url("inventory-management-system-without-barcode-500x500.jpg");
  background-position: center;
  background-repeat: no-repeat;
  background-size: 400px 400px;
  background-color:#E4405F;
}

	
#full{width: 100%;
		height: auto;
	}
	#inner-full{
		width: 80%;
		height: auto;
		margin: auto; 
	}	
	#header{width: 100%;
		height: 50px;
		background-color: red;
		color:white;
	}
	#body{
		width: 100%;
		height: 400px;
	}
	#footer{
		width: 100%;
		height:60px;
		background-color: red;
	}
#form{
	width: 80%;
	height: 350px;
	background-color: red;
	color:white;
	border-radius: 10px;
}
</style>
</head>
<body>
<div id="full">
	<div id="inner-full">
		<marquee  bgcolor=red direction = "left" loop="" >
<div id="header"><h1><a href="admin-home.php" style="text-decoration: none;color: white;">INVENTORY MANAGEMENT SYSTEM</a></h1></div>
</marquee>
		<div id="body">
		<?php
		$un=$_SESSION['un'];
		if (!$un){
			header("Location:index1.php");
		}
		?>
		<h3><b>STOCK EXCHANGE REGISTRATION</b></h3>
		<center><div id="form">
			<form action="" method="post">
			<table>
				<tr>
					
					<td width="200px" height="50px">Enter Receiver's Name</td>
					<td width="200px" height="50px"><input type="text" name="fname" placeholder="Enter Receiver Name" autocomplete="off"></td>
				</tr>
				<tr>
					<td width="200px" height="50px">Enter Address</td>
					<td width="200px" height="50px"><textarea name="address" autocomplete="off"></textarea></td>
					<td width="200px" height="50px">Enter City</td>
					<td width="200px" height="50px"><input type="text" name="city" placeholder="Enter City" autocomplete="off"></td>
				</tr>
				<tr>
				<td width="200px" height="50px">Enter Age</td>
					<td width="200px" height="50px"><input type="text" name="age" placeholder="Enter Age" autocomplete="off"></td>
				     <td width="200px" height="50px">Enter E-mail</td>
					<td width="200px" height="50px"><input type="text" name="email" placeholder="Enter E-mail" autocomplete="off"></td>
				</tr>
				<tr>
					<td width="200px" height="50px">Enter Mobile No</td>
					<td width="200px" height="50px"><input type="text" name="mno" placeholder="Enter Mobile No" autocomplete="off"></td>
                   </tr>
                   <tr>
                   	<td width="200px" height="50px">Select Order</td>
					<td width="200px" height="50px">
						<select name="bgroup">
							<option>SHIRT</option>
							<option>PANT</option>
							<option>JEANS</option>
							<option>T SHIRT</option>
							<option>SHOE</option>
							<option>GIRLS SUIT</option>
							<option>CROP T-SHIRT</option>
							<option>UNDER GARMENTS</option>
							
						</select>
					</td>
					<td width="200px" height="50px">Exchange Order</td>
					<td width="200px" height="50px">
						<select name="ebgroup">
							<option>SHIRT</option>
							<option>PANT</option>
							<option>JEANS</option>
							<option>T SHIRT</option>
							<option>SHOE</option>
							<option>GIRLS SUIT</option>
							<option>CROP T-SHIRT</option>
							<option>UNDER GARMENTS</option>
							
						</select>
					</td>
                   </tr>
                   <tr>
                   	<td><input type="submit" name="sub" value="save"></td>
                   </tr>
               </table>
           </form>
           <?php
           if(isset($_POST['sub']))
           {
           	//front end data input
           
            $fname=$_POST['fname'];
            $address=$_POST['address'];
            $city=$_POST['city'];
            $age=$_POST['age'];
            $bgroup=$_POST['bgroup'];
            $mno=$_POST['mno'];
            $email=$_POST['email'];
            $ebgroup=$_POST['ebgroup'];
             //front end data input end

            //select and insert
            $q="select * from order_registration where bgroup='$bgroup'";
            $st=$db->query($q);
            $num_row=$st->fetch();
            $id=$num_row['id'];
            $name=$num_row['name'];
            $b1=$num_row['bgroup'];
            $mno=$num_row['mno'];
            $q1="INSERT INTO out_stock_b (bname, name, mno) VALUES (?,?,?)";
            $st1=$db->prepare($q1);
            $st1->execute([$b1,$name,$mno]);
            //select and insert end

            //delete code
            $q2="delete from order_registration where id='$id'";
            $st=$db->prepare($q2);
            $st->execute();
            //delete

            //exchange info insert
    $q=$db-> prepare("INSERT INTO `exchange_b` (name, fname, address, city, age, bgroup, mno,email, ebgroup) VALUES ( :name,:fname, :address, :city, :age, :bgroup,:mno,:email, :ebgroup)");
     $q->bindvalue('name',$name);
     $q->bindValue('fname',$fname);
     $q->bindValue('address',$address);
     $q->bindValue('city',$city);
     $q->bindValue('age',$age);
     $q->bindValue('bgroup',$bgroup);
      $q->bindValue('mno',$mno);
     $q->bindValue('email',$email);
      $q->bindValue('ebgroup',$ebgroup);
     
   if($q->execute())
              {
           	echo "<script>alert('Registration Successfull')</script>";
           }
           else{
           	echo "<script>alert('Registration Not Successfull')</script>";
           }
           //exchange info insert end
           }
           ?>
           </div>
       </center>
   </div>
		<div id="footer"><h4 align="center"><font color="white">Copyright@myproject&nbsp&nbsp DESIGN BY-Aishwarya Kumar, Ayush and Anurag</font></h4>
		<p align="center"><a href="logout1.php"><font color="white">LogOut</font></a></p>
		</div>
</body>
</html> 