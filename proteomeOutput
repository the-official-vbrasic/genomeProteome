/*
DNA to Amino Acid Sequencer
Brinda Venkataramani
April 12th, 2015
Version 1.0
*/

import java.util.Scanner; 

class proteomeOutput {

   public static void main (String[] args) throws java.lang.Exception {
   
      Scanner userInput = new Scanner(System.in); // Declares scanner.
      String DNACode = ""; // Initializes null string of codons.
      boolean loopCheck = true; // Boolean check to quit/continue looping.
      String codonAcid[][] = new String[64][2];
      
      // Initialize the codonAcid array... This would be more efficient if I just read from a file.
      
      codonAcid[0][0] = "TTT";
      codonAcid[0][1] = "Phe";
      codonAcid[1][0] = "TTC";
      codonAcid[1][1] = "Phe";
      codonAcid[2][0] = "TTA";
      codonAcid[2][1] = "Leu";
      codonAcid[3][0] = "TTG";
      codonAcid[3][1] = "Leu";
      codonAcid[4][0] = "CTT";
      codonAcid[4][1] = "Leu"; 
      codonAcid[5][0] = "CTC";
      codonAcid[5][1] = "Leu";
      codonAcid[6][0] = "CTA";
      codonAcid[6][1] = "Leu";
      codonAcid[7][0] = "CTG";
      codonAcid[7][1] = "Leu";
      codonAcid[8][0] = "ATT";
      codonAcid[8][1] = "Ile";
      codonAcid[9][0] = "ATC";
      codonAcid[9][1] = "Ile";
      codonAcid[10][0] = "ATA";
      codonAcid[10][1] = "Ile";
      codonAcid[11][0] = "ATG";
      codonAcid[11][1] = "Met";
      codonAcid[12][0] = "GTT";
      codonAcid[12][1] = "Val";
      codonAcid[13][0] = "GTC";
      codonAcid[13][1] = "Val";
      codonAcid[14][0] = "GTA";
      codonAcid[14][1] = "Val";
      codonAcid[15][0] = "GTG";
      codonAcid[15][1] = "Val";
      codonAcid[16][0] = "TCT";
      codonAcid[16][1] = "Ser";
      codonAcid[17][0] = "TCC";
      codonAcid[17][1] = "Ser";
      codonAcid[18][0] = "TCA";
      codonAcid[18][1] = "Ser";
      codonAcid[19][0] = "TCG";
      codonAcid[19][1] = "Ser";
      codonAcid[20][0] = "CCT";
      codonAcid[20][1] = "Pro";
      codonAcid[21][0] = "CCC";
      codonAcid[21][1] = "Pro";
      codonAcid[22][0] = "CCA";
      codonAcid[22][1] = "Pro";
      codonAcid[23][0] = "CCG";
      codonAcid[23][1] = "Pro";
      codonAcid[24][0] = "ACT";
      codonAcid[24][1] = "Thr";
      codonAcid[25][0] = "ACC";
      codonAcid[25][1] = "Thr";
      codonAcid[26][0] = "ACA";
      codonAcid[26][1] = "Thr";
      codonAcid[27][0] = "ACG";
      codonAcid[27][1] = "Thr";
      codonAcid[28][0] = "GCT";
      codonAcid[28][1] = "Ala";
      codonAcid[29][0] = "GCC";
      codonAcid[29][1] = "Ala";
      codonAcid[30][0] = "GCA";
      codonAcid[30][1] = "Ala";
      codonAcid[31][0] = "GCG";
      codonAcid[31][1] = "Ala";
      codonAcid[32][0] = "TAT";
      codonAcid[32][1] = "Tyr";
      codonAcid[33][0] = "TAC";
      codonAcid[33][1] = "Tyr";
      codonAcid[34][0] = "TAA";
      codonAcid[34][1] = "STOP";
      codonAcid[35][0] = "TAG";
      codonAcid[35][1] = "STOP";
      codonAcid[36][0] = "CAT";
      codonAcid[36][1] = "His";
      codonAcid[37][0] = "CAC";
      codonAcid[37][1] = "His";
      codonAcid[38][0] = "CAA";
      codonAcid[38][1] = "Gln";
      codonAcid[39][0] = "CAG";
      codonAcid[39][1] = "Gln";
      codonAcid[40][0] = "AAT";
      codonAcid[40][1] = "Asn";
      codonAcid[41][0] = "AAC";
      codonAcid[41][1] = "Asn";
      codonAcid[42][0] = "AAA";
      codonAcid[42][1] = "Lys";
      codonAcid[43][0] = "AAG";
      codonAcid[43][1] = "Lys";
      codonAcid[44][0] = "GAT";
      codonAcid[44][1] = "Asp";
      codonAcid[45][0] = "GAC";
      codonAcid[45][1] = "Asp";
      codonAcid[46][0] = "GAA";
      codonAcid[46][1] = "Glu";
      codonAcid[47][0] = "GAG";
      codonAcid[47][1] = "Glu";
      codonAcid[48][0] = "TGT";
      codonAcid[48][1] = "Cys";
      codonAcid[49][0] = "TGC";
      codonAcid[49][1] = "Cys";
      codonAcid[50][0] = "TGA";
      codonAcid[50][1] = "Phe";
      codonAcid[51][0] = "TGG";
      codonAcid[51][1] = "STOP";
      codonAcid[52][0] = "CGT";
      codonAcid[52][1] = "Arg";
      codonAcid[53][0] = "CGC";
      codonAcid[53][1] = "Arg";
      codonAcid[54][0] = "CGA";
      codonAcid[54][1] = "Arg";
      codonAcid[55][0] = "CGG";
      codonAcid[55][1] = "Arg";
      codonAcid[56][0] = "AGT";
      codonAcid[56][1] = "Ser";
      codonAcid[57][0] = "AGC";
      codonAcid[57][1] = "Ser";
      codonAcid[58][0] = "AGA";
      codonAcid[58][1] = "Arg";
      codonAcid[59][0] = "AGG";
      codonAcid[59][1] = "Arg";
      codonAcid[60][0] = "GGT";
      codonAcid[60][1] = "Gly";
      codonAcid[61][0] = "GGC";
      codonAcid[61][1] = "Gly";
      codonAcid[62][0] = "GGA";
      codonAcid[62][1] = "Gly";
      codonAcid[63][0] = "GGG";
      codonAcid[63][1] = "Gly";
      
      // End array initialization
         
      while (loopCheck) {
         System.out.println("Please enter the string of codons to be sequenced. (No spaces. Uppercase.)");  
         DNACode = userInput.nextLine(); // Gets mRNA code.
         
         if (DNACode.length()%3 !=0){ // Codons are triplets. Throws codes which don't have a multiple of three chars.
         
            System.out.println("Sorry. That's not a valid mRNA sequence.");
         
         }
         
         else {
         
            String codonArray[] = DNACode.split("(?<=\\G...)"); // Java regex to split by three chars into an array of triplets.
            int arrayLength = codonArray.length;
            
            for (int j=0; j<arrayLength; j++) { // Returns value at codonArray.
            
               for (int k=0; k<64; k++) { // Returns value at codonAcid.
               
                  if (codonArray[j].equals(codonAcid[k][0])) { // Compares.
                  
                     System.out.println(codonAcid[k][1]); // Output.
                  
                  }
               
               }
            
            }
            
            System.out.println("Thanks for using the program!");
            loopCheck = false;
            
         }
         
      }
    
   }

}

