Exercise 1
Create a program that asks the user to enter their name and their age. Print out a message that tells how many years they have to be 100 years old.


void main() {
  Exercicio1("Matheus", 23);
}

Exercicio1(String name, int idade) {
  int result = 100 - idade;
  print("$name, voce possui $idade anos , faltam $result anos para completar 100 anos de idade.");
}
