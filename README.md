class Method1
{
		public static String BuatDaftarIsi(String Judul1Bab,int halaman)
		{
			String str=Judul1Bab;
			for(int i=str.length();i<70;i++)
			str=str+".";
			str=str+" "+halaman;
			return str;
		}
		public static void main (String[]args)
		{
			System.out.println("");
			System.out.println("");
			System.out.println("\t\t\t\tDAFTAR ISI");
			System.out.println("");
			System.out.println("");
			System.out.println("\t\t\t\t\t\t\t\t   halaman");
			String Bab1=BuatDaftarIsi("Bab 1: Pengantar Bpro",2);
			System.out.println(Bab1);
			String Bab2=BuatDaftarIsi("Bab 2: Basic Java Program",22);
			System.out.println(Bab2);
			String Bab3=BuatDaftarIsi("Bab 3: pengertian Java",44);
			System.out.println(Bab3);
			String Bab4=BuatDaftarIsi("Bab 4: contoh-contoh java",66);
			System.out.println(Bab4);
			String Bab5=BuatDaftarIsi("Bab 5: cara belajar java",88);
			System.out.println(Bab5);
			String Bab6=BuatDaftarIsi("Bab 6: kesimpulan",100);
			System.out.println(Bab6);
			String Bab7=BuatDaftarIsi("Bab 7: saran belajar java",102);
			System.out.println(Bab7);
			String Bab8=BuatDaftarIsi("Bab 8: java pustaka",104);
			System.out.println(Bab8);
		}
}
