package arraylist;

import java.util.ArrayList;

public class ArrayListDemo{

    public static void main(String[] args){
        ArrayList<Integer> arr= new ArrayList<>(20);
        arr.add(10);
        arr.add(20);
        arr.add(30);
        arr.add(1,80)

        System.out.println(arr.size());
        System.out.println(arr.get(1));

    }
}
