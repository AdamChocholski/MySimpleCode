# MySimpleCode
My Scribbles in Java


This code just simply creates multiplicacion table dependent of amount of rows and columns required by user.



First we Put in the amount of row and then the amounts of columns 



package com.company;

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        Scanner ent = new Scanner(System.in);

        System.out.println("Podaj liczbę wierszy: ");
        int wiersze =ent.nextInt();
        System.out.println("Podaj liczbę kolumn: ");
        int kolumny =ent.nextInt();

        System.out.println("\n=============\n");
	for(int j=1;j <= wiersze;j++)
    {
        for(int i=1;i < kolumny;i++){
            System.out.print(i * j + "\t");

        }
        System.out.println();
    }
    }
}


Thats all for now folks it's really the begining so I hope I will get better
