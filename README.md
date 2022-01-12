package com.company;

import java.util.Scanner;

public class Main {

            public static void main(String[] args) {
                {
                    int firstNumber ;
                    int secondNumber ;
                    Scanner input = new Scanner(System.in);
                    System.out.print("input first number:");
                    firstNumber = input.nextInt();
                    System.out.print("input second number:");
                    secondNumber= input.nextInt();

                    System.out.println(firstNumber + "+" + secondNumber + "=" + (firstNumber+secondNumber));
                    System.out.println(firstNumber + "-" + secondNumber + "=" + (firstNumber-secondNumber));
                    System.out.println(firstNumber + "X" + secondNumber + "=" + (firstNumber*secondNumber));
                    System.out.println(firstNumber + "/" +secondNumber + "=" + (firstNumber/secondNumber));
                    System.out.println(firstNumber + "mod" +secondNumber + "=" + (firstNumber%secondNumber));

                }
            }
        }
