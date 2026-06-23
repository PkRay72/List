# List

import java.util.*;
class ListDemo
{
   public static void main(String args[])
   {
      List<String>list = new ArrayList<>();
      list.add("MIT");
      list.add("MIET");
      list.add("SIT");
      list.add("KIET");
      list.add("BIT");

   System.out.println(list);
   System.out.println(list.get(3));
   System.out.println(list.set(3,"RIET"));
   System.out.println(list);
   list.add(1,"DIET");
   System.out.println(list);
   System.out.println(list.remove(5));
   System.out.println(list);
   System.out.println(list.indexOf("MIET"));
   System.out.println(list.lastIndexOf("SIT"));
   System.out.println(list.subList(0,3));
   System.out.println(list);
    }
}
   
