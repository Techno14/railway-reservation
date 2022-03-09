# railway-reservation
import java.io.*;
class Railway
{
  public void Clear()
  {
     for(int i=1;i<=30;i++)
        System.out.println(" ");
  }
  public void Show() throws InterruptedException
  {
    for(long i=1;i<=8000000;i++)
    {
       if(i%100000==0)
          System.out.print("�");
    }
    System.out.print("\n\n\n\n");
    System.out.println("\n\t\t\tvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvvv");
    System.out.println("\t\t\t|             WELCOME              |");
    System.out.println("\t\t\t|               T O                |");
    System.out.println("\t\t\t|           My  Project            |");
    System.out.println("\t\t\t|               O F                |");
    System.out.println("\t\t\t|    RAILWAY RESERVATION SYSTEM    |");
    System.out.println("\t\t\t^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^");
    System.out.println("\n\n\n");
    System.out.print("\t\t\t        COMPILING");
    for(long i=1;i<=8000000;i++)
      if(i%1000000==0)
         System.out.print(".");
    System.out.println("\n");
    System.out.print("\t\t\t        BE SEATED");
    Thread.sleep(3000);
    for(long i=1;i<=8000000;i++)
       if(i%1000000==0)
         System.out.print("!");
    System.out.print("\n\n\n\n");
    for(long i=1;i<=8000000;i++)
    {
       if(i%100000==0)
          System.out.print("�");
    }
  }
  void sow()throws InterruptedException
  {
    Clear();
    System.out.println("\t\t\t  ");
    System.out.println("\t\t\t         W E L C O M E         ");
    System.out.println("\t\t\t              T O              ");
    System.out.println("\t\t\t          H O W R A H          ");
    System.out.println("\t\t\t         S T A T I O N         ");
    System.out.println("\t\t\t  ");
    System.out.println("\n\n\n\n\n\n");
    Thread.sleep(3000);
    for(long i=1;i<=8000000;i++)
    {
      if(i%100000==0)
        System.out.print("�");
    }
  }
  void mainmenu( ) throws IOException
  {
    BufferedReader ob=new BufferedReader(new InputStreamReader(System.in));
    Clear();
    System.out.println("\t\t\t ");
    System.out.println("\t\t\t          MAIN MENU         ");
    System.out.println("\t\t\t ");
    System.out.println("\t\t\t     1. MASTER HANDLING     ");
    System.out.println("\t\t\t     2. RESERVATION         ");
    System.out.println("\t\t\t     3. ENQUIRY             ");
    System.out.println("\t\t\t     4. Exit                ");
    System.out.println("\t\t\t ");
    System.out.println("\n\n\n\n\n\n");
    for(long i=1;i<=8000000;i++)
    {
      if(i%100000==0)
        System.out.print("�");
    }
    System.out.print("\n\t\t\t   Enter Yr Choice  :=> ");
  }
  void masterHandling()
  {
    Clear();
    System.out.println("\t\t    ");
    System.out.println("\t\t       MASTER HANDLING   ");
    System.out.println("\t\t    ");
    System.out.println("\t\t             1. NEW   TRAIN                ");
    System.out.println("\t\t             2. REMOVE   TRAIN             ");
    System.out.println("\t\t             3. CHANGE INFORMATION         ");
    System.out.println("\t\t             4. PREVIOUS                   ");
    System.out.println("\t\t    ");
    System.out.println("\n\n\n\n\n\n");
    for(long i=1;i<=8000000;i++)
    {
      if(i%100000==0)
         System.out.print("�");
    }
    System.out.print("\n\t\t\t   Enter Yr Choice  :=> ");
  }
  void NewTrain()throws IOException
  {
    BufferedReader br =new  BufferedReader(new InputStreamReader(System.in));
    File fil=new File("Howrah.dat");
    DataOutputStream dos=new DataOutputStream(new FileOutputStream(fil,true));
    Clear();
    System.out.println("�������������������������������������������������");
    System.out.println("�        PLEASE FILL THE FOLLOWING DATA         �");
    System.out.println("�������������������������������������������������");
    System.out.print("\tENTER THE NAME OF THE TRAIN:-  ");
    String name=br.readLine();
    System.out.print("\t\tEnter the TRAIN NUMBER     :-  ");
    String trnno=br.readLine();
    System.out.print("\t\tEnter the Fare Rate per KM :-  ");
    double fare=Double.parseDouble(br.readLine());
    System.out.print("\tEnter the START Place      :-  ");
    String start=br.readLine();
    System.out.print("\t\tEnter the Departure Time   :-  ");
    String depart=br.readLine();
    System.out.print("\tENTER THE FIRST STOPPAGE   :-  ");
    String stop1=br.readLine();
    System.out.print("\t\tEnter Distance from START  :-  ");
    double dist1=Double.parseDouble(br.readLine());
    System.out.print("\t\tEnter Arrival At STOP      :-  ");
    String arriv1=br.readLine();
    System.out.print("\t\tEnter Departure from STOP  :-  ");
    String depart1=br.readLine();
    System.out.print("\tENTER THE SECOND STOPPAGE    :-  ");
    String stop2=br.readLine();
    System.out.print("\t\tEnter Distance from START  :-  ");
    double dist2=Double.parseDouble(br.readLine());
    System.out.print("\t\tEnter Arrival At STOP      :-  ");
    String arriv2=br.readLine();
    System.out.print("\t\tEnter Departure from STOP  :-  ");
    String depart2=br.readLine();
    System.out.print("\tENTER THE THIRD STOPPAGE     :-  ");
    String stop3=br.readLine();
    System.out.print("\t\tEnter Distance from START  :-  ");
    double dist3=Double.parseDouble(br.readLine());
    System.out.print("\t\tEnter Arrival At STOP      :-  ");
    String arriv3=br.readLine();
    System.out.print("\t\tEnter Departure from STOP  :-  ");
    String depart3=br.readLine();
    System.out.print("\tENTER THE FOURTH STOPPAGE    :-  ");
    String stop4=br.readLine();
    System.out.print("\t\tEnter Distance from START  :-  ");
    double dist4=Double.parseDouble(br.readLine());
    System.out.print("\t\tEnter Arrival At STOP      :-  ");
    String arriv4=br.readLine();
    System.out.print("\t\tEnter Departure from STOP  :-  ");
    String depart4=br.readLine();
    System.out.print("\tEnter the Last STOPPAGE    :-  ");
    String stop=br.readLine();
    System.out.print("\t\tEnter Distance from START  :-  ");
    double dist=Double.parseDouble(br.readLine());
    System.out.print("\t\tEnter Arrival At Last STOP :-  ");
    String arriv=br.readLine();
    dos.writeUTF(name);
    dos.writeUTF(trnno);
    dos.writeDouble(fare);
    dos.writeUTF(start);
    dos.writeUTF(depart);
    dos.writeUTF(stop1);
    dos.writeDouble(dist1);
    dos.writeUTF(arriv1);
    dos.writeUTF(depart1);
    dos.writeUTF(stop2);
    dos.writeDouble(dist2);
    dos.writeUTF(arriv2);
    dos.writeUTF(depart2);
    dos.writeUTF(stop3);
    dos.writeDouble(dist3);
    dos.writeUTF(arriv3);
    dos.writeUTF(depart3);
    dos.writeUTF(stop4);
    dos.writeDouble(dist4);
    dos.writeUTF(arriv4);
    dos.writeUTF(depart4);
    dos.writeUTF(stop);
    dos.writeDouble(dist);
    dos.writeUTF(arriv);
    System.out.println(" \n\t\t\t�����������������������������������������");
    System.out.println(" \n\t\t\t DATA HAS BEEN ADDED......");
    System.out.println("\n\t\t\t Press Enter To Continue......");
    br.read();
    dos.close();
  }
  void RemoveTrain() throws IOException
  {
    Clear();
    BufferedReader br=new BufferedReader(new InputStreamReader(System.in));
    DataOutputStream dos= new DataOutputStream(new FileOutputStream("temp.dat"));
    DataInputStream dis= new DataInputStream(new FileInputStream("Howrah.dat"));
    String tno,trname,trnno,stop1,arriv1,depart1,stop2,arriv2,depart2,name;
    String stop3,arriv3,depart3,stop4,arriv4,depart4,start,depart,stop,arriv;
    double dist,dist1,dist2,dist3,dist4,fare;
    int found=0;
    System.out.print("\n\nEnter the TRAIN NAME :->> ");
    name=br.readLine();
    System.out.print("Enter the TRAIN NUMBER   :->> ");
    tno=br.readLine();
    boolean flag=true;
    try
    {
       while(true)
       {
         trname=dis.readUTF();
         trnno=dis.readUTF();
         fare=dis.readDouble();
         start=dis.readUTF();
         depart=dis.readUTF();
         stop1=dis.readUTF();
         dist1=dis.readDouble();
         arriv1=dis.readUTF();
         depart1=dis.readUTF();
         stop2=dis.readUTF();
         dist2=dis.readDouble();
         arriv2=dis.readUTF();
         depart2=dis.readUTF();
         stop3=dis.readUTF();
         dist3=dis.readDouble();
         arriv3=dis.readUTF();
         depart3=dis.readUTF();
         stop4=dis.readUTF();
         dist4=dis.readDouble();
         arriv4=dis.readUTF();
         depart4=dis.readUTF();
         stop=dis.readUTF();
         dist=dis.readDouble();
         arriv=dis.readUTF();
         if(name.equalsIgnoreCase(trname) && tno.equalsIgnoreCase(trnno) && found==0)
         {
             System.out.println("Train Name     : "+trname);
             System.out.println("Train Number   : "+tno);
             System.out.println("Start Platform : "+start);
             System.out.println("Stop Platform  : "+stop);
             System.out.println("Total Distance : "+dist);
             System.out.println("Fare per KM    : "+fare);
             System.out.print("\n\nInformation CORRECT to DELETE ? [y/n] :->> ");
             char ans=br.readLine().charAt(0);
             if(ans=='y' || ans=='Y')
             {
               found=1; flag=false;
             }
          }
          if (flag==true)
          {
             dos.writeUTF(name);
             dos.writeUTF(trnno);
             dos.writeDouble(fare);
             dos.writeUTF(start);
             dos.writeUTF(depart);
             dos.writeUTF(stop1);
             dos.writeDouble(dist1);
             dos.writeUTF(arriv1);
             dos.writeUTF(depart1);
             dos.writeUTF(stop2);
             dos.writeDouble(dist2);
             dos.writeUTF(arriv2);
             dos.writeUTF(depart2);
             dos.writeUTF(stop3);
             dos.writeDouble(dist3);
             dos.writeUTF(arriv3);
             dos.writeUTF(depart3);
             dos.writeUTF(stop4);
             dos.writeDouble(dist4);
             dos.writeUTF(arriv4);
             dos.writeUTF(depart4);
             dos.writeUTF(stop);
             dos.writeDouble(dist);
             dos.writeUTF(arriv);
          }
          flag=true;
       }
    }
    catch(EOFException e1){}
    if (found==0)
       System.out.println("\n\nSorry.....NOT FOUND.....");
    else
       System.out.println("\n\nData Updated............");
    dos.close();
    dis.close();
    File ff1=new File("Howrah.dat");
    ff1.delete();
    File ff2 = new File("temp.dat");
    File ff3 = new File("Howrah.dat");
    ff2.renameTo(ff3);
    System.out.print("Press ENTER to GO BACK....");
    br.readLine();
  }
  void ChangeTrain() throws IOException
  {
    Clear();
    BufferedReader br=new BufferedReader(new InputStreamReader(System.in));
    DataOutputStream dos= new DataOutputStream(new FileOutputStream("temp.dat"));
    DataInputStream dis= new DataInputStream(new FileInputStream("Howrah.dat"));
    String tno,trname,trnno,stop1,arriv1,depart1,stop2,arriv2,depart2,name;
    String stop3,arriv3,depart3,stop4,arriv4,depart4,start,depart,stop,arriv;
    double dist,dist1,dist2,dist3,dist4,fare;
    int found=0;
    System.out.print("\n\nEnter the TRAIN NAME :->> ");
    name=br.readLine();
    System.out.print("Enter the TRAIN NUMBER   :->> ");
    tno=br.readLine();
    boolean flag=true;
    try
    {
       while(true)
       {
         trname=dis.readUTF();
         trnno=dis.readUTF();
         fare=dis.readDouble();
         start=dis.readUTF();
         depart=dis.readUTF();
         stop1=dis.readUTF();
         dist1=dis.readDouble();
         arriv1=dis.readUTF();
         depart1=dis.readUTF();
         stop2=dis.readUTF();
         dist2=dis.readDouble();
         arriv2=dis.readUTF();
         depart2=dis.readUTF();
         stop3=dis.readUTF();
         dist3=dis.readDouble();
         arriv3=dis.readUTF();
         depart3=dis.readUTF();
         stop4=dis.readUTF();
         dist4=dis.readDouble();
         arriv4=dis.readUTF();
         depart4=dis.readUTF();
         stop=dis.readUTF();
         dist=dis.readDouble();
         arriv=dis.readUTF();
         if(name.equalsIgnoreCase(trname) && tno.equalsIgnoreCase(trnno) && found==0)
         {
             System.out.println("\t\t\t O L D   I N F O R M A T I O N");
             System.out.println("\t\t\t -----------------------------");
             System.out.println("Train Details...");
             System.out.println("****************");
             System.out.println("\tTrain Name     : "+trname+"\t\tTrain Number   : "+tno);
             System.out.println("\tStart Platform : "+start+"\t\tStop Platform  : "+stop);
             System.out.println("\tTotal Distance : "+dist+"\t\tFare per KM    : "+fare);
             System.out.println("Stoppage Details...");
             System.out.println("*******************");
             System.out.println("\tFirst Stop     : "+stop1+"\t\tThird Stop     : "+stop3);
             System.out.println("\t     Distance  : "+dist1+"\t\t     Distance  : "+dist3);
             System.out.println("\t     Arrival   : "+arriv1+"\t\t     Arrival   : "+arriv3);
             System.out.println("\t     Departure : "+depart1+"\t\t     Departure : "+depart3);
             System.out.println("\tSecond Stop    : "+stop2+"\t\tFourth Stop    : "+stop4);
             System.out.println("\t     Distance  : "+dist2+"\t\t     Distance  : "+dist4);
             System.out.println("\t     Arrival   : "+arriv2+"\t\t     Arrival   : "+arriv4);
             System.out.println("\t     Departure : "+depart2+"\t\t     Departure : "+depart4);
             System.out.println("-------------------------------------------------------------------");
             System.out.print("\n\t\tInformation CORRECT to CHANGE ? [y/n] :->> ");
             char ans=br.readLine().charAt(0);
             if(ans=='y' || ans=='Y')
             {
               found=1;
               System.out.println("�������������������������������������������������");
               System.out.println("�        ENTER THE NEW DETAILS FO TRAIN         �");
               System.out.println("�������������������������������������������������");
               System.out.print("\tENTER THE NAME OF THE TRAIN:-  ");
               name=br.readLine();
               System.out.print("\t\tEnter the TRAIN NUMBER     :-  ");
               trnno=br.readLine();
               System.out.print("\t\tEnter the Fare Rate per KM :-  ");
               fare=Double.parseDouble(br.readLine());
               System.out.print("\tEnter the START Place      :-  ");
               start=br.readLine();
               System.out.print("\t\tEnter the Departure Time   :-  ");
               depart=br.readLine();
               System.out.print("\tENTER THE FIRST STOPPAGE   :-  ");
               stop1=br.readLine();
               System.out.print("\t\tEnter Distance from START  :-  ");
               dist1=Double.parseDouble(br.readLine());
               System.out.print("\t\tEnter Arrival At STOP      :-  ");
               arriv1=br.readLine();
               System.out.print("\t\tEnter Departure from STOP  :-  ");
               depart1=br.readLine();
               System.out.print("\tENTER THE SECOND STOPPAGE    :-  ");
               stop2=br.readLine();
               System.out.print("\t\tEnter Distance from START  :-  ");
               dist2=Double.parseDouble(br.readLine());
               System.out.print("\t\tEnter Arrival At STOP      :-  ");
               arriv2=br.readLine();
               System.out.print("\t\tEnter Departure from STOP  :-  ");
               depart2=br.readLine();
               System.out.print("\tENTER THE THIRD STOPPAGE     :-  ");
               stop3=br.readLine();
               System.out.print("\t\tEnter Distance from START  :-  ");
               dist3=Double.parseDouble(br.readLine());
               System.out.print("\t\tEnter Arrival At STOP      :-  ");
               arriv3=br.readLine();
               System.out.print("\t\tEnter Departure from STOP  :-  ");
               depart3=br.readLine();
               System.out.print("\tENTER THE FOURTH STOPPAGE    :-  ");
               stop4=br.readLine();
               System.out.print("\t\tEnter Distance from START  :-  ");
               dist4=Double.parseDouble(br.readLine());
               System.out.print("\t\tEnter Arrival At STOP      :-  ");
               arriv4=br.readLine();
               System.out.print("\t\tEnter Departure from STOP  :-  ");
               depart4=br.readLine();
               System.out.print("\tEnter the Last STOPPAGE    :-  ");
               stop=br.readLine();
               System.out.print("\t\tEnter Distance from START  :-  ");
               dist=Double.parseDouble(br.readLine());
               System.out.print("\t\tEnter Arrival At Last STOP :-  ");
               arriv=br.readLine();
             }
          }
          dos.writeUTF(name);
          dos.writeUTF(trnno);
          dos.writeDouble(fare);
          dos.writeUTF(start);
          dos.writeUTF(depart);
          dos.writeUTF(stop1);
          dos.writeDouble(dist1);
          dos.writeUTF(arriv1);
          dos.writeUTF(depart1);
          dos.writeUTF(stop2);
          dos.writeDouble(dist2);
          dos.writeUTF(arriv2);
          dos.writeUTF(depart2);
          dos.writeUTF(stop3);
          dos.writeDouble(dist3);
          dos.writeUTF(arriv3);
          dos.writeUTF(depart3);
          dos.writeUTF(stop4);
          dos.writeDouble(dist4);
          dos.writeUTF(arriv4);
          dos.writeUTF(depart4);
          dos.writeUTF(stop);
          dos.writeDouble(dist);
          dos.writeUTF(arriv);
       }
    }
    catch(EOFException e1){}
    if (found==0)
       System.out.println("\n\nSorry.....NOT FOUND.....");
    else
       System.out.println("\n\nData Updated............");
    dos.close();
    dis.close();
    File ff1=new File("Howrah.dat");
    ff1.delete();
    File ff2 = new File("temp.dat");
    File ff3 = new File("Howrah.dat");
    ff2.renameTo(ff3);
    System.out.print("Press ENTER to GO BACK....");
    br.readLine();
  }
  void reservation()
  {
    Clear();
    System.out.println("\t\t    ");
    System.out.println("\t\t         RESERVATION     ");
    System.out.println("\t\t    ");
    System.out.println("\t\t         1.ADD           ");
    System.out.println("\t\t         2.REMOVE        ");
    System.out.println("\t\t         3.PREVIOUS      ");
    System.out.println("\t\t    ");
    System.out.println("\n\n\n\n\n\n");
    for(long i=1;i<=8000000;i++)
    {
      if(i%100000==0)
        System.out.print("�");
    }
    System.out.print("\n\t\t\t   Enter Yr Choice  :=> ");
  }
  void AddReserve() throws IOException
  {
  }
  void RemoveReserve() throws IOException
  {
  }
  void Enquiry()
  {
    Clear();
    System.out.println("\t\t    ");
    System.out.println("\t\t               ENQUIRY           ");
    System.out.println("\t\t    ");
    System.out.println("\t\t           1.TIMING              ");
    System.out.println("\t\t           2.TRAIN INFORMATION   ");
    System.out.println("\t\t           3.PREVIOUS            ");
    System.out.println("\t\t    ");
    System.out.println("\n\n\n\n\n\n");
    for(long i=1;i<=8000000;i++)
    {
      if(i%100000==0)
        System.out.print("�");
    }
    System.out.print("\n\t\t\t   Enter Yr Choice  :=> ");
  }
  void Timing() throws IOException
  {
    Clear();
    BufferedReader br=new BufferedReader(new InputStreamReader(System.in));
    DataInputStream dis= new DataInputStream(new FileInputStream("Howrah.dat"));
    String trname,trnno,stop1,arriv1,depart1,stop2,arriv2,depart2;
    String stop3,arriv3,depart3,stop4,arriv4,depart4,start,depart,stop,arriv;
    String name,plf="",arv="",dep="",tno="",tname="";
    double dist,dist1,dist2,dist3,dist4,fare;
    int found=0,c=0;
    System.out.print("\n\nEnter the PLATFORM NAME for TIMING view :->> ");
    name=br.readLine();
    try
    {
       while(true)
       {
         if(c==0)
         {
           Clear();
           System.out.println("TRAIN NAME \t TRAIN NO \t ARRIVAL \t DEPARTURE");
           System.out.println("---------- \t -------- \t ------- \t ---------");
         }
         trname=dis.readUTF();
         trnno=dis.readUTF();
         fare=dis.readDouble();
         start=dis.readUTF();
         depart=dis.readUTF();
         stop1=dis.readUTF();
         dist1=dis.readDouble();
         arriv1=dis.readUTF();
         depart1=dis.readUTF();
         stop2=dis.readUTF();
         dist2=dis.readDouble();
         arriv2=dis.readUTF();
         depart2=dis.readUTF();
         stop3=dis.readUTF();
         dist3=dis.readDouble();
         arriv3=dis.readUTF();
         depart3=dis.readUTF();
         stop4=dis.readUTF();
         dist4=dis.readDouble();
         arriv4=dis.readUTF();
         depart4=dis.readUTF();
         stop=dis.readUTF();
         dist=dis.readDouble();
         arriv=dis.readUTF();
         if(name.equalsIgnoreCase(start))
         {
            plf=start;tno=trnno; tname=trname;
            arv="        ";dep=depart; found=1;
         }
         if(name.equalsIgnoreCase(stop1))
         {
            plf=stop1; tno=trnno; tname=trname;
            arv=arriv1;dep=depart1; found=1;
         }
         if(name.equalsIgnoreCase(stop2))
         {
            plf=stop2; tno=trnno; tname=trname;
            arv=arriv2;dep=depart2; found=1;
         }
         if(name.equalsIgnoreCase(stop3))
         {
            plf=stop3; tno=trnno; tname=trname;
            arv=arriv3;dep=depart3; found=1;
         }
         if(name.equalsIgnoreCase(stop4))
         {
            plf=stop4; tno=trnno; tname=trname;
            arv=arriv4;dep=depart4; found=1;
         }
         if(name.equalsIgnoreCase(stop))
         {
            plf=stop; tno=trnno; tname=trname;
            arv=arriv;dep="        "; found=1;
         }
         if(found==1)
         {
            System.out.println(tname+"\t"+tno+"\t"+arv+"\t"+dep);
            c++;
            if(c==18)
            {
               c=0;
               System.out.println("------------------------------------------------------");
               System.out.print("\t\t\tPress Enter to VIEW NEXT >>");
               br.readLine();
            }
         }
         found=0;
       }
    }
    catch(EOFException e1){}
    System.out.println("----------------------------------------------------");
    dis.close();
    System.out.print("Press ENTER to GO BACK....");
    br.readLine();
  }
  void TrainInformation() throws IOException
  {
    Clear();
    BufferedReader br=new BufferedReader(new InputStreamReader(System.in));
    DataInputStream dis= new DataInputStream(new FileInputStream("Howrah.dat"));
    String tno,trname,trnno,stop1,arriv1,depart1,stop2,arriv2,depart2,name;
    String stop3,arriv3,depart3,stop4,arriv4,depart4,start,depart,stop,arriv;
    double dist,dist1,dist2,dist3,dist4,fare;
    int found=0;
    System.out.print("\n\nEnter the TRAIN NAME :->> ");
    name=br.readLine();
    System.out.print("Enter the TRAIN NUMBER   :->> ");
    tno=br.readLine();
    try
    {
       while(true)
       {
         trname=dis.readUTF();
         trnno=dis.readUTF();
         fare=dis.readDouble();
         start=dis.readUTF();
         depart=dis.readUTF();
         stop1=dis.readUTF();
         dist1=dis.readDouble();
         arriv1=dis.readUTF();
         depart1=dis.readUTF();
         stop2=dis.readUTF();
         dist2=dis.readDouble();
         arriv2=dis.readUTF();
         depart2=dis.readUTF();
         stop3=dis.readUTF();
         dist3=dis.readDouble();
         arriv3=dis.readUTF();
         depart3=dis.readUTF();
         stop4=dis.readUTF();
         dist4=dis.readDouble();
         arriv4=dis.readUTF();
         depart4=dis.readUTF();
         stop=dis.readUTF();
         dist=dis.readDouble();
         arriv=dis.readUTF();
         if(name.equalsIgnoreCase(trname) && tno.equalsIgnoreCase(trnno) && found==0)
         {
             System.out.println("\t\t\t T R A I N   I N F O R M A T I O N");
             System.out.println("\t\t\t ---------------------------------");
             System.out.println("Train Details...");
             System.out.println("****************");
             System.out.println("\tTrain Name     : "+trname+"\t\tTrain Number   : "+tno);
             System.out.println("\tStart Platform : "+start+"\t\tStop Platform  : "+stop);
             System.out.println("\tTotal Distance : "+dist+"\t\tFare per KM    : "+fare);
             System.out.println("Stoppage Details...");
             System.out.println("*******************");
             System.out.println("\tFirst Stop     : "+stop1+"\t\tThird Stop     : "+stop3);
             System.out.println("\t     Distance  : "+dist1+"\t\t     Distance  : "+dist3);
             System.out.println("\t     Arrival   : "+arriv1+"\t\t     Arrival   : "+arriv3);
             System.out.println("\t     Departure : "+depart1+"\t\t     Departure : "+depart3);
             System.out.println("\tSecond Stop    : "+stop2+"\t\tFourth Stop    : "+stop4);
             System.out.println("\t     Distance  : "+dist2+"\t\t     Distance  : "+dist4);
             System.out.println("\t     Arrival   : "+arriv2+"\t\t     Arrival   : "+arriv4);
             System.out.println("\t     Departure : "+depart2+"\t\t     Departure : "+depart4);
             System.out.println("-------------------------------------------------------------------");
         }
       }
    }
    catch(EOFException e1){}
    if (found==0)
       System.out.println("\n\nSorry.....NOT FOUND.....");
    dis.close();
    System.out.print("Press ENTER to GO BACK....");
    br.readLine();
  }
  public static void main(String arg[])throws IOException
  {
    BufferedReader br=new BufferedReader(new InputStreamReader(System.in));
    Railway ob=new Railway();
    ob.Clear();
    try{
    	ob.Show();
    	ob.sow();
	}
	catch(Exception ie){
		ie.printStackTrace();
	}
    int opta=0;
    while (opta!=4)
    {
       ob.Clear();
       ob.mainmenu();
       opta=Integer.parseInt(br.readLine());
       switch(opta)
       {
         case 1:
            ob.Clear();
            int opta1=0;
            while (opta1!=4)
            {
               ob.masterHandling();
               opta1=Integer.parseInt(br.readLine());
               switch(opta1)
               {//heat down (to UpperCase(is.equalsIgnoreCase))
                 case 1:
                    ob.Clear();
                    ob.NewTrain();
                    break;
                 case 2:
                    ob.Clear();
                    ob.RemoveTrain();
                    break;
                 case 3:
                    ob.Clear();
                    ob.ChangeTrain();
                    break;
                 case 4:
                    break;
                 default:
                    System.out.println("Invalid Entry....");
                    System.out.println("Press Enter and Try Again....");
                    br.readLine();
               }
            }
            break;
         case 2:
            ob.Clear();
            int opta2=0;
            while (opta2!=3)
            {
               ob.reservation();
               opta2=Integer.parseInt(br.readLine());
               switch(opta2)
               {
                 case 1:
                    ob.Clear();
                    ob.AddReserve();
                    break;
                 case 2:
                    ob.Clear();
                    ob.RemoveReserve();
                    break;
                 case 3:
                    break;
                 default:
                    System.out.println("Invalid Entry....");
                    System.out.println("Press Enter and Try Again....");
                    br.readLine();
               }
            }
            break;
         case 3:
            ob.Clear();
            int opta3=0;
            while (opta3!=3)
            {
               ob.Enquiry();
               opta3=Integer.parseInt(br.readLine());
               switch(opta3)
               {
                 case 1:
                    ob.Clear();
                    ob.Timing();
                    break;
                 case 2:
                    ob.Clear();
                    ob.TrainInformation();
                    break;
                 case 3:
                    break;
                 default:
                    System.out.println("Invalid Entry....");
                    System.out.println("Press Enter and Try Again....");
                    br.readLine();
               }
            }
            break;
         case 4:
                ob.Clear();
                System.out.println("\nTeacher-in-charge:"+"\n\t Tushar Kanti Sasmal");
                System.out.println("\n\n\n\t\t Completed By:- ");
                System.out.println("\n\n\n\t\t\t  SUMIT KUMAR. \n\t\t\t   Roll-29 \n\t\t\t    Sec-A");
            break;
         default:
            System.out.println("Invalid Entry....");
            System.out.println("Press Enter and Try Again....");
            br.readLine();
       }
    }
  }
}


its just a java based program
