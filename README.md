# Array sorting by bubble method on C#
class Program{
        static void Main(string[] args) {
            Console.Write("Введите количество чисел: ");
            int a = Convert.ToInt32(Console.ReadLine());
            int[] b = new int[a];
            for (int k=0; k< a; k++){
            int h = k + 1;
            Console.Write("Введите " +h+ " число: ");
            int c = Convert.ToInt32(Console.ReadLine());
            b[k] = c;}
            for (int i=a-1; 0<i; i--) {
                for (int j = 0; j < i; j++) {
                if (b[j] > b[j+1]){
                int d = b[j]; 
                b[j] = b[j+1];
                b[j+1] = d;}}}
            for(int g=0;g<a;g++)
            Console.Write(b[g] + " ");
            Console.ReadKey();}}
