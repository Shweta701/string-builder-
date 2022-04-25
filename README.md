# string-builder- to short name like shweta sharma to s sharma


 static void Main(string[] args)
        {
            string str = "shweta sharma";
            string[] strarr = str.Split();
            StringBuilder sb = new StringBuilder();
            for (int i = 0; i <= str.Length - 1; i++)
            {
                sb.Append(strarr[i].Substring(0, 1).ToUpper());
                sb.Append("");
                sb.Append(strarr[strarr.Length - 1]);
                Console.WriteLine(sb);
                Console.ReadLine();
            }
        }
