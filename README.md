# sample-1
講習会のサンプルです。
#include <iostream>

#include <array>



int main(void) {

	std::array <int, 5> a = { 10, 10, 10, 10, 10 };



	std::array <int, 5> b;

	for (int i = 0; i<5; i++) {

		b[i] = 10;

	}



	std::array <int, 5> c;

	for (int &stock : c) {

		stock = 10;

	}



	for (int i = 0; i<5; i++) {

		std::cout << a[i] << " ";

	}

	std::cout << std::endl;



	for (int stock : b) {

		std::cout << stock << " ";

	}

	std::cout << std::endl;



	for (int stock : c) {

		std::cout << stock << " ";

	}

	std::cout << std::endl;



	return 0;

}
