# S-n-f-Nedir-Instance-Field-Property
using System;

namespace Sınıflar
{
    internal class Program
    {
        static void Main(string[] args)
        {
            // Sınıf Nedir ? Instance, Field, Property
            // Söz Dizimi
            // class SınıfAdi
            // {
            // [Erişim belirleyici] [Veri Tipi] ÖzellikAdi; // Property (Özellikler)
            //[Erişim Belirleyici] [Geri Dönüş Tipi] MetotAdi)([Parametre Listesi])
            // {
            // Metot Komutları
            // }
            //}
            // Erişim Belirleyiciler
            //* Public:Her yerden erişilebilir.
            //*Private:Sadece tanımlandığı sınıf içerisinden erişilebilir.

            //*Internal:Sadece bulunduğu proje içerisinden erişilebilir.

            //*Protected:Sadece tanımlandığı sınıfta ya da o sınıfın miras alana sınıflarından erişilebilir.

            Calısan calısan1 = new Calısan(); // Çalışan sınıfının bir örneğini new ile yaptık.
            calısan1.Ad = "Rabia";// Calısan birinin bilgilerini tanımaldık.
            calısan1.SoyAD = "Çakmak";
            calısan1.No = 12121214;
            calısan1.Departman = "Bilişim";

            calısan1.CalısanBilgileri(); // Ekrana yazdırmak için.
        }
  
    }
    class Calısan
    {
        public string Ad;// Calışanın özelliklerini belirledik.
        public string SoyAD;// Özellik
        public int No;// özellik
        public string Departman;//Özellik

        public  void CalısanBilgileri()// Metot yazdık. Özellikleri ekranda görmek için. Void Kullandık geri dönüş yapılmayacağı için.
        {
            Console.WriteLine("Çalışan Adı:{0}", Ad);// Ekrana yazdırıyoruz.
            Console.WriteLine("Çalışan SoyAdı:{0}", SoyAD);
            Console.WriteLine("Çalışan No:{0}", No);
            Console.WriteLine("Çalışan Departman:{0}",Departman);    
        }
        

    }
}
