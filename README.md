# STUDENT
package xyz;
class FYBCS {
	String Studentname =  "Ishwari Shinde";
	int Rollnumber  = 11;
	String Studentclass = "FYBCS";
	String Studentaddress = "Sangamner";
	int Studentmarkmath = 78;
	int Studentmarksenglish = 82;
	int markelectronic = 67;
	int Studentabcid = 23445;
	void StudentInfo(){
		System.out.println("CLASS FYBCS");
		System.out.println("Student Name =" + Studentname);
		System.out.println("Student Roll Number =" + Rollnumber);
		System.out.println("Student class  =" + Studentclass);
		System.out.println("Student address =" + Studentaddress);
		System.out.println("Student Math marks =" + Studentmarkmath);
		System.out.println("Student English marks =" + Studentmarksenglish);
		System.out.println("Student Electronic marks=" + markelectronic);
		System.out.println("Student abc id =" + Studentabcid);
		
	}
}
class SYBCS{
	String Studentname =  "Shruti Wakchaure";
	int Rollnumber  = 101;
	String Studentclass = "SYBCS";
	String Studentaddress = "Akole";
	int Studentmarkmath = 67;
	int Studentmarksenglish = 98;
	int markelectronic = 67;
	Long Studentabcid = 23445456l;
	void StudentInfo(){
		System.out.println("CLASS SYBCS");
		System.out.println("Student Name =" + Studentname);
		System.out.println("Student Roll Number =" + Rollnumber);
		System.out.println("Student class  =" + Studentclass);
		System.out.println("Student address =" + Studentaddress);
		System.out.println("Student Math marks =" + Studentmarkmath);
		System.out.println("Student English marks =" + Studentmarksenglish);
		System.out.println("Student Electronic marks=" + markelectronic);
		System.out.println("Student abc id =" + Studentabcid);
		
	}
	
}
class TYBCS{
	String Studentname =  "Sayli Satpute";
	int Rollnumber  = 23;
	String Studentclass = "TYBCS";
	String Studentaddress = "Ganore";
	int Studentmarkmath = 82;
	int Studentmarksenglish = 90;
	int markelectronic = 67;
	int Studentabcid = 456;
	void StudentInfo(){
		System.out.println("CLASS TYBCS");
		System.out.println("Student Name =" + Studentname);
		System.out.println("Student Roll Number =" + Rollnumber);
		System.out.println("Student class  =" + Studentclass);
		System.out.println("Student address =" + Studentaddress);
		System.out.println("Student Math marks =" + Studentmarkmath);
		System.out.println("Student English marks =" + Studentmarksenglish);
		System.out.println("Student Electronic marks=" + markelectronic);
		System.out.println("Student abc id =" + Studentabcid);
		
	}
}

public class student {

	public static void main(String[] args) {
		FYBCS f1 = new FYBCS();
		SYBCS s1 = new SYBCS();
		TYBCS t1 = new TYBCS();
		f1.StudentInfo();
		s1.StudentInfo();
		t1.StudentInfo();
		// TODO Auto-generated method stub

	}

}
