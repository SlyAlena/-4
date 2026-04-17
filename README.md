# Bilet4


	#include <iostream>
	using namespace std;

	int main() {
	setlocale(LC_ALL, "Russian");
	int age;
	cin >> age;

	if(age >= 18) cout << "Ты можешь голосовать!";
	else cout << "Ты не можешь голосовать. Тебе нет 18!";
	}

