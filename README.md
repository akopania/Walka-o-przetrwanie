# Walka-o-przetrwanie
<!-- komentaSZ -->
<!-- PLAN: Kreator planu treningowego z doradca -->

<!-- Ctoolkit - biblioteka do przetwarzania tekstu cpp -->

import java.io.BufferedReader;
import java.io.File;
import java.io.IOException;
import java.io.InputStreamReader;
import java.io.FileNotFoundException;
import java.util.Scanner;
import java.io.*;

public class Main {
	static void wyswietlMenu(){
		System.out.println("Dziennik treningowy\n 1) Stworz plan treningowy\n 2) Usun plan treningowy\n 3) Wyswietl plan treningowy\n 4) Wylacz program\n");
		
	public static void main(String[] args) throws IOException{
		BufferedReader input = new BufferedReader(new InputStreamReader(System.in));
		wyswietlMenu();
		String wybor=input.readLine();
			switch(wybor){
			case "1":
			case "2":	
			case "3":
			case "4":	
			default:
				System.out.println("Dokonales zlego wyboru, wybierz ponownie\n");}
				break;
			}
		}
