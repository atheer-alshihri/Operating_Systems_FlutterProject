void main() { 
 List <String> names = ['Khalid', 'Ali','Sameer'];
 List <double> grades = [99.3, 87.7, 65.7];
 String score = '';
 int i = 0;
 while(i < 3){
 var G = grades[i];
 if(G >= 95){
 score = 'A+';
 }
 else if(G >= 90){
 score = 'A';
 }
 else if(G >= 85){
 score = 'B+';
 }
 else if(G >= 80){
 score = 'B';
 }
 else if(G >= 75){
 score = 'C+';
 }
 else if(G >= 70){
 score = 'C';
 }
 else if(G >= 65){
 score = 'D+';
 }
 else if(G >= 60){
 score = 'D';
 }
 else{
 score = 'F';
 }
 
 print(names[i]+" "+score);
 i++;
 }
}
