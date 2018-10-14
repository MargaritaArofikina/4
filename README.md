# 4

//Напишите программу , находящую в массиве сумму элементов делящихся либо на 72, либо 27 (не вместе).

#include <iostream>
using namespace std;
int main() {

	int N, a, p_darr, i;

	cin  >> N;

	for (i = 0; i< N; i++) {
		cin >> p_darr[i];

	}

	a = 0;
	for (i = 0; i < N; i++) {

		if (((p_darr[i] % 27 == 0) && (p_darr[i] % 72 != 0)) || ((p_darr[i] % 72 == 0) && (p_darr[i] % 27 != 0))) a = p_darr[i] + a;

		cout << a;


	}

	return 0;

}
