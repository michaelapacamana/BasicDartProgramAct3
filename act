import 'dart:io';

void main() {
  
  // ignore: prefer_typing_uninitialized_variables
  int n1, n2; var userChoice;
  stdout.write('Enter first number: ');
  n1 = int.parse(stdin.readLineSync()!);
  stdout.write('Enter second number: ');
  n2 = int.parse(stdin.readLineSync()!);
  
  String message = '''
Select Operation
1. Addition
2. Subtraction
3. Multiplication
4. Division
You choice?''';
 stdout.write(message);
  int.parse(stdin.readLineSync()!);
  
  
  if(userChoice == 1) {
    print('Sum = ${n1+n2}');
  }
  
    if(userChoice == 2 ){
      print('Difference = ${n1-n2}');
    }
  
  if(userChoice == 3 ){
      print('Product = ${n1*n2}');  
  }
  
    if(userChoice == 4 ){
      print('Division = ${n1/n2}');
    }
  
    if (userChoice > 4){
      print('Invalid Choice');
    }
}